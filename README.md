# 🔢 NumPy Workshop

[![License](https://img.shields.io/github/license/mr-pylin/numpy-workshop)](https://github.com/mr-pylin/numpy-workshop/blob/main/LICENSE)
[![Python Version](https://img.shields.io/badge/Python-3.12.3-blue?logo=python&logoColor=white)](https://www.python.org/downloads/release/python-3123/)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/1faf9d4577d3406a9ac65a4cb8d3d4f1)](https://app.codacy.com/gh/mr-pylin/numpy-workshop/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![Code Style](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
![Repo Size](https://img.shields.io/github/repo-size/mr-pylin/numpy-workshop)
![Last Updated](https://img.shields.io/github/last-commit/mr-pylin/numpy-workshop)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/mr-pylin/numpy-workshop/pulls)

An in-depth guide to mastering **NumPy**, covering fundamental to advanced array operations for **data science** and **numerical computing**.

## 📖 Table of Contents

### 📖 Main Notebooks

1. [**Array Basics**](./codes/01-array-basics.ipynb)  
   Introduction to NumPy arrays
1. [**Arithmetic Operations**](./codes/02-arithmetic-operations.ipynb)  
   Arithmetic operations between (array & scalar) or (array & array)
1. [**Comparative Operations**](./codes/03-comparative-operations.ipynb)  
   Comparative operations between (array & scalar) or (array & array)
1. [**Index & Slice**](./codes/04-index-&-slice.ipynb)  
   Basic and advanced indexing and slicing arrays including Mask & Filters
1. [**Axes**](./codes/05-axes.ipynb)  
   Understanding use of axes in multi-dimensional arrays combined with methods [the hardest part in NumPy for newbies in my opinion]
1. [**Array Manipulations**](./codes/06-array-manipulations.ipynb)  
   Techniques for updating values, appending, inserting, reshaping, concatenating, ...
1. [**NdArray properties & methods**](./codes/07-ndarray-members.ipynb)  
   Comprehensive overview of properties and methods associated with NumPy arrays.
1. [**Array Creation**](./codes/08-array-creation.ipynb)  
   Various methods to create NumPy arrays (e.g., `numpy.array`, `numpy.zeros`, etc.).
1. [**Mathematics**](./codes/09-mathematics.ipynb)  
   Mathematical functions and operations available in NumPy
1. [**Statistics**](./codes/10-statistics.ipynb)  
   Statistical functions for data analysis (mean, median, variance, etc.).
1. [**Sort, Search & Count**](./codes/11-sort-search-count.ipynb)  
   Methods for sorting, searching, and counting elements in arrays.
1. [**Logic**](./codes/12-logic.ipynb)  
   Logical operations and boolean indexing with NumPy arrays.
1. [**Set**](./codes/13-set.ipynb)  
   Set operations for array elements (union, intersection, difference).
1. [**Linear Algebra**](./codes/14-linear-algebra.ipynb)  
   Fundamental linear algebra operations using NumPy (matrix multiplication, determinants).
1. [**Structured Array**](./codes/15-structured-array.ipynb)  
   Creating and manipulating structured arrays with custom data types.
1. [**Input/Output**](./codes/16-input-output.ipynb)  
   Techniques for reading from and writing to files using NumPy.
1. [**Random Generator**](./codes/17-random-generator.ipynb)  
   Generating random numbers and distributions with NumPy's random module.
1. [**Fourier Transform**](./codes/18-fourier-transform.ipynb)  
   Understanding and applying Fourier transforms in NumPy.
1. [**Efficient Computing**](./codes/19-efficient-computing.ipynb)  
   Strategies for optimizing performance and memory usage in NumPy operations.
1. [**Miscellaneous**](./codes/20-miscellaneous.ipynb)  
   Additional topics and advanced features in NumPy.
1. [**Looking Ahead**](./codes/21-looking-ahead.ipynb)  
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

This project was developed using Python **v3.12.3**. If you encounter issues running the specified version of dependencies, consider using this specific Python version.

### 📝 List of Dependencies

Installing **matplotlib** and **pandas** is **OPTIONAL**. They are used exclusively in the [**Looking Ahead Notebook**](./codes/21-looking-ahead.ipynb) to show an application of using them.

[![numpy](https://img.shields.io/badge/numpy-2.1.3-orange)](https://pypi.org/project/numpy/2.1.3/)
[![matplotlib](https://img.shields.io/badge/matplotlib-3.9.1-green)](https://pypi.org/project/matplotlib/3.9.1/)
[![pandas](https://img.shields.io/badge/pandas-2.2.2-yellow)](https://pypi.org/project/pandas/2.2.2/)

### 📦 Installing Dependencies

You can install all dependencies listed in [**requirements.txt**](./requirements.txt) using [**pip**](https://pip.pypa.io/en/stable/installation/):

```bash
pip install -r requirements.txt
```

### 🛠️ Usage Instructions

1. Open the root folder with [**VS Code**](https://code.visualstudio.com/):
    - **Windows/Linux**: `Ctrl + K` followed by `Ctrl + O`
    - **macOS**: `Cmd + K` followed by `Cmd + O`
1. Open `.ipynb` files using [**Jupyter extension**](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) integrated with **VS Code**.
1. Allow **VS Code** to install any **recommended dependencies** for working with Jupyter Notebooks.

✍️ **Notes**:  

- The **table of contents** embedded in the **notebooks** is not fully functional on **GitHub**!
- To navigate the **table of contents** effectively, open the notebooks **locally** or view them via [**nbviewer**](https://nbviewer.org/github/mr-pylin/pytorch-workshop) for a better experience.

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
