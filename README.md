[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QM7QGF1q)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## My Proof

let A = (V,E)(V = {a, b, c}  with  E = {{a,b},{a,c},{b,c}})

let B = (V,E)(V = {d, e, f}  with  E = {{d,e},{d,f},{e,f}})

to check for isomorphism, we can map A to B and check the vertex relations against each other 

let A $\to$ B

$\implies$ {a, b, c} $\to$ {d, e, f}

because there are the same number of nodes this works and now we can compare the relations

$\implies$ {a, b} = {d, e}, {a, c} = {d, f}, {b, c} = {e,f}

$\therefore$ since A and B are both complete graphs and we show that all of the relations match, we can assume that all complete graphs with n nodes will be isomorphic with one another









## Sources

https://math.libretexts.org/Bookshelves/Combinatorics_and_Discrete_Mathematics/Applied_Combinatorics_(Keller_and_Trotter)/05:_Graph_Theory/5.01:_Basic_Notation_and_Terminology_for_Graphs used this for graph notation
