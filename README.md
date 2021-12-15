# exact diagonalization with U(1) symmetry in dilute systems

## Codes

- unofficial python/julia test codes for QS-Cube/ED
(see https://github.com/QS-Cube/ED https://arxiv.org/abs/2107.00872 )

- (Python version works at least for numba-0.54.1. If it does not work (possibly "f1 = p_xxz[0,j-1] in st_list" in "ham_to_vec_wave_vector_2"), please comment out "@jit(nopython=True)")

- spin 1/2, 1d Heisenberg, python [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryuikaneko/exact_diagonalization_u1_dilute/blob/master/spin_half/colab_python_1d_heisenberg_20211206.ipynb)

<!--
- spin 1/2, 1d Heisenberg, python [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryuikaneko/exact_diagonalization_u1_dilute/blob/master/spin_half/prog_python_1d_heisenberg_20211206.ipynb)

- spin 1/2, 1d Heisenberg, julia [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryuikaneko/exact_diagonalization_u1_dilute/blob/master/spin_half/prog_julia_1d_heisenberg_20211206.ipynb)
-->

- (\# local Hilbert space) = (\# particles) (no truncation), 1d Bose-Hubbard (U/J=10), Ponomarev basis, python [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryuikaneko/exact_diagonalization_u1_dilute/blob/master/bose_hubbard_basis_ponomarev_no_truncation/colab_python_1d_bose_basis_ponomarev_20211215.ipynb)

## References

- spin 1/2

  - https://arxiv.org/abs/2107.00872

- general spin

  - https://arxiv.org/abs/0706.3293

- Bose-Hubbard

  - tag method

    - https://doi.org/10.1088/0143-0807/31/3/016 ( https://arxiv.org/abs/1102.4006 )
    - https://github.com/MelkoCollective/BH_diagonalize
    - https://github.com/rgmelko/BH_diagonalize/blob/master/BH_basis.jl

  - Jeszenszki basis

    - https://doi.org/10.1016/j.chemphys.2011.10.003 ( http://coulson.chem.elte.hu/surjan/PREPRINTS/181.pdf )
    - https://github.com/0/JeszenszkiBasis.jl
    - https://github.com/0/JeszenszkiBasis.jl/blob/master/src/basis.jl

  - Ponomarev basis

    - https://doi.org/10.1088/1361-6455/aa68b1 ( https://arxiv.org/abs/1410.7280 )
    - https://www.tdx.cat/handle/10803/666723
