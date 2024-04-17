# DESAFÍO 1 - MATEMÁTICA
\documentclass{article}
\usepackage[spanish]{babel}
\usepackage{pifont}
\usepackage{amsmath,amsthm,amsfonts}
\usepackage{latexsym,amssymb}
\usepackage{setspace}
\setstretch{1.5}
\usepackage{titlesec}
\usepackage{multicol}
\usepackage[a4paper, margin=1.3cm]{geometry}
\newtheorem{teor}{\LARGE Teorema}
\renewcommand{\qedsymbol}{$\blacksquare$}
\usepackage{microtype}

\title{DESAFÍO 1 - MATEMÁTICAS}
\author{Ervin Mauricio Lima Suxo}
\date{13 de abril de 2024}

\begin{document}
\maketitle
\large
\clearpage
\section{\LARGE Medida}
\begin{itemize}
    \item[-] \Large Por espacio medible entendemos que un par ordenado (\(\Omega\), \textit{B}) que consta de un conjunto \(\Omega\) y un \(\sigma\) -álgebra \textit{B} de subconjuntos de \(\Omega\). Un subconjunto \textit{A} de $\Omega$ se llama medible si \textit{A} $\in$ \textit{B}. 
    \item[-] \Large Una medida \(\mu\) en un espacio medible (\(\Omega\), \textit{B}) es una función \(\mu\) : \textit{B} \(\rightarrow\) [0,\(\infty\)] que satisface:
    $$\mu(\phi)=0$$
    $$\mu(\bigcup_{i}^{\infty}E_{i})=\sum_{i}^{\infty}\mu(E_{i})$$ para cualquier sucesión $\left\{ E_i \right\}$ de conjuntos medibles disjuntos, es decir $E_i\cap E_j=\varnothing, E_i\in B, i\neq j$.
    \item[-] \Large ($\Omega, B, \mu$) se llama espacio de medida.
    %Aqui presento dos formas de ingresar letras griegas, la primera es mediante \(\símbolo romano\) y la segunda es por los "$".
\end{itemize}
\begin{teor} 
\Large Las siguientes afirmaciones son equivalentes para un grupo G.
\begin{multicols}{2}
    \begin{enumerate}
        \item P(G)=1 \ \item G es abeliano \ \item Z(G)=G
        \item G'=$\left\{1 \right\}$ \ \item $C_G(a)=G$ para todo a $\in$ G \ \item G/G'$\cong$G.
    \end{enumerate}
\end{multicols}
\end{teor}

\begin{proof}[\LARGE \textbf {Demostración.}]
\Large Si P(G)=1, entonces $\left | L(G) \right |=\left | G \right |^2$. Luego $L(G)=G^2$, y esto significa $xy=yz$ para todo $x, y \in$ G. Así G es un grupo abeliano. Es inmediato observar que el razonamiento inverso también es cierto, lo que prueba que 1 es equivalente a 2.
\end{proof}
\Large Según este resultado, para tener grados de conmutatividad diferentes de 1 debemos analizar grupos no abelianos.
\end{document}
