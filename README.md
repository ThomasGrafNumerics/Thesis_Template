<div id="lee-logo" align="center">
    <br />
    <img src="./icons/LeeLogo.svg" alt="Lee Logo" width="400"/>
    <h1>Lee Template</h1>
    <h3>A LaTeX template for students and teachers</h3>
</div>

## Table of Contents

- [Build](#compilation)
- [Maintainers](#maintainers)
- [Why Does This Exist?](#why)
- [License](#license)

## <a id="compilation"></a>Build
First, make sure that you are using the latest [TeX distribution](https://www.latex-project.org/get/) for your system.

To compile your project, run:
```bash
    lualatex -synctex=1 -interaction=nonstopmode main.tex
    biber main
    lualatex -synctex=1 -interaction=nonstopmode main.tex
    lualatex -synctex=1 -interaction=nonstopmode main.tex
```
We recommend using a bash-script that will invoce these commands for you. An example of such a bash-script can be found [here](https://gist.github.com/Dih5/6a25a3a2be7a99eee79cb89b8de2ce72).


## <a id="maintainers"></a>Maintainers
List of maintainers:
- [Cyril Wendl](https://github.com/CyrilWendl/LeeTeX)
- [Thomas Graf](https://github.com/ThomasGrafNumerics)


## <a id="why"></a>Why Does This Exist?
This LaTeX template is designed to give you a jump start in typesetting professional and visually appealing documents with ease. It covers a wide range of common use cases, making it ideal for students, educators, and professionals alike.  

Whether you're working on your high school thesis project, crafting well-structured lecture notes, designing exams, or preparing technical presentations, this template provides a solid foundation. Additionally, it serves as a valuable tool for teachers looking to create high-quality class materials for their students.  

Developed using best practices, this template is well-maintained to ensure compatibility, efficiency, and ease of use. Its structured design and ready-to-use formatting help streamline your workflow, allowing you to focus on content while ensuring a polished and consistent presentation.


## <a id="license"></a>License

[MIT](https://github.com/ThomasGrafNumerics/Thesis_Template/blob/main/LICENSE)
