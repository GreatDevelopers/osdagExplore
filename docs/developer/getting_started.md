# Getting Started with Osdag Development

This guide helps developers set up a complete Osdag development environment from source.

## Overview

Osdag consists of multiple repositories. Depending on the component you are working on, you may need one or more of them.

The primary repository is:

- **Osdag**
  - https://github.com/osdag-admin/Osdag

Some features rely on supporting repositories.

For example, PDF report generation requires the **osdag-latex-env** package.

---

# Development Setup

The recommended setup sequence is:

1. Install Conda.
2. Clone the Osdag repository.
3. Create the Osdag development environment.
4. Build and install supporting packages.
5. Run Osdag.

---

# Supporting Packages

## osdag-latex-env

Osdag uses `osdag-latex-env` to generate PDF reports.

Before building or running Osdag with PDF report generation enabled, build and install this package.

See:

**Building and Installing osdag-latex-env**

[Build and install build-latex-env](build_latex_env.md)

---

# Build Osdag

Once all required supporting packages have been installed, continue with the Osdag build instructions.

See:

**Building Osdag**

[Build Osdag](build_Osdag.md)
