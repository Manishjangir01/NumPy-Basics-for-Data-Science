# NumPy Basics for Data Science

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Manishjangir01/NumPy-Basics-for-Data-Science/blob/main/numpy_basics.ipynb)

NumPy fundamentals for data science beginners: arrays, operations, indexing,
broadcasting, statistics, random numbers and linear algebra.

## Topics covered

- Creating NumPy arrays (1D and 2D)
- Built-in functions (`zeros`, `ones`, `arange`, `linspace`)
- Mathematical functions (`sin`, `cos`, `sqrt`, `exp`)
- Indexing and slicing
- Broadcasting
- Vectorized operations
- Conditional (boolean) indexing
- Reshaping, flattening and transposing
- Aggregations and statistics (`sum`, `mean`, `std`, `var`, axis-wise)
- Random numbers and distributions
- Linear algebra (dot product, determinant, inverse, eigenvalues)

## Files

| File                  | Description                                          |
|-----------------------|------------------------------------------------------|
| `numpy_basics.ipynb`  | Runnable Jupyter notebook with all the examples      |
| `Numpy.pdf`           | Original printed notebook, including saved outputs   |
| `requirements.txt`    | Python packages needed to run the notebook           |

## How to run

```bash
pip install -r requirements.txt
jupyter notebook numpy_basics.ipynb
```

Run the cells from top to bottom. The random-number cell uses a fixed seed
(`np.random.seed(42)`), so it gives the same output every time.

## Who is this for

- BCA / BSc / MCA students
- Data science beginners
- College assignments
- Interview and revision notes

## License

MIT, see [LICENSE](LICENSE).
