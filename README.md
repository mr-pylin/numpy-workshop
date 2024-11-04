# 🔢 NumPy Workshop
An in-depth guide to mastering NumPy, covering fundamental to advanced array operations for data science and numerical computing.

## 📖 Table of Contents
0. **[Array](./codes/00_array.ipynb)**  
   Introduction to NumPy arrays
0. **[Arithmetic Operations](./codes/01_arithmetic-operations.ipynb)**  
   Arithmetic operations between (array & scalar) or (array & array)
0. **[Comparative Operations](./codes/02_comparative-operations.ipynb)**  
   Comparative operations between (array & scalar) or (array & array)
0. **[Index & Slice](./codes/03_index-&-slice.ipynb)**  
   Basic and advanced indexing and slicing arrays including Mask & Filters
0. **[Axes](./codes/04_axes.ipynb)**  
   Understanding use of axes in multi-dimensional arrays combined with methods [the hardest part in NumPy for newbies in my opinion]
0. **[Array Modifications](./codes/05_array-modifications.ipynb)**  
   Techniques for updating values, appending, inserting, reshaping, concatenating, ...
0. **[NdArray properties & methods](./codes/06_ndarray-members.ipynb)**  
   Comprehensive overview of properties and methods associated with NumPy arrays.
0. **[Array Creation](./codes/07_array-creation.ipynb)**  
   Various methods to create NumPy arrays (e.g., `numpy.array`, `numpy.zeros`, etc.).
0. **[Mathematics](./codes/08_mathematics.ipynb)**  
   Mathematical functions and operations available in NumPy
0. **[Statistics](./codes/09_statistics.ipynb)**  
   Statistical functions for data analysis (mean, median, variance, etc.).
0. **[Sort, Search & Count](./codes/10_sort-search-count.ipynb)**  
   Methods for sorting, searching, and counting elements in arrays.
0. **[Logic](./codes/11_logic.ipynb)**  
   Logical operations and boolean indexing with NumPy arrays.
0. **[Set](./codes/12_set.ipynb)**  
   Set operations for array elements (union, intersection, difference).
0. **[Linear Algebra](./codes/13_linear-algebra.ipynb)**  
   Fundamental linear algebra operations using NumPy (matrix multiplication, determinants).
0. **[Structured Array](./codes/14_structured-array.ipynb)**  
   Creating and manipulating structured arrays with custom data types.
0. **[Input/Output](./codes/15_input-output.ipynb)**  
   Techniques for reading from and writing to files using NumPy.
0. **[Random Generator](./codes/16_random-generator.ipynb)**  
   Generating random numbers and distributions with NumPy's random module.
0. **[Fourier Transform](./codes/17_fourier-transform.ipynb)**  
   Understanding and applying Fourier transforms in NumPy.
0. **[Efficient Computing](./codes/18_efficient-computing.ipynb)**  
   Strategies for optimizing performance and memory usage in NumPy operations.
0. **[Miscellaneous](./codes/19_miscellaneous.ipynb)**  
   Additional topics and advanced features in NumPy.
0. **[Looking Ahead](./codes/20_looking-ahead.ipynb)**  
   Introduction to *Pandas* for data manipulation and *Matplotlib* for data visualization.

## 📋 Prerequisites
   - **Programming Fundamentals**
      - Proficiency in Python (data types, control structures, functions, etc.).
         - My Python Workshop: [github.com/mr-pylin/python-workshop](https://github.com/mr-pylin/python-workshop)
   - **Mathematics for Machine Learning**
      - Linear Algebra: Vectors, matrices, matrix operations.
         - [*Linear Algebra Review and Reference*](https://www.cs.cmu.edu/%7Ezkolter/course/linalg/linalg_notes.pdf) written by [Zico Kolter](https://zicokolter.com)
         - [*Notes on Linear Algebra*](https://webspace.maths.qmul.ac.uk/p.j.cameron/notes/linalg.pdf) written by [Peter J. Cameron](https://cameroncounts.github.io/web)
         - [*MATH 233 - Linear Algebra I Lecture Notes*](https://www.geneseo.edu/~aguilar/public/assets/courses/233/main_notes.pdf) written by [Cesar O. Aguilar](https://www.geneseo.edu/~aguilar/)
      - Probability & Statistics: Probability distributions, mean/variance, etc.
         - [*MATH1024: Introduction to Probability and Statistics*](https://www.sujitsahu.com/teach/2020_math1024.pdf) written by [Sujit Sahu](https://www.southampton.ac.uk/people/5wynjr/professor-sujit-sahu)

# ⚙️ Setup
This project was developed using Python `v3.12.3`. If you encounter issues running the specified version of dependencies, consider using this specific Python version.

## 📦 Installing Dependencies
You can install all dependencies listed in `requirements.txt` using [pip](https://pip.pypa.io/en/stable/installation/).
```bash
pip install -r requirements.txt
```

## 🛠️ Usage Instructions
   - Open the root folder with [VS Code](https://code.visualstudio.com/)
      - **Windows/Linux**: `Ctrl + K` followed by `Ctrl + O`
      - **macOS**: `Cmd + K` followed by `Cmd + O`
   - Open `.ipynb` files using [Jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) integrated with **VS Code**
   - Allow **VS Code** to install any recommended dependencies for working with Jupyter Notebooks.
   - Note: Jupyter is integrated with both **VS Code** & **[Google Colab](https://colab.research.google.com/)**

# 🔗 Useful Links
   - **NumPy Website**:
      - The official website for NumPy, providing information, tutorials, and resources for the NumPy library
      - Official site: [numpy.org](https://numpy.org/)
   - **NumPy Documentation**:
      - Comprehensive guide and reference for all functionalities and features of the NumPy library
      - Doc: [numpy.org/doc](https://numpy.org/doc/)
   - **NumPy Source Code**:
      - Over 1500 contributors are currently working on NumPy.
      - Link: [github.com/numpy/numpy](https://github.com/numpy/numpy)
   - **Looking Ahead**:
      - **Pandas**
         - A powerful, open-source data analysis and manipulation library built on top of NumPy for Python
         - Official site: [pandas.pydata.org](https://pandas.pydata.org/)
         - My Pandas Workshop: [Coming Soon](https://github.com/mr-pylin/#)
      - **MatPlotLib**
         - A comprehensive library for creating static, animated, and interactive visualizations in Python
         - Official site: [matplotlib.org](https://matplotlib.org/)
         - My MatPlotLib Workshop: [Coming Soon](https://github.com/mr-pylin/#)
      - **PyTorch**
         - An open-source machine learning library for Python developed by [Meta AI](https://ai.meta.com/), used for applications such as deep learning and neural networks.
         - Official site: [pytorch.org](https://pytorch.org/)
         - My PyTorch Workshop: [github.com/mr-pylin/pytorch-workshop](https://github.com/mr-pylin/pytorch-workshop)

# 🔍 Find Me
Any mistakes, suggestions, or contributions? Feel free to reach out to me at:
   - 📍[linktr.ee/mr_pylin](https://linktr.ee/mr_pylin)
   
I look forward to connecting with you! 🏃‍♂️

# 📄 License
This project is licensed under the **[Apache License 2.0](./LICENSE)**.  
You are free to use, modify, and distribute this code, but you must include copies of both the [**LICENSE**](./LICENSE) and [**NOTICE**](./NOTICE) files in any distribution of your work.