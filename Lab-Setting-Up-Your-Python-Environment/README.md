# Lab: Setting Up Your Python Environment

## Introduction

In this lab, you’ll set up a professional Python environment and create your first Jupyter Notebook. You’ll practise working with code and markdown cells, organise a reproducible project structure, and version your work using Git and GitHub.

---

## Learning Objectives

By the end of this lab, you'll be able to:

- Install and configure Python and Jupyter Notebook using Anaconda  
- Create and run a Jupyter Notebook with both code and markdown cells  
- Organise a clean and reproducible project folder structure  
- Initialise a Git repository and push your project to GitHub  

---

## Getting Started

### Prerequisites

Before beginning this lab, ensure you have:

- Anaconda installed (Python 3 included)  
- Access to a GitHub account  
- Git installed on your local machine  

---

### Setup Instructions

1. Open **Anaconda Navigator** and launch **Jupyter Notebook**.  
2. Create a new folder on your computer named `python-environment-lab`.  
3. Open this folder in Jupyter Notebook.  
4. Inside the folder, create a new notebook using **Python 3 (ipykernel)**.  
5. Rename the notebook to `environment-check.ipynb`.

---

### Lab Structure

By the end of this lab, your project should look like this:

```text
python-environment-lab/
│
├── notebooks/
│   └── environment-check.ipynb
├── data/
├── README.md
```

## Exercise Overview

In this lab, you’ll verify that your Python environment is correctly set up, practise writing and documenting code in Jupyter, and prepare a reproducible project structure. You’ll also initialise version control and publish a reproducible project to GitHub.

### How to Work Through the Lab

Follow the steps below to complete the lab in order. Run each step as you go to confirm your environment is working correctly.

1. Verify your Python environment by creating a code cell in Jupyter and running:
   ```python
   print("Python environment successfully configured!") ```

2. Create a markdown cell that includes:

- A clear title for the notebook
- A short description explaining what the notebook does

3. Add a second code cell where you:

- Assign two variables
- Perform a simple calculation
- Display the output

4. Create the following folders if they do not already exist:

```text
notebooks/
data/
```
5. Move your notebook into the `notebooks/` folder.

6. Create a `README.md` file at the root of the project describing the purpose of this lab.

## Version Control and Submission

Open a terminal in your project folder.

Initialise a Git repository:

```bash
git init
git add .
git commit -m "Initial environment setup"
```
Create a new repository on GitHub.

Connect your local project to GitHub and push your work:

```bash
git branch -M main
git push -u origin main
```
A completed lab includes a working Jupyter notebook, a README.md file, and a GitHub repository containing the full project structure.

### Tips for Success

- Run each notebook cell as you go to confirm everything works as expected  
- Use markdown cells to explain what your code is doing  
- Save your notebook frequently  
- Keep your folder structure clean and organised  


## Additional Resources

- **Anaconda Documentation**: https://docs.anaconda.com  
- **Jupyter Notebook Documentation**: https://jupyter.org/documentation  
- **GitHub Guides**: https://docs.github.com  
