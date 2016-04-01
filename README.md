# linter-matlab package

This Atom package provides a [Linter](https://atom.io/packages/linter) for MATLAB's `mlint` utility.

## Installation

1. Install the Linter package, following the instructions on [this page](https://atom.io/packages/linter).
2. `apm install linter-matlab`
3. If `mlint` is not already in your PATH, you will need to set the `mlintDir` setting to point to the directory containing `mlint`. As noticed by [@hyiltiz](https://github.com/hyiltiz), this currently does not work with symbolic links.
For example, on Linux, the path for MATLAB R2015b is `/usr/local/MATLAB/R2015b/bin/glnxa64`.
On Windows, the path for MATLAB R2016a is `C:\Program Files\MATLAB\R2016a\bin\win64\`.
