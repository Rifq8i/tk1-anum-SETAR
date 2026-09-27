# Numerical Analysis Project - SETAR

This project implements a *Least Squares Problem* to estimate the parameters of a two-regime SETAR model using:

- Normal Equations with Gaussian elimination and partial pivoting
- QR decomposition with Givens rotations

## Requirements

- Python 3
- Jupyter Notebook
- NumPy
- pandas
- Matplotlib

Install the required packages:

```bash
pip install jupyter numpy pandas matplotlib
```

## Usage

Run the following command from the repository directory:

```bash
jupyter notebook
```

Open a notebook and select **Restart & Run All**:

- `normal_equations.ipynb`: solution using the Normal Equations
- `givens_qr.ipynb`: solution using Givens QR and model evaluation
