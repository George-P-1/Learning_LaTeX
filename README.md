# Learning LaTeX

I will be using this repository to record my progress of learning LaTeX. 
This includes:
- Installing LaTeX
    - LaTeX Workshop in VSCode
    - MikTex or TexLive
    - TexStudio or TexMaker (for extra features that may be useful)
- Links to useful information, learning material and guides I found online. 

--- 
<!-- Intentional separator. In GitHub website, there are extra separators after every heading I think. -->

## Links for Research before Installation
The things I looked at to decide what to install, why and how.

- https://www.reddit.com/r/LaTeX/comments/15sup7o/texstudio_vs_latex_workshop_on_vscode/?rdt=58891
    <details>
    <summary>Highlights</summary>

    - "I switched to 95% VS Code/5% TexStudio once I got the settings right. The only thing VS Code lacks is the ability to change labels across a project, which TS handles well."
    - "Mostly the lack of extensions that VSCode has to make my coding experience for the most part easier. And lack of some text manipulation features, for example column selection, multiple cursors which I am used to using when coding day to day. I do still use TexStudio a little bit for some niche operations like outline manipulation, label manipulation and table generation."

    </details>

- https://github.com/James-Yu/LaTeX-Workshop
    - https://github.com/James-Yu/LaTeX-Workshop/wiki/Install
        - Requirements for Installation are mentioned here.

- https://www.reddit.com/r/LaTeX/comments/1c7s9r2/best_latex_editor/?rdt=50941
    <details>
    <summary>Highlights</summary>

    - "Latex Workshop, LTex and TexLab extensions"
    - "VS Code + LaTeX Workshop and LaTeX Language Tool is a game changer"

    </details>

- https://www.reddit.com/r/LaTeX/comments/xu3yoi/texstudio_vs_texmaker/?rdt=61091

- https://tex.stackexchange.com/questions/208219/what-are-the-main-differences-between-texmaker-and-texstudio
    <details>
    <summary>Highlights</summary>

    - "in TeXstudio, you can draw math symbols with your mouse and have them translated into LaTeX code."

    </details>


### Conclusion from Research: 
- VSCode > TeXStudio > TexMaker
- Overleaf good for collaboration with others but same effect achieved with above options and proper git use.
- All local versions need Perl to be installed for full functionality.
- Optional but probably useful extensions available in VSCode.

## Installation

Followed instructions from - https://www.youtube.com/watch?v=qy93QXnvo0M

- First install MikTex.
    - https://miktex.org/download - Download the basic installer.

- Then install Strawberry Perl.
    - https://strawberryperl.com - Download the MSI installer.

- Then install LaTeX Workshop (by James Yu) extension in VScode.

- Maybe also install TexStudio.
    - https://www.texstudio.org

## Using LaTeX Workshop in VSCode

- An introduction - https://www.youtube.com/watch?v=vIImoKpKWIo

## Introduction to coding in LaTeX
Learning material, tips and tricks, etc.

- Quick Introduction - https://www.youtube.com/watch?v=lgiCpA4zzGU

- freecodecamp - https://www.youtube.com/watch?v=ydOTMQC7np0
    - The tutorial files from the video are in the `michelle_krummel_files` directory.
        - Tutorial 1: Introduction
        - Tutorial 2: Common Mathematical Notation
        - Tutorial 3: Brackets, Tables and Arrays
        - Tutorial 4: Creating Lists
        - Tutorial 5: Text Document Formatting
        - Tutorial 6: Packages, Macros and Graphics
        - Tutorial 7: Errors and Debugging
        - Tutorial 8: TeXmaker and Overleaf Tips

- Turn a python math function to LaTeX code - https://www.youtube.com/shorts/CrsFXEqQuPY

- Some info about using LaTeX Workshop - https://www.youtube.com/watch?v=triTgcyF_IA

## About files generated during compilation

- https://tex.stackexchange.com/questions/7770/file-extensions-related-to-latex-etc

- .aux files - https://www.reddit.com/r/LaTeX/comments/12y6uip/aux_files/

- https://www.dickimaw-books.com/latex/novices/html/auxiliary.html
