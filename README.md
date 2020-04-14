Introduction
============

Latex template for HVL PhD dissertations.

The template uses the latexmk to compile the latex to pdf by running a makefile enclosed.

All the default settings of the template are in the preamble.tex and macros.tex.

The font size of the PhD thesis template is 12pt.

The fonts used in the template include:
1. [Palatino](https://en.wikipedia.org/wiki/Palatino#Palatino) font: [tgpagella](https://tug.org/FontCatalogue/texgyrepagella/)
   pacakge

2. Typewriter font: [beramono](https://tug.org/FontCatalogue/beramono/) package

3. The Euler-VM fonts for maths (blend well with Palatino): [eulervm](http://ftp.riken.jp/tex-archive/fonts/eulervm/doc/latex/eulervm/eulervm.pdf) package 

Install/Upate Latest Latex
========
* Install TeX document production system (Latex)
To get the TeX document production system, one easy way is to download [TeX Live](https://www.tug.org/texlive/).

* Update Latex
If you already have Latex (Tex Live) in your machine,
then it to the latest version first.

Compiling
=========

* To generate the main pdf file, you can simply run the command:

`> make`

This should generate the thesis.pdf if everything is set up correctly, 

* To run latexmk in "continuous mode" such that the thesis.pdf file
is recreated every time the sources change after saving. 
The continuous mode can be executed by running the command:

`> make cont`

Both should generate thesis.pdf and open the file using the pdf-viewer.
The default setting in the Makefile is to use Preview to open thesis.pdf in
MacOS.
If, e.g., in Linux, you need to change the Makefile for the pdf-viewer you want
to use, such as [okular](https://okular.kde.org/): `okular thesis.pdf`.

* To clean up the generated files, you can run the command

`> make clean`


Possible ways to use Latex: 
=========

1. vim/nvim

      a. [Install NeoVim and Plugins with vim-plug](https://www.linode.com/docs/tools-reference/tools/how-to-install-neovim-and-plugins-with-vim-plug/)
  
      b. [Setup Neovim for Latex](https://yufanlu.net/2018/09/03/neovim-latex/)
  
      c. [Awesome vim plugins for writers](https://opensource.com/article/17/2/vim-plugins-writers)
  
      d. [10 Vim Plugins for Writing](https://dev.to/tomfern/10-vim-plugins-for-writing-2k66)

      e. To speed up the wirting if there are lots of mathematics: [take notes in mathematics lectures using LaTeX and Vim](https://castel.dev/post/lecture-notes-1/)

2. [Using Atom as a LaTeX editor](https://medium.com/@lucasrebscher/using-atom-as-a-latex-editor-93756de3d726)

3. [Overleaf](https://www.overleaf.com/)

4. [TeXstudio](https://www.texstudio.org/)
