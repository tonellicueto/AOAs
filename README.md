# AOAs
In this repository, we provide almost-orthogonal arrays (AOAs) constructed through algebraic construction (AC), integer programming (IP) and two-staged local search (TS). An extra folder with previously constructed arrays (EXT) is also provided for comparison. See the paper "Almost-orthogonal arrays optimal with respect to a given tolerance and an automorphism group" ([paper link]()) by Luis Martínez, [María Merino](https://sites.google.com/view/maria-merino-maestre/en), Juan Manuel Montoya, [Josué Tonelli-Cueto](https://tonellicueto.xyz/) for more details.

Each array is given as a .dat file and organized in four folders (according to the construction method): AC, EXT, IP and TS. Each file has the format
s$s$_k$k$_l$\lambda$_p$p$_e$\epsilon$_MET.dat
where $s$, $k$, $\lambda$, $p$ and $\epsilon$ are positive integers, and MET is either AC, EXT, IP, TSBC (two-staged local search for bi-cyclic arrays) or TSQC (two-staged local search for quasi-cyclic) depending on the construction method. In such a file, the array has size $\lambda s^2\times k$ and entries ranging from $1$ to $s$. More precisely, each almost-orthogonal array provided has $\lambda s^2$ runs, $k$ factors, $s$ levels, a strength of $2$, index $\lambda$ and tolerance $\epsilon$. In (paper link), definitions and tables specifying further details about these arrays are provided.

All our constructions were done using [the computational cluster ARINA from IZO-SGI, SGIker, at the University of the Basque Country](https://www.ehu.eus/sgi/arina_es/recursos-computacionales-es/cluster-arina).
