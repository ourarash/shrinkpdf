# Shrinkpdf

Reduce size of PDF (compress) using Ghostscript at terminal.

# Requirement

Make sure `gs` is installed on your machine and it's in your path.

## Installation on Mac:

```bash
brew install ghostscript
```

Check [here](http://macappstore.org/ghostscript/) for more info on mac installation.

## Windows and Linux

See [how to install gs](https://www.ghostscript.com/doc/current/Install.htm)

# Usage

Once `gs` is installed in your system and it's in your path:

```bash
shrinkpdf.sh infile [outfile] [resolution_in_dpi]
```

## Examples:

```bash
shrinkpdf.sh input.pdf output.pdf
```

```bash
shrinkpdf.sh input.pdf output.pdf 100
```

```bash
shrinkpdf.sh input.pdf output.pdf 120
```
