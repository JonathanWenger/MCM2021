# Probabilistic Numerical Methods - An Algorithmic Perspective

My talk at [MCM2021](https://www.uni-mannheim.de/mcm-2021/) on ProbNum.

## Talk

You can view the compiled [`main.pdf`](https://github.com/JonathanWenger/MCM2021/blob/compiled/talk/talk.pdf) in the `compiled` branch of the GitHub repository.

### LaTeX Compilation

We use `tikz` externalization to keep compilation times low. To compile the pdf run the following in the command line:

```bash
pdflatex talk.tex
make -j 8 -B -f talk.makefile 
pdflatex -g talk.tex
```
