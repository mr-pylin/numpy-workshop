# 🔢 NumPy Workshop

[![License](https://img.shields.io/github/license/mr-pylin/numpy-workshop?color=blue)](https://github.com/mr-pylin/numpy-workshop/blob/main/LICENSE)
[![Python Version](https://img.shields.io/badge/Python-3.12.8-yellow?logo=python&logoColor=white)](https://www.python.org/downloads/release/python-3128/)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/1faf9d4577d3406a9ac65a4cb8d3d4f1)](https://app.codacy.com/gh/mr-pylin/numpy-workshop/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![Code Style](https://img.shields.io/badge/code%20style-black-black.svg)](https://github.com/psf/black)
![Repo Size](https://img.shields.io/github/repo-size/mr-pylin/numpy-workshop?color=lightblue)
![Last Updated](https://img.shields.io/github/last-commit/mr-pylin/numpy-workshop?color=orange)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?color=brightgreen)](https://github.com/mr-pylin/numpy-workshop/pulls)

An in-depth guide to mastering **NumPy**, covering fundamental to advanced array operations for **data science** and **numerical computing**.

## 📖 Table of Contents

### 📖 Main Notebooks

1. [**Array Basics**](./code/01-array-basics.ipynb)  
   Introduction to NumPy arrays
1. [**Arithmetic Operations**](./code/02-arithmetic-operations.ipynb)  
   Arithmetic operations between (array & scalar) or (array & array)
1. [**Comparative Operations**](./code/03-comparative-operations.ipynb)  
   Comparative operations between (array & scalar) or (array & array)
1. [**Index & Slice**](./code/04-index-&-slice.ipynb)  
   Basic and advanced indexing and slicing arrays including Mask & Filters
1. [**Axes**](./code/05-axes.ipynb)  
   Understanding use of axes in multi-dimensional arrays combined with methods [the hardest part in NumPy for newbies in my opinion]
1. [**Array Manipulations**](./code/06-array-manipulations.ipynb)  
   Techniques for updating values, appending, inserting, reshaping, concatenating, ...
1. [**NdArray properties & methods**](./code/07-ndarray-members.ipynb)  
   Comprehensive overview of properties and methods associated with NumPy arrays.
1. [**Array Creation**](./code/08-array-creation.ipynb)  
   Various methods to create NumPy arrays (e.g., `numpy.array`, `numpy.zeros`, etc.).
1. [**Mathematics**](./code/09-mathematics.ipynb)  
   Mathematical functions and operations available in NumPy
1. [**Statistics**](./code/10-statistics.ipynb)  
   Statistical functions for data analysis (mean, median, variance, etc.).
1. [**Sort, Search & Count**](./code/11-sort-search-count.ipynb)  
   Methods for sorting, searching, and counting elements in arrays.
1. [**Logic**](./code/12-logic.ipynb)  
   Logical operations and boolean indexing with NumPy arrays.
1. [**Set**](./code/13-set.ipynb)  
   Set operations for array elements (union, intersection, difference).
1. [**Linear Algebra**](./code/14-linear-algebra.ipynb)  
   Fundamental linear algebra operations using NumPy (matrix multiplication, determinants).
1. [**Structured Array**](./code/15-structured-array.ipynb)  
   Creating and manipulating structured arrays with custom data types.
1. [**Input/Output**](./code/16-input-output.ipynb)  
   Techniques for reading from and writing to files using NumPy.
1. [**Random Generator**](./code/17-random-generator.ipynb)  
   Generating random numbers and distributions with NumPy's random module.
1. [**Fourier Transform**](./code/18-fourier-transform.ipynb)  
   Understanding and applying Fourier transforms in NumPy.
1. [**Efficient Computing**](./code/19-efficient-computing.ipynb)  
   Strategies for optimizing performance and memory usage in NumPy operations.
1. [**Miscellaneous**](./code/20-miscellaneous.ipynb)  
   Additional topics and advanced features in NumPy.
1. [**Looking Ahead**](./code/21-looking-ahead.ipynb)  
   Introduction to *Pandas* for data manipulation and *Matplotlib* for data visualization.

## 📋 Prerequisites

- 👨‍💻 **Programming Fundamentals**
  - Proficiency in **Python** (data types, control structures, functions, classes, etc.).
    - My Python Workshop: [github.com/mr-pylin/python-workshop](https://github.com/mr-pylin/python-workshop)
- 🔣 **Mathematics for Machine Learning**
  - 🔲 **Linear Algebra**: Vectors, matrices, matrix operations.
    - [**Linear Algebra Review and Reference**](https://www.cs.cmu.edu/%7Ezkolter/course/linalg/linalg_notes.pdf) written by [*Zico Kolter*](https://zicokolter.com).
    - [**Notes on Linear Algebra**](https://webspace.maths.qmul.ac.uk/p.j.cameron/notes/linalg.pdf) written by [*Peter J. Cameron*](https://cameroncounts.github.io/web).
    - [**MATH 233 - Linear Algebra I Lecture Notes**](https://www.geneseo.edu/~aguilar/public/assets/courses/233/main_notes.pdf) written by [*Cesar O. Aguilar*](https://www.geneseo.edu/~aguilar/).
  - 🎲 **Probability & Statistics**: Probability distributions, mean/variance, etc.
    - [**MATH1024: Introduction to Probability and Statistics**](https://www.sujitsahu.com/teach/2020_math1024.pdf) written by [*Sujit Sahu*](https://www.southampton.ac.uk/people/5wynjr/professor-sujit-sahu).

## ⚙️ Setup

This project requires Python **v3.10** or higher. It was developed and tested using Python **v3.12.8**. If you encounter issues running the specified version of dependencies, consider using this version of Python.

### 📝 List of Dependencies

Installing `matplotlib` and `pandas` is **OPTIONAL**. They are used exclusively in the [**Looking Ahead Notebook**](./code/21-looking-ahead.ipynb) to show an application of using them.

[![ipykernel](https://img.shields.io/badge/ipykernel-6.29.5-ff69b4)](https://pypi.org/project/ipykernel/6.29.5/)
[![ipywidgets](https://img.shields.io/badge/ipywidgets-8.1.5-ff6347)](https://pypi.org/project/ipywidgets/8.1.5/)
[![matplotlib](https://img.shields.io/badge/matplotlib-3.10.0-green)](https://pypi.org/project/matplotlib/3.10.0/)
[![numpy](https://img.shields.io/badge/numpy-2.2.1-orange)](https://pypi.org/project/numpy/2.2.1/)
[![pandas](https://img.shields.io/badge/pandas-2.2.3-yellow)](https://pypi.org/project/pandas/2.2.3/)

### 📦 Install Dependencies

#### 📦 Method 1: Poetry (Recommended)

Use [**Poetry**](https://python-poetry.org/) for dependency management. It handles dependencies, virtual environments, and locking versions more efficiently than pip. To install dependencies using Poetry:

- **Option 1 [Recommended]**: Install exact dependency versions specified in [**poetry.lock**](./poetry.lock) for consistent environments:

  ```bash
  poetry install
  ```

- **Option 2**: Install the latest compatible dependency versions from [**pyproject.toml**](./pyproject.toml) and regenerate the [**poetry.lock**](./poetry.lock) file:

  ```bash
  poetry install --no-root
  ```

#### 📦 Method 2: Pip

Install all dependencies listed in [**requirements.txt**](./requirements.txt) using [**pip**](https://pip.pypa.io/en/stable/installation/):

```bash
pip install -r requirements.txt
```

#### 🌐 Connection Issues

If you encounter connection issues during installation, you can try extending the **timeout** and increasing the number of **retries** with the following:

- **For Poetry**: Use the following command to set the retries and timeout directly in the terminal **before running the install**:
  - **Windows**:
    - **PowerShell**:

      ```bash
      $env:POETRY_HTTP_TIMEOUT=300
      $env:POETRY_HTTP_RETRIES=10
      ```

    - **Command Prompt**:

      ```bash
      set POETRY_HTTP_TIMEOUT=300
      set POETRY_HTTP_RETRIES=10
      ```

  - **Linux/macOS**:
    - **Terminal**:

      ```bash
      export POETRY_HTTP_TIMEOUT=300
      export POETRY_HTTP_RETRIES=10
      ```

- **For Pip**: Use the `--retries` and `--timeout` flags directly in your pip command:

  ```bash
  pip install -r requirements.txt --retries 10 --timeout 300
  ```

### 🛠️ Usage Instructions

1. Open the root folder with [**VS Code**](https://code.visualstudio.com/) (`Ctrl/Cmd + K` followed by `Ctrl/Cmd + O`).
1. Open `.ipynb` files using the [**Jupyter extension**](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) integrated with **VS Code**.
1. Select the correct Python kernel and virtual environment where the dependencies were installed.
1. Allow **VS Code** to install any recommended dependencies for working with Jupyter Notebooks.

✍️ **Notes**:  

- It is **highly recommended** to stick with the exact dependency versions specified in [**poetry.lock**](./poetry.lock) or [**requirements.txt**](./requirements.txt) rather than using the latest package versions. The repository has been **tested** on these versions to ensure **compatibility** and **stability**.
- This repository is **actively maintained**, and dependencies are **updated regularly** to the latest **stable** versions.
- The **table of contents** embedded in the **notebooks** may not function correctly on **GitHub**.
- For an improved experience, open the notebooks **locally** or view them via [**nbviewer**](https://nbviewer.org/github/mr-pylin/numpy-workshop).

## 🔗 Useful Links

### **NumPy**

- Official Website:
  - The official website for NumPy, providing information, tutorials, and resources for the NumPy library
  - Official site: [numpy.org](https://numpy.org/)
- Documentation
  - Comprehensive guide and reference for all functionalities and features of the NumPy library
  - Doc: [numpy.org/doc](https://numpy.org/doc/)
- Source Code
  - Over 1500 contributors are currently working on NumPy.
  - Link: [github.com/numpy/numpy](https://github.com/numpy/numpy)

### **Looking Ahead**

- **Pandas**
  - A powerful, open-source data analysis and manipulation library built on top of NumPy for Python
  - Official site: [pandas.pydata.org](https://pandas.pydata.org/)
  - My Pandas Workshop: [Coming Soon](https://github.com/mr-pylin/#)
- **Data Visualization**
  - A comprehensive collection of Python libraries for creating static, animated, and interactive visualizations: **Matplotlib**, **Seaborn**, and **Plotly**.
  - Official sites: [matplotlib.org](https://matplotlib.org/) | [seaborn.pydata.org](https://seaborn.pydata.org/) | [plotly.com](https://plotly.com/)
  - My MatPlotLib Workshop: [github.com/mr-pylin/data-visualization-workshop](https://github.com/mr-pylin/data-visualization-workshop)
- **PyTorch**
  - An open-source **machine learning** library for Python developed by [**Meta AI**](https://ai.meta.com/), used for applications such as **deep learning** and **neural networks**.
  - Official site: [pytorch.org](https://pytorch.org/)
  - My PyTorch Workshop: [github.com/mr-pylin/pytorch-workshop](https://github.com/mr-pylin/pytorch-workshop)

## 🔍 Find Me

Any mistakes, suggestions, or contributions? Feel free to reach out to me at:

- 📍[**linktr.ee/mr_pylin**](https://linktr.ee/mr_pylin)

I look forward to connecting with you! 🏃‍♂️

## 📄 License

This project is licensed under the **[Apache License 2.0](./LICENSE)**.  
You are free to **use**, **modify**, and **distribute** this code, but you **must** include copies of both the [**LICENSE**](./LICENSE) and [**NOTICE**](./NOTICE) files in any distribution of your work.
