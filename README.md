# FAIR theory: Dunning-Kruger Effect

# Description

This is a FAIR theory (see Van Lissa et al., in preparation) implementation of the Dunning-Kruger (DK) effect.
The DK effect is a psychological theory relating levels of performance and self-rated performance. We closely follow the formalization of Feld, Sauermann, and De Grip (2017), who paraphrase the DK effect as "low performers vastly overestimate their performance while high performers more accurately assess their performance".

# Interoperability

The implementation is split into the following parts:

1. Definitions of all concepts: verbal description in the markdown text file `definitions.md`.
2. Relationships between the concepts: standardized graph specification following [GraphML](http://graphml.graphdrawing.org/) in the text file `relationship_graph.txt`. This specification is machine-readable and can be rendered using for example the [igraph](https://r.igraph.org/) software package, as we do in the accompanying [vignette](https://cjvanlissa.github.io/theorytools/articles/dunning-kruger.html).
3. Mathematical definitions and theorems/proofs as LaTeX code in the file `equations.tex`. LaTeX code can be rendered to pdf documents using for example [LuaTeX](https://www.luatex.org/), and multiple `.tex` files can be combined into larger files, as we do in the [vignette](https://cjvanlissa.github.io/theorytools/articles/dunning-kruger.html).
4. Statistical models again as LaTeX code in `linear_model.tex`.
5. All LaTeX code (equations and models) is combined in `render.tex`.

# Contributing

If you want to contribute to this project, please get involved. You can do so in three ways:

1. **To discuss the current implementation and discuss potential changes**, file a 'GitHub' issue [here](https://github.com/cjvanlissa/theorytools/issues)
2. **To directly propose changes**, send a pull request containing the proposed changes [here](https://github.com/cjvanlissa/theorytools/pulls)
3. **To create a derivative theory**, please fork the repository [here](https://github.com/cjvanlissa/theorytools/fork)

If you fork the repository, please cite this repository (see below), and add it as a related work (below and by adding the appropriate metadata on 'Zenodo').

By participating in this project, you agree to abide by the [Contributor Covenant](https://www.contributor-covenant.org/version/2/0/code_of_conduct.html).

## Related works

See this project's Zenodo page for cross-references to related work. 

This repository contains an implementation of the Dunning-Kruger effect proposed by Kruger and Dunning (1999).
We closely follow the formalization of Feld, Sauermann, and De Grip (2017).

> Feld, J., Sauermann, J., & De Grip, Andreas. 2017. “Estimating the Relationship Between Skill and Overconfidence.” Journal of Behavioral and Experimental Economics 68: 18–24.

> Kruger, J., & Dunning, D. (1999). Unskilled and unaware of it: how difficulties in recognizing one's own incompetence lead to inflated self-assessments. Journal of personality and social psychology, 77(6), 1121.

## Citing this work

See this project's 'Zenodo' page for the preferred citation.
