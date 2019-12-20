# Example

\documentclass[tikz]{standalone}

\usepackage{tikz}

\begin{document}

\usetikzlibrary{matrix,arrows}

\begin{Huge}
\begin{tikzpicture}[description/.style={fill=white,inner sep=2pt}]

\matrix (m) [matrix of math nodes, row sep=3.5em,
column sep=2.9em, text height=1.6ex, text depth=0.25ex]
{ A & E& B \\
D& C &K \\ };

\path[->]
(m-1-1) edge node[auto] {$ \varphi $} (m-1-2)
        edge node[description] {$ f $} (m-2-1)
        edge node[description] {$d $} (m-2-2)
(m-1-2) edge node[auto] {$ \phi $} (m-1-3)
        edge node[description] {$ h $} (m-2-2)
(m-2-2) edge node[auto] {$ \Phi $} (m-2-3)
(m-1-3) edge node[auto] {$ g $} (m-2-3)
(m-2-1) edge node[auto]{$\Psi$} (m-2-2);

\end{tikzpicture}
\end{Huge}

\end{document}
