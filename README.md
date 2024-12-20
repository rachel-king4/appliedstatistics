# appliedstatistics
Repository for Applied Statistics Module Winter 2024

## Contents of the Repository

This repository contains coursework created and maintained as part of the module Applied Statistics, undertaken as part of the Higher Diploma in Science in Data Analytics in ATU, Galway.

The repository contains two Jupyter notebooks:

- tasks.ipynb (contains my answers to assessment tasks set out by the module lecturer, accounts for 40% of the module assessment)
- project.ipynb (contains my code and notes for the project assessment set out by the module lecturer, accounts for 40% of the module assessment)

Other content in the repository is a .gitignore file which specifies intentionally untracked files that Git should ignore.

## Learning Outcomes

1. Data Exploration and Preprocessing

    - Understand how to import and clean real-world data for statistical analysis.
    - Explore data distributions and visualize key features using appropriate plots.

2. Statistical Test Selection

    - Recognize different types of claims and select the appropriate statistical test (e.g., t-test, ANOVA).
    - Justify the choice of statistical test based on the nature of the data (e.g., continuous vs. categorical, paired vs. unpaired).
    - Understand the assumptions underlying common statistical tests (e.g., normality, homogeneity of variance) and check if they are met.

3. Performing Statistical Analysis

    - Conduct statistical tests using Python libraries (e.g., scipy, statsmodels) to test hypotheses.
    - Interpret p-values and test statistics in the context of the claim being made.

4. Reproducibility and Documentation

    - Use Jupyter notebooks to document the process of data analysis, including data exploration, hypothesis testing, and result interpretation.
    - Include appropriate comments and explanations in notebooks to facilitate understanding of statistical concepts.

5. Critical Thinking and Communication

    - Critically evaluate the assumptions and limitations of statistical tests used.

## Installation and Usage

The Jupyter notebooks "tasks.ipynb" and "project.ipynb" can be ran in any code editor such as Visual Studio Code, or using the web application JupyterLab.

The notebooks contain all details in relation to both the Tasks and Project assessments for the module, including all references to research performed as part of the assessments.

To run the notebooks, the repository must first be cloned to the user's machine, which can be achieved by following the below instructions:

- First, navigate to the directory that you would like to clone the repository into using commands like:
    > cd: to change your working directory.

    > cd ../ to "go back" a level in your directory tree.

- Next, clone the remote repository and create a local copy on your machine using this command:
    > git clone https://github.com/rachel-king4/appliedstatistics.git

- Any changes made to the remote repository will not automatically sync with the local cloned copy. To update the local directory, navigate to the cloned directory and use this command:
    > git pull

Once the repository is cloned, the cloned directory can be opened and ran in a code editor such as Visual Studio Code.


## Dependencies

You can install all the required dependencies in one step by using the requirements.txt file:

Clone the repository and navigate to the project directory.
Install the dependencies:

`pip install -r requirements.txt`


Alternatively, you can set up a virtual environment to manage your dependencies:

1. Create a virtual environment:

    `python -m venv env`

2. Activate the environment:

    - On Windows:

        `.\env\Scripts\activate`

    - On macOS/Linux:

        `source env/bin/activate`

3. Install dependencies:

    `pip install -r requirements.txt`

By setting up the above dependencies, you'll be able to run the notebooks, perform statistical analysis, and work with the PlantGrowth dataset.
