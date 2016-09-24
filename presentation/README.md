# LaTeX Beamer Presentation Slides

Presentation using LaTeX Beamer in 16:10 aspect ratio.

Requirements:

- XeLaTeX
- latexmk
- Fira fonts
- pygmentize (for code highlighting)
- minted (for code highlighting)

To install the dependencies under Ubuntu 16.04:

    sudo apt-get install make latexmk \
        texlive-xetex texlive-fonts-recommended texlive-fonts-extra texlive-latex-extra \
        python-pygments lmodern

Arch Linux:

    sudo pacman -S texlive-most pygmentize minted

## Building

First, install Fira Sans and Fira Mono fonts on your system:

- https://www.fontsquirrel.com/fonts/fira-sans
- https://www.fontsquirrel.com/fonts/fira-mono

Then build the slides:

    git clone --recursive https://github.com/coredump-ch/templates
    cd templates/presentation
    make
