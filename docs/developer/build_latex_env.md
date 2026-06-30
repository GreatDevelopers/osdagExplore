# Building and Installing `osdag-latex-env`

> [!NOTE]
> This document describes how to build and install **`osdag-latex-env`**, a supporting package used by Osdag for LaTeX-based PDF report generation.
>
> If you are setting up Osdag for development, begin with **[Getting Started with Osdag Development](getting_started.md)** and return here when instructed.
>
> If you are installing Osdag using the official installer, **you do not need this guide**. The LaTeX environment is installed automatically.

> [!IMPORTANT]
> `osdag-latex-env` **must be built and installed using Conda**.
>
> **Do not use** `pip install`, `pip install -e`, or any other pip-based installation method.
>
> Pip installs only the Python package. It **does not** install the bundled LaTeX runtime and supporting assets required by Osdag. Consequently, a pip installation is incomplete and cannot be used for Osdag PDF report generation.

---

# Supported Platforms

`osdag-latex-env` supports:

- Windows
- Linux
- macOS

This document uses platform-independent commands wherever possible. Platform-specific paths are shown only where necessary.

---

# Overview

`osdag-latex-env` provides a self-contained, cross-platform LaTeX runtime used by Osdag for generating PDF reports.

This guide explains how to:

1. Prepare a development machine.
2. Obtain the source code.
3. Build the Conda package.
4. Install it into a Conda environment.
5. Verify that the installation is working.

---

# Requirements

Before proceeding, ensure the following software is available:

- Conda (Miniconda, Anaconda or Miniforge)
- Python 3.11–3.13
- Git (optional, only if cloning the repository)

---

# System Prerequisites

## 1. Install Git (Optional)

Git is required only if you intend to clone the repository.

Verify the installation:

```bash
git --version
```

If Git is not installed, either:

- Install Git from https://git-scm.com/
- **or**
- Download the repository as a ZIP archive from GitHub.

---

## 2. Install Conda

`osdag-latex-env` is distributed as a Conda package.

Install one of the following:

- Miniconda (recommended)
- Anaconda
- Miniforge

Verify the installation:

```bash
conda --version
```

Example:

```text
conda 26.x.x
```

If the command is not recognised, restart your terminal (or computer) and try again.

---

# Project Prerequisites

## 3. Create or Activate the Development Environment

If you already have an Osdag development environment, activate it:

```bash
conda activate osdag-dev
```

Otherwise create one first:

```bash
conda create -n osdag-dev python=3.13
conda activate osdag-dev
```

> Use the Python version compatible with the current Osdag development environment.

---

## 4. Install `conda-build`

Verify whether `conda-build` is already installed:

```bash
conda list conda-build
```

If it is not installed:

```bash
conda install -n base conda-build
```

Verify the installation:

```bash
conda build --version
```

---

# Obtain the Source Code

The repository may be cloned or extracted into **any convenient directory**. It **does not** need to be located inside the Osdag source tree.

You may either clone the repository or download it as a ZIP archive.

## Option 1 — Clone the Repository

```bash
git clone https://github.com/osdag-admin/osdag-latex-env.git
cd osdag-latex-env
```

## Option 2 — Download ZIP

1. Download the repository ZIP from GitHub.
2. Extract it.
3. Open a terminal.
4. Change to the repository root.

Example:

```bash
cd path/to/osdag-latex-env
```

---

# Build the Conda Package

From the repository root, run:

```bash
conda build conda-recipe
```

The build process may take several minutes.

If the build completes successfully, Conda creates a package similar to:

```text
osdag_latex_env-<version>-<build>.conda
```

The package is placed in the local Conda build cache.

Typical locations are:

**Windows**

```text
<conda-root>\conda-bld\win-64\
```

Example:

```text
D:\Programs\MiniConda\conda-bld\win-64\
```

**Linux**

```text
<conda-root>/conda-bld/linux-64/
```

Example:

```text
~/miniconda3/conda-bld/linux-64/
```

**macOS**

```text
<conda-root>/conda-bld/osx-64/
```

or

```text
<conda-root>/conda-bld/osx-arm64/
```

depending on the platform.

---

# Install the Package

Install the package into the active Conda environment:

```bash
conda install --use-local osdag_latex_env
```

The `--use-local` option instructs Conda to install the package from the local Conda build cache created in the previous step.

---

# Verify the Installation

Run:

```bash
python -c "from osdag_latex_env.__main__ import OsdagLatexEnv; x=OsdagLatexEnv(); print('Available:', x.available); print('PDFLaTeX:', x.pdflatex)"
```

Expected output:

```text
Available: True
PDFLaTeX: <path-to-pdflatex>
```

For example:

```text
Available: True
PDFLaTeX: D:\Programs\MiniConda\envs\osdag-dev\Library\share\osdag_latex_env\bin\x86_64-windows\pdflatex.exe
```

`Available: True` confirms that the bundled LaTeX runtime has been successfully located and is ready for use.

---

# Next Step

`osdag-latex-env` is now ready for use.

No additional configuration is required.

When generating PDF reports, Osdag automatically detects and uses the installed `osdag-latex-env` package.

Continue with:

- **[Build Osdag](build_Osdag.md)**
