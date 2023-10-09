# Game Theory
<p align="center">
<img src="https://github.com/DidierMerk/GameTheory/blob/main/gametheoryresults.png" width="700" height="275" alt="Plots of the results of simplified poker from homework 4">
</p>

## The course
In this repository you can find the homework and the written code for the course Game Theory, taught at the University of Amsterdam for the master AI programme. The course goes over concepts such as Nash Equilibria, normal-form games, bayesian games, extensive-form games, auctions and transferable utility games. During this course we study the mathematical theory and write the code to run theoretical concepts in practice. In the image above, for example, we demonstrate our results of playing 102 million games of _simplified poker_ (which can be seen in the report of week 4). 

## LateX typesetting instruction 
For this course, a lot of normal-form game typesetting is needed in LateX. To make this easier I made a short LateX file that includes the typesetting for normal-form games up to a size of 4x4. To use this, include the ``normal_games.tex`` file in your own ``main.tex`` file as follows:

```
%%%% NORMAL-GAMES TYPESETTING %%%%
\include{normal_games}
```

The codes for each size matrix can be copied from the ``normal_games.tex`` file, but it basically comes down to using \nfgame_x_{...}, where the two underscores need to be replaced by the size of the game you want to use; and the dots with the game’s information. For a 2x2 normal-form game, this would look as follows:

```
\begin{center}

%%% 2x2 %%%
\nfgametwoxtwo{T B L R $1$ $2$ $3$ $4$ $5$ $6$ $7$ $8$}
\qquad

\end{center}
```

With the result looking like this:

<p align="left">
<img src="https://github.com/DidierMerk/GameTheory/blob/main/twobytwo.png" width="200" height="200" alt="Example of a two by two normal-form game in LateX">
</p>

Oh, one last thing. For this to compile correctly in Overleaf, you need to set your compiler to the 2021 version. To do this, when editing your document, click on ’Menu’ at the top left and then set your TeX Live version to 2021!



