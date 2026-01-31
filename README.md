# Machine-Learning-CodeBasics
Machine Learning course implementation by code basics : https://codebasics.io/courses/machine-learning-for-data-science-beginners-to-advanced

# How to clone a github folder
1. `git init` on the folder 
2. `git clone https://github.com/nandini2294/Machine-Learning-CodeBasics.git` to create this folder 
3. `git remote -v` to check the remote connections

# Creating virtual environments
1. Run `uv init`
2. Run `uv venv`
3. Run `source .venv/bin/activate`
4. Run `uv add ipykernel` - Make UV Virtual Environment Show Up as a Jupyter Kernel `uv pip show ipykernel`
5. Run `python -m ipykernel install --user --name=ml-codebasics --display-name "ML CodeBasics (uv)"` - register your environment as a Jupyter kernel
6. `jupyter kernelspec list` confirm kernel registration
7. Go to jupyter notebook , select kernel for jupyter notebook
8. IF your kernel , doesn't show up then click "CMD + Shift + P" and click on "Developer: Reload Window" and then try find the kernel again
9. Do `uv sync` if at any point when you re-open again and you cant find kernel 
<!-- 8. Run `uv run jupyter notebook`  -->

# uv commands to manage packaging
1. Install a package `uv add numpy`
2. Remove a package  `uv remove numpy`
3. List installed packages `uv pip list`

# setting up gitignore
1. `touch .gitignore`
2. Add whatever you want to ignore in the .gitignore file 


# Dataset link: UC ML Datasets https://archive.ics.uci.edu/datasets/
1. https://archive.ics.uci.edu/dataset/9/auto+mpg 