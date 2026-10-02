# Welcome

This folder contains materials for your Posit Academy course project. You will complete this project in Positron using a dedicated instance of Posit Workbench (instructions for accessing Posit Workbench will be shared at the beginning of your course).

**By accessing these Posit Academy course materials, you agree to Posit's [End User License Agreement](https://posit.co/about/eula/) and [Learning Services Agreement](https://posit.co/learning-services-agreement/).**

## Project Structure

- **Quarto (.qmd) files**: These are the project milestone files where you'll complete your work each week

- **data/**: Contains the datasets you'll explore along with "solution" datasets for you to compare against your work

- **assets/**: Contains data dictionaries explaining the variables in each dataset

- **images/**: Contains milestone "solution" images for you to compare against your work

## Getting Started

If Positron shows a **Restricted Mode** banner when you open this folder, click **Trust this folder** in the Console, then click **Trust**.

**Step 1: Install the Python packages you will need for this project.**

1. Open the **Terminal** tab (just to the right of the **Console** tab).

2. Copy and paste this command into the Terminal and press <kbd>Enter</kbd>:

   ```bash
   uv venv --allow-existing && uv pip install jupyter pandas palmerpenguins plotnine scikit-learn statsmodels
   ```

   This uses [uv](https://docs.astral.sh/uv/), a fast Python package manager, to create a virtual environment (a `.venv` folder in this project) and install the packages into it. It may take a few minutes to complete.

**Step 2: Tell Positron to use your project's Python environment.**

1. Click the interpreter button in the top right corner of Positron. It shows **Start Session**, or the name of a Python or R version. (If a menu of running sessions opens, click **New Console Session...** first.)

2. Select the Python whose name ends in **(uv: academy-python-stock-portfolios)**. Its path ends in `.venv/bin/python`. It may not be at the top of the list; the **(Global)** Pythons don't have your packages.

You only need to do this once. The next time you open this project, Positron starts its environment automatically.

For step-by-step instructions with screenshots, see the **Set Up Your Project** tutorial on your course site.

**Step 3: Open your first milestone file.**

1. In the Explorer tab on the left, open the file `indexes_01_quarto_python-intro.qmd`

2. Follow the instructions in this file to complete the exercises

## Note: One milestone at a time

Once you have set up your project in Positron, you will have access to all of the milestone files for your project. However, we encourage you to **only focus on the milestone corresponding to the current week of your Academy course**.

Milestone files are numbered sequentially according to the week of the course. For example:

Week 1 = `indexes_01_quarto_python-intro.qmd`  
Week 2 = `indexes_02_quarto_python-wrangle.qmd`  
etc.
