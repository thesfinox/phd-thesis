# Ph.D. Thesis

This project contains the LaTeX code of my Ph.D. defence thesis.

I chose to use `XeLaTeX` to compile it (`BibTeX` for the bibliography) in order to have more freedom to customise the class and the packages. I have included a local `.latexmkrc` file so if you use [_latexmk_](https://mg.readthedocs.io/latexmk.html) you should be good to go. In other cases you should probably use somthing like `xelatex -file-line-error -synctex=1 -interaction=nonstopmode` and the name of the file to compile it. Remember to install both `xelatex` and `biber`!

The repository contains submodules which point to other repositories where I keep my custom packages and classes. Clone the repository using `git clone --recurse-submodules` to include them in your local machine.
