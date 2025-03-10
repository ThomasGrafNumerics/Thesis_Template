<div id="lee-logo" align="center">
    <br />
    <img src="./icons/LeeLogo.svg" alt="Lee Logo" width="400"/>
    <h1>Lee Template</h1>
    <h3>A LaTeX template for students and teachers</h3>
</div>

## Table of Contents

- [Build](#compilation)
- [Why Does This Exist?](#why)

## <a id="compilation"></a>Build
First, make sure that you are using the latest [TeX distribution]([https://scoop.sh](https://www.latex-project.org/get/)) for your system.

To compile your project, run:
```bash
    lualatex -synctex=1 -interaction=nonstopmode main.tex
    biber main
    lualatex -synctex=1 -interaction=nonstopmode main.tex
    lualatex -synctex=1 -interaction=nonstopmode main.tex
```

## <a id="why"></a>Why Does This Exist?
