# Math for Machine Learning: Jupyter Notebooks

## What is this?

A set of Jupyter notebooks demonstrating the core math required for machine learning, implemented with numpy. This repo covers linear algebra, probability, and statistics, with clear, practical examples.

## Why?

I'm upskilling from software engineering to machine learning. Instead of just learning theory on a paper notebook, I'm implementing every concept as code, for my own understanding and as a reference for others.

## Contents

- Linear Algebra (vectors, matrices, products, decompositions)
- Probability (distributions, Bayes, etc.)
- Statistics (mean, variance, hypothesis testing, etc.)
- Each concept is explained briefly and then implemented with numpy.

## How to use

These instructions reflect how the author uses these notebooks. There are two main ways I use them:

### Option 1: View on GitHub (Recommended for learning)

- Simply browse the notebooks in the `notebooks/` directory
- GitHub will render the notebooks with all explanations and code
- Great for learning concepts and reviewing code

### Option 2: Run locally with VS Code/Cursor (Author's preferred method for running code)

1. Clone the repo
2. Create and activate a virtual environment:

   ```bash
   # Create virtual environment
   python -m venv venv

   # Activate virtual environment (on mac)
   source venv/bin/activate
   ```

3. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
4. Install VS Code and the "Jupyter" extension
5. Open any notebook in VS Code
6. Select your Python interpreter (the venv you created)
7. Run cells using the play button or Shift+Enter

## Requirements

- Python 3.8 or higher (The author likes managing python with asdf)
- See `requirements.txt` for package dependencies

## Status

This repo is a work in progress. Contributions and corrections are welcome but may not be merged until the author gets to that concept and actually understands them.
