# ML Assignment 1 — NumPy

Notebook: `assignment1_numpy.ipynb` (run top to bottom with Runtime -> Restart and run all).

## Q8 speed-up
`np.bincount` vs a plain Python loop over 1,000,000 integers (0-99):

- Python loop: 0.1225 s
- np.bincount: 0.001505 s
- **Speed-up: 81x**

Note: the Python loop in Q8 runs over a list (`.tolist()`), as the question requires; no loop runs over a NumPy array anywhere.
