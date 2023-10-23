[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12516996&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Suppose $A = (V_1, E_1)$ and $B = (V_2, E_2)$ are two graphs that do not have the same number of nodes but are isomorphic, and let $f: V_1 \rightarrow V_2$ be a bijection between the two.

By the definition of one-to-one and onto, every vertex in $V_1$ should correspond to exactly one vertex in $V_2$, meaning that the number of vertices in $V_1$ should be equal to the number of vertices in $V_2$. However, if the two graphs do not have the same number of nodes, then at least one vertex does not correspond to another.

Therefore, if two graphs do not have the same number of nodes, they cannot be isomorphic.
