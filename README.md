texmf
=====

Miscellaneous latex packages and clases

exercises.sty
---------

Create assignments or books of exercises where you can list each exercise with answers and print the answers at the end or inline.

```tex
\begin{Exercises}
    \item{First}
    \Answer{first answer}
    \item{With nested exercises}
    \begin{SubExercises}
        \item{First}
        \item{Second}
        \SubAnswer{Second's answer}
    \end{SubExercises}
\end{Exercises}
```

tkz-automata.sty
--------

Create automata diagrams

```tex
\automata{
    \Vertices[x=0,y=1]{q_1,q_2}
    \initial{q_1}
    \accepting{q_2}
    \arc[left]{q_1}{q_2}{b}
    \arc[left]{q_2}{q_1}{a}
    \loopArc{q_2}{b}
}
```
