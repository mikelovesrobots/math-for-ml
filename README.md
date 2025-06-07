# Math for Machine Learning: Jupyter Notebooks

## What is this?

A set of Jupyter notebooks demonstrating the core math required for machine learning, implemented with numpy. This repo covers linear algebra, probability, and statistics, with clear, practical examples.

## Note on Status

This repo is a work in progress, filling out as I encounter concepts in my classes:

- Linear Algebra: In Progress
- Probability: Not Started
- Statistics: Not Started

## Why?

I'm upskilling from software engineering to machine learning. Instead of just learning theory on paper, I'm implementing every concept as code, for my own understanding and as a reference for others.

## Contents

- Linear Algebra (vectors, matrices, products, decompositions)
- Probability (distributions, Bayes, etc.)
- Statistics (mean, variance, hypothesis testing, etc.)
- Each concept is explained briefly and then implemented with numpy.

## How to Use

These instructions reflect how I use these notebooks. There are two main ways I work with them:

### Option 1: View on GitHub (Recommended for learning)

- Simply browse the notebooks in the `notebooks/` directory
- GitHub will render the notebooks with all explanations and code
- Great for learning concepts and reviewing code

### Option 2: Run locally with VS Code/Cursor (My preferred method for running code)

1. Clone the repo
2. Create and activate a virtual environment:

   ```bash
   # Create virtual environment
   python -m venv venv

   # Activate virtual environment (on macOS)
   source venv/bin/activate
   ```

3. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
4. Install VS Code (or Cursor) and the "Jupyter" extension
5. Open any notebook in your editor
6. Select your Python interpreter (the venv you created)
7. Run cells using the play button or Shift+Enter

## Requirements

- Python 3.8 or higher (I use asdf for Python version management)
- See `requirements.txt` for package dependencies

## Contributions

Contributions are welcome, but I probably won't merge them until I actually understand the mathematical concepts myself.
