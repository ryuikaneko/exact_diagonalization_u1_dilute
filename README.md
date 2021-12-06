# exact diagonalization with U(1) symmetry in dilute systems

- unofficial python/julia test codes for QS-Cube/ED
(see https://github.com/QS-Cube/ED https://arxiv.org/abs/2107.00872 )

- (Python version works at least for numba-0.54.1. If it does not work (possibly "f1 = p_xxz[0,j-1] in st_list" in "ham_to_vec_wave_vector_2"), please comment out "@jit(nopython=True)")

<!--
- spin 1/2, 1d Heisenberg, python [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryuikaneko/exact_diagonalization_u1_dilute/blob/master/spin_half/prog_python_1d_heisenberg_20211206.ipynb)

- spin 1/2, 1d Heisenberg, julia [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryuikaneko/exact_diagonalization_u1_dilute/blob/master/spin_half/prog_julia_1d_heisenberg_20211206.ipynb)
-->
