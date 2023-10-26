[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11730532&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Answer

Let's say we have two graphs, $A$ and $B$.  They each have the same number of nodes, and they are both completely connected.
For each node in $A$, you could pick a single unique node in $B$.  This makes a relation that is one-to-one since they both have the same number of nodes.
Since both graphs are completely connected, each node has an edge to every other node in its graph.  Thus, in this relation from $A$ to $B$,
each node in $A$ would have the same edges as its corresponding node in $B$, so this is a bijection.  Since this relation must be one-to-one and bijective,
it fulfills the definition of isomorphism.  Therefore, if two graphs $A$ and $B$ have the same number of nodes and are completely connected, they must be isomorphic.
