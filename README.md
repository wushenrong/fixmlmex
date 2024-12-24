# fixmlmex

The `fixmlmex` package extends the `fixcmex` to provide fully scalable
Computer Modern Math Extensions font for Modified Latin Modern font
(`mlmodern`).

## Modified Changes

- Rename all instances of `fixcmex` to `fixmlmex` including the filenames to
  comply with 6.a of the LaTeX Project Public License.
- Add fixes for `mlmodern` by adding `mlmex` to the list of fonts to patch.

## Installation

- Run `latex fixmlmex.ins`.
- Move `fixmlmex.sty` to your `texmf` folder where LaTeX will be able to
  find the package.
- Change `\usepackage{fixcmex}` to `\usepackage{fixmlmex}` as a drop in
  replacement.

## License

```text
Copyright 2019 Enrico Gregorio
Copyright 2024 Samuel Wu

This modified program is provided under the terms of the LaTeX Project Public
License. See LICENSE for the entire text or at
https://www.latex-project.org/lppl.txt.

The original author is Enrico Gregorio. Modified by Samuel Wu.

This work consists of the following files:

README (this file)
fixmlmex.dtx
fixmlmex.ins
fixmlmex.pdf

and of the derived file

fixmlmex.sty

An unmodified copy of the original work can be found in the fixcmex folder
containing the following files:

README
fixcmex.dtx
fixcmex.ins
fixcmex.pdf

and of the derived file

fixcmex.sty

Or can be found at the CTAN archive: https://ctan.org/pkg/fixcmex

This work has the LPPL maintenance status "author-maintained".
```
