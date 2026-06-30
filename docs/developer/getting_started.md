# Getting Started with Osdag Development from Source

> [!IMPORTANT]
> This guide is intended for developers building Osdag from source.
>
> If you are installing Osdag using the official installer, this guide does not apply.

## Overview

This guide helps developers set up a complete Osdag development environment.

The primary repository is:

- **Osdag**
  - https://github.com/osdag-admin/Osdag

A complete development setup may also require supporting repositories that provide additional functionality.

---

## Development Setup

The recommended setup sequence is:

1. Install Conda.
2. Clone the Osdag repository.
3. Create the Osdag development environment.
4. Build and install any required supporting packages.
5. Build and run Osdag.

---

## Supporting Components

Some Osdag features require additional supporting packages.

### osdag-latex-env

`osdag-latex-env` provides the self-contained LaTeX runtime used by Osdag for LaTeX-based report generation.

Without `osdag-latex-env`:

- Design calculations continue to work.
- The graphical user interface continues to work.
- Most Osdag features continue to work.
- PDF report preview and PDF report generation are **not available**.

Developers who intend to use or test PDF report generation should build and install `osdag-latex-env`.

See:

- [Building and Installing osdag-latex-env](build_latex_env.md)

---

## Build Osdag

Once all required supporting packages have been installed, continue with the Osdag build instructions.

See:

- [Build Osdag](build_osdag.md)
