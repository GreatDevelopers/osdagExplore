## Local built of osdag

## Technical Brief: Upstream Structural Integrity Failures

The current dependency management configuration within the official Osdag repositories contains architectural contradictions:

### 1. Dual-Qt Framework Pollution

The `pyproject.toml` file declares both `PyQt5` and `PySide6` concurrently in its `dependencies` array.

* **The Conflict:** `PyQt5` binds to the legacy Qt5 C++ runtime, while `PySide6` binds to the modern Qt6 framework.
* **The Impact:** When compiled via `pip`, Python attempts to fetch and overlay conflicting binary bindings, corrupting the active interpreter namespace. This directly triggers the fatal dynamic-link library collision (`ImportError: DLL load failed while importing QtWidgets`).

### 2. Disparate Version Declarations

The underlying configuration scripts lack synchronization across sub-modules:

* The main project layer restricts execution to `requires-python = ">= 3.10,<3.13"`.
* Sibling components like `osdag-latex-env` lack uniform locks, exposing the system to runtime failure when executed on Python 3.12+ engines.

### 3. Namespace Collision Risk

Both `osdag-core` and `Osdag` compile directly into the identical top-level global module namespace (`osdag`), meaning subsequent development-mode tracking (`pip install -e .`) can silently unregister previously mapped internal routes if dependencies are processed indiscriminately with automated resolution trees.

---

## Absolute Local Build Procedure

Uses:

1. Python 3.12.13,
2. PySide6 6.11.1,
3. Qt6 6.11.1

### Step 1: Repair the Source Metadata

Before initialising installation, you must scrub the hardcoded upstream dependency bug.

Open `osdag-core\pyproject.toml` in your text editor. Locate the `dependencies` mapping block, and **delete** `"PyQt5"` entirely.

```toml
# Corrected block inside pyproject.toml
dependencies = ["PySide6", "requests", "pylatex", "numpy", "PyYaml", "PyGithub", "Click", "navcube"]

```

### Step 2: Establish a Clean Environmental Baseline

Open your native command window, append the missing shell engine parameters to protect initialization hooks, and purge previous faulty installations:

```cmd
:: Enforce PowerShell paths for background C++ compilation scripts
set PATH=%PATH%;C:\Windows\System32\WindowsPowerShell\v1.0\

:: Deactivate and eliminate the corrupt development block
conda deactivate
conda env remove -n osdag-dev --yes
conda clean --packages --tarballs --yes

```

### Step 3: Provision and Inject Native Structural Binaries

Build the foundational target environment using your verified operational production parameters. We isolate heavy geometry matrices entirely within Conda's tracking network:

```cmd
:: Instantiate the exact base interpreter configuration
conda create -n osdag-dev python=3.12.13 conda-forge::pyside6=6.11.1 conda-forge::qt6-main=6.11.1 -c conda-forge -y
conda activate osdag-dev

:: Allocate CAD kernels and text processors from dedicated engineering channels
conda install -c conda-forge -c geompy pythonocc-core=7.9.3 smesh=9.9.0.0 shapely pandas openpyxl matplotlib-base navcube lark markdown -y

```

### Step 4: Map Local Source Roots (Editable Governance Mode)

Navigate to your active fork repositories. We execute installations utilizing the `--no-deps` modifier. This locks our core binary layout down, preventing `pip` from re-introducing foreign artifacts:

```cmd
cd osdag-core
pip install -e . --no-deps

cd Osdag
pip install -e . --no-deps

cd osdag-latex-env
pip install -e . --no-deps

```

### Step 5: Execute and Run Verification

Confirm that structural compilation pathways pass diagnostic validation rules, and launch the platform:

```cmd
python -c "import markdown, openpyxl, pandas, pylatex, navcube, lark, yaml, OCC.Core, shapely; print('>>> EXCELLENT: All structural layers authenticated! <<<')"
osdag

```
