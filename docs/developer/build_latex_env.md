# Building and Installing `osdag-latex-env` for Osdag Development

> [!IMPORTANT]
> This guide is intended **only for Osdag developers** building or modifying Osdag from source.
>
> If you are installing Osdag using the official installer, **you do not need this guide**. The LaTeX environment is installed automatically.

> [!IMPORTANT]
> `osdag-latex-env` **must be built and installed using Conda**.
>
> **Do not use** `pip install`, `pip install -e`, or any other pip-based installation method. Pip installs only the Python package and **does not install the bundled LaTeX runtime** required by Osdag.

---

# Supported Platforms

`osdag-latex-env` supports:

- Windows
- Linux
- macOS

This document uses platform-independent commands wherever possible.
Platform-specific paths are shown only where necessary.

---

# Overview

`osdag-latex-env` provides a self-contained, cross-platform LaTeX runtime used by Osdag for PDF report generation.

This guide explains how to:

1. Prepare a development machine.
2. Build the Conda package.
3. Install it into a Conda environment.
4. Verify that the installation is working.

---

# System Prerequisites

## 1. Install Git (Optional)

Git is required only if you intend to clone the repository.

Verify Git installation:

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

Example output:

```text
conda 26.x.x
```

If the command is not recognized, restart your terminal (or your computer) and try again.

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

Verify:

```bash
conda build --version
```

---

# Obtain the Source Code

You may either clone the repository or download it as a ZIP archive.

## Option 1 — Clone the Repository

```bash
git clone <repository-url>
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

The repository can be located anywhere on your computer.

---

# Build the Conda Package

From the repository root, run:

```bash
conda build conda-recipe
```

The build process may take several minutes.

If successful, Conda creates a package under:

```text
<conda-root>/conda-bld/
```

For example:

**Windows**

```text
D:\Programs\MiniConda\conda-bld\win-64\
```

**Linux**

```text
~/miniconda3/conda-bld/linux-64/
```

---

# Install the Package

Install the package built in the previous step:

```bash
conda install --use-local osdag_latex_env
```

Conda will automatically locate the package in the local build cache.

---

# Verify the Installation

Run:

```bash
python -c "from osdag_latex_env.__main__ import OsdagLatexEnv; print(OsdagLatexEnv().available)"
```

Expected output:

```text
True
```

If `True` is printed, the package has been installed successfully.

---

# Next Step

`osdag-latex-env` is now ready for use by Osdag.

No additional configuration is required.

Osdag will automatically detect the installed LaTeX environment when generating PDF reports.
