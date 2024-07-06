# AOAs
In this repository, we provide almost-orthogonal arrays (AOAs) constructed through algebraic construction (AC), integer programming (IP) and two-staged local search (TS). An extra folder with previously constructed arrays (EXT) is also provided for comparison. See the paper "Almost Orthogonal Arrays: Theory and Search Three Ways" ([arXiv:2406.19516](https://arxiv.org/abs/2406.19516)) by Luis Martínez, [María Merino](https://sites.google.com/view/maria-merino-maestre/en), Juan Manuel Montoya, [Josué Tonelli-Cueto](https://tonellicueto.xyz/) for more details.

Each array is given as a .dat file and organized into four folders (according to the construction method): AC (Algebraic Construction), EXT (from the Literature), IP (Integer Programming), and TS (Two-Staged Local Search). Each file has the format

$\text{s}s\textunderscore\text{k}k\textunderscore\text{l}\lambda\textunderscore\text{p}p\textunderscore\text{e}\epsilon\textunderscore\text{MET.dat}$

where $s$, $k$, $\lambda$, $p$ and $\epsilon$ are positive integers, and MET is either AC, EXT, IP, TSBC (two-staged local search for bi-cyclic arrays) or TSQC (two-staged local search for quasi-cyclic) depending on the construction method. In such a file, the array has size $\lambda s^2\times k$ and entries ranging from $1$ to $s$. More precisely, each almost-orthogonal array provided has $\lambda s^2$ runs, $k$ factors, $s$ levels, a strength of $2$, index $\lambda$, tolerance $\epsilon$ and $p\in\{1,2\}$ the value for which the $p$-unbalance was minimized. In [the aforementioned paper](paper link), definitions and tables specifying further details about these arrays are provided.

All our constructions were done using [the computational cluster ARINA from IZO-SGI, SGIker, at the University of the Basque Country](https://www.ehu.eus/sgi/arina_es/recursos-computacionales-es/cluster-arina).
