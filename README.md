My PhD thesis
==================

1. Compiled on a Mac computer using [LatexTools](https://github.com/SublimeText/LaTeXTools) (Cmd+b shortcut) in [Sublime text editor](http://www.sublimetext.com/).

__List of abbreviations is not included in the final output file!!!__: this is still related to a compilation process. In the past I used this sequence of steps to include/update the list of abbreviations:

* Run LaTeX 2 times then
* ```bash makeindex thesis.nlo  -s nomencl.ist -o thesis.nls ```
* followed by running LaTeX once again.

2. cleanup.sh script is then used to delete all extra files after compilation.

Link to Edinburgh Research Archive: https://www.era.lib.ed.ac.uk/handle/1842/5751

TO DO: find out an exact sequence of compilation commands for both Mac and Linux
