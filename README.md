## BayesNet ~ _WLee_ style 

TikZ library for drawing Bayesian networks, graphical models and (directed) factor graphs in LaTeX.

Forked from [jluttine's original library](https://github.com/jluttine/tikz-bayesnet)

###### This one follows the conventions from the Wagenmakers & Lee book, _Bayesian Cognitive Modeling_

### Differences 
The **main differences** are:

* removal of `latent`, `det` and `obs`  
 and introduction of a Discrete (square) and a Continous (circle) version of each

* the deterministic node is no longer a diamond, but a double bordered square or circle

* minimal modifications with the style  
 everything's a little darker...

Everything else is just as it used to in [jluttine's version](https://github.com/jluttine/tikz-bayesnet)

### Usage

Install the package by copying tikzlibrarybayesnetWLee.code.tex to your LaTeX system or copy the file into projects that are using it. To use the library in your LaTeX file

`\usepackage{tikz}`  
`\usetikzlibrary{bayesnetWLee}`

#### If lost:

`pdflatex example.tex`

And compare example.tex with example.pdf

### TODO

* Finish example.tex


### Why?

Because I needed it for a College work and we used the Wagenmakers & Lee conventions.  
Also, it adds some expressivity to the Bayesian Networks
