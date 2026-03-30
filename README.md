# Introduction to Python and Jupyter Notebooks

**Session Time:** 120 minutes  

---

## Prerequisites
- None  
This is an entry-level module designed for learners with no prior programming experience.

---

## Table of Contents
1. [Module Overview](#module-overview)  
2. [Learning Objectives](#learning-objectives)  
3. [What You Will Learn](#what-you-will-learn)  
4. [Why Python for Data & AI?](#why-python-for-data--ai)  
5. [Setting Up Your Python Environment](#setting-up-your-python-environment)  
6. [Introduction to Jupyter Notebooks](#introduction-to-jupyter-notebooks)  
7. [Working with Code and Markdown Cells](#working-with-code-and-markdown-cells)  
8. [Reproducible Workflows and Project Structure](#reproducible-workflows-and-project-structure)  
9. [Version Control with Git and GitHub](#version-control-with-git-and-github)  
10. [Wrap-Up Reflection](#wrap-up-reflection)  
11. [Resources](#resources)

---

## Module Overview

In this module, you’ll set up a professional Python environment and explore Jupyter Notebooks as the core workspace for data analysis and AI workflows. You’ll learn how to execute Python code, document your work using markdown, and organise files in a reproducible project structure aligned with industry best practices.

---

## Learning Objectives

By the end of this module, you’ll be able to:
- Install and configure Python, Jupyter Notebook, and core tools for analytical work  
- Navigate the Jupyter Notebook interface and execute Python code cells  
- Use markdown cells to document analysis and improve reproducibility  
- Organise a clean project structure suitable for data analytics workflows  
- Initialise a Git repository and push your first project to GitHub  

---
## Session Breakdown

| Segment | Topic | Duration (minutes) |
|--------|-------|--------------------|
| 1 | Environment Setup & Course Orientation | 25 |
| 2 | Introduction to Jupyter Notebooks | 25 |
| 3 | Working with Code and Markdown Cells | 30 |
| 4 | Reproducible Project Structure & Git Basics | 25 |
| 5 | Wrap-Up & Lab Overview | 15 |

---
## What You Will Learn

This module introduces the foundational tools used throughout the course. You’ll focus on environment setup, interactive coding, and documentation to ensure you’re ready to work confidently with Python in later analytical and AI-focused modules.

Topics include:
- Why Python is widely used in data and AI roles  
- Installing Python and Jupyter via Anaconda  
- Understanding notebooks as reproducible analytical documents  
- Writing and running simple Python code  
- Documenting work clearly using markdown  
- Versioning your work with Git and GitHub  

---

## Why Python for Data & AI?

Python is one of the most widely used programming languages in data analytics and AI due to:
- Its clean, readable syntax  
- A large open-source ecosystem  
- Powerful libraries for data analysis, statistics, and machine learning  

Python enables analysts and AI practitioners to move efficiently from raw data to insight, combining computation, analysis, and communication in a single workflow.

---

## 1.Setting Up Your Python Environment

### Step 1: Install Anaconda

Anaconda bundles Python, Jupyter Notebook, and essential tools in one installation.

1. Visit: https://www.anaconda.com/products/distribution  
2. Download the installer for your operating system  
3. Follow the installation instructions  
4. Confirm installation by opening **Anaconda Navigator**

> Jupyter Notebook is included automatically with Anaconda.

---

### Step 2: Verify Python and Jupyter

Once installed:

- Launch **Jupyter Notebook** from Anaconda Navigator  
- Create a new notebook using **Python 3 (ipykernel)**  
- Run the following code cell to confirm Python is working:

```python
print("Python is ready for data analysis!")
```
If the message prints successfully, your environment is correctly configured.

---

## 2.Introduction to Jupyter Notebooks

A Jupyter Notebook is an interactive document that combines:

- Executable Python code  
- Formatted text using markdown  
- Outputs such as tables and visualisations  

This makes notebooks ideal for exploratory analysis, experimentation, and reproducible reporting.

---

### Key Interface Elements

#### Code cells
Used to write and execute Python code.

#### Markdown cells
Used to add explanations, headings, lists, links, and documentation.

#### Kernel
Runs your Python code in the background and manages variables and execution state.

---

## 3.Working with Code and Markdown Cells

### Code Cells

Use code cells to write and execute Python:

```python
x = 10
y = 5
x + y
```
When you run a code cell, the output appears directly below it.

---
### Markdown Cells

Use markdown cells to document your work:

```markdown
## My First Analysis
This notebook explores basic Python operations.
```
Clear documentation improves readability, collaboration, and reproducibility.

---
## Reproducible Workflows and Project Structure

Professional data work relies on reproducibility. In this course, you’ll follow a consistent project structure:

```text
project-name/
│
├── notebooks/
│   └── analysis.ipynb
├── data/
│   └── raw-data.csv
├── README.md
```
This structure helps keep code, data, and documentation organised and easy to maintain.

----
## 4.Version Control with Git and GitHub

You’ll use Git and GitHub to track changes and share your work.

Initialise a Git repository:

```bash
git init
git add .
git commit -m "Initial project setup"
```
Push your project to GitHub:

```bash
git branch -M main
git push -u origin main
 ```
Version control ensures your work is transparent, collaborative, and reproducible.

---
## 5.Wrap-Up Reflection

- Why is Jupyter Notebook well suited for data analysis workflows?  
- How does documenting code improve reproducibility?  
- What challenges might arise if environments are not properly configured?

---

## Resources

- **Anaconda Distribution**: https://www.anaconda.com  
- **Jupyter Documentation**: https://jupyter.org/documentation  
- **Python Official Documentation**: https://docs.python.org/3/  
- **GitHub Guides**: https://docs.github.com 
