# LaTeX demo step-by-step

## Preamble

Briefly explain command syntax and the document classes, such as `article`, `beamer`, `book` etc. 

Copy:

```latex
\documentclass[letterpaper, 12pt]{article}
```

Load packages including `amsmath` for math and `mhchem` for chem equations.

Copy:

```latex
\usepackage{float}
\usepackage{graphicx}
\usepackage{amsmath}
\usepackage[version=4]{mhchem}
```

Write the header.

Copy:

```latex
\title{My first Overleaf document!}
\author{Your Name}
\date{\today}
```

## Sections and markup

Copy:

```latex
This is my \textbf{first} \LaTeX{} \textit{document}! 
Here is how you \\ line break. 
```

### Package `mhchem`

### Incorporating R

Point to where to switch between Sweave/knitr in Tools (RStudio) or change extension to .Rtex (Overleaf). 