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
This LaTeX template is designed to give you a jump start in typesetting professional and visually appealing documents with ease. It covers a wide range of common use cases, making it ideal for students, educators, and professionals alike.  

Whether you're working on your high school thesis project, crafting well-structured lecture notes, designing exams, or preparing technical presentations, this template provides a solid foundation. Additionally, it serves as a valuable tool for teachers looking to create high-quality class materials for their students.  

Developed using best practices, this template is well-maintained to ensure compatibility, efficiency, and ease of use. Its structured design and ready-to-use formatting help streamline your workflow, allowing you to focus on content while ensuring a polished and consistent presentation.
