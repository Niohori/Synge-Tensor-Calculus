# Synge-Tensor-Calculus
## Solutions and clarifications for the book Tensor Calculus by J.L. Synge and A. Schild (Dover Publication, 1978)
### Besides pdf text contains full Latex and Tikz codes
### If you have any questions, comments, suggestions, or concerns, you can leave a message in the Issues tag.
### The *.tex Tikz files have to be located in an ./images/*.tex directory, relative to the working directory where Part1.tex and so are put.
### The "externalized"  Tikz files have to be located in an ./Externalized_figures/ directory, relative to the working directory where Part1.tex and so are put. 
### Possible problem when compiling the Latex code. 
#### Due to use of a lot of TIKZ plots, your Latex compilation  will probably fail, issuing an error message. 
#### One way to turn around this problem, is to add the "-shell-escape" switch in de pdf-command line, something like
#### pdflatex -shell-escape "filename".
#### This  can be done in LaTeX editors: there is usually a place in the settings for this type of thing.
#### I use Texmaker and this how the settings look like:
<img src="https://github.com/Niohori/Synge-Tensor-Calculus/blob/main/images/texmaker.PNG" width="800" />

#### This way, every image will be treated as a separate pdf-file and will make the compilation faster (except the first time).

##The solutions are given in the Ricci index notation as in the book. An interesting exercise could be to convert the exercises in the coordinate-free notation.


