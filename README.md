# NMC LESS Boilerplate

## Overview

This boilerplate contains base LESS files and site-specific LESS files. The base LESS files exist in the `base/` directory and define the default bootstrap appearance; DO NOT edit the base files. The site-specific LESS files exist in the `site/` directory; create custom LESS files in the `site/` directory to customize the bootstrap for your website design.

The base and site-specific LESS files are controlled with LESS variables. Find the default
variables in `base/variables.less`; DO NOT edit this file. If you need to change a variable, override the base variable with a site-specific variable in `site/variables.less`.

## Getting Started

1. Copy the contents of this directory into your HiFi template's `styles/` directory.
2. Create site-specific `.less` files inside the `site/` directory.
3. `@import` site-specific `.less` files into `all.less`.
4. Compile and minify `all.less` before site launch.

## Coding Style

* Indent with 4 spaces (do not use tabs)
* Variable, mixin, operator, and function names should:
    * Use lower-case characters
    * Use dashes to separate words