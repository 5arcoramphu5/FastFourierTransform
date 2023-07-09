# Bachelor's Thesis - Fast Fourier Transform

This repository contains my Bachelor's thesis from Jagiellonian University in Cracow titled "Fast Fourier Transform in one and two dimensions". Content of the thesis is available in `thesis.pdf`. File `fast_fourier_transform.ipynb` contains implementation of algorithms described in the thesis and visualisations of their results. 

## Contents of file `thesis.pdf`

- Introduction to Discrete Fourier Transform (DFT) with required definitions and proofs
- Introduction to multidimensional DFT
- Description of Fast Fourier Transform (FFT) algorithms with proofs of complexity and correctness:
    - One dimensional FFT:
        - Cooley-Tukey Radix-2 DIT FFT
        - Cooley-Tukey Radix-$n$ DIT for any $n$
    - Two dimensional FFT :
        - "Row-Column" algorithm
        - "Vector-Radix" algorithm
- Examples of applications of FFT:
    - 1D - polynomial multiplication
    - 2D - simple image compression

## Contents of `fast_fourier_transform.ipynb`

- Implementation of algorithms listed above
- Plots of results
- Comparison of execution times
- Example of image compression 
