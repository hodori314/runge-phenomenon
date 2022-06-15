# Runge phenomenon
This is an article that introduces and proposes several mitigating methods for Runge phenomenon. While making guesses of functions with discrete data points, one can use polynomial interpolation. However, there were some problems using this method. Proposed higher degree polynomial are oscillating at the end of the given interval. This problem grows errors of the proposed polynomial. In this article, we are going to introduce several solutions for erasing errors for given high order polynomials. 

## Experiments
I experimented three solutions for runge phenomenon.
1. Chebyshev node
2. Cubic spline
3. Bernstein polynomial

You can check the outputs and **try your own `n` high degree polynomial** at `experiment.ipynb`.

## Etc
- This is final project for POSTECH MATH351 lecture.</br>
- Other graphs on this <a href="https://github.com/hodori314/runge-phenomenon/blob/main/Solutions%20for%20Runge%20Phenomenon.pdf">paper</a> was made at `several_graphs.ipynb`.</br>
- I used online latex editor, `overleaf` with `SIAM` template.

## File tree
- <a href="https://github.com/hodori314/runge-phenomenon/blob/main/Solutions%20for%20Runge%20Phenomenon.pdf">paper</a>
- <a href="https://github.com/hodori314/runge-phenomenon/blob/main/experiment.ipynb">experiment</a>
- <a href="https://github.com/hodori314/runge-phenomenon/blob/main/several_graphs.ipynb">graph images</a>
