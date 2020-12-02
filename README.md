# Machine Learning and Statistics

# **Tasks 2020**

    1. Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. The code should not depend on any module from the standard library or otherwise.
    2. The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table, stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value.
    3. The standard deviation of an array of numbers x is calculated using numpy as `np.sqrt(np.sum((x - np.mean(x))**2)/len(x))`. However, Microsoft Excel has two different versions of the standard deviation calculation, `STDEV.P` and `STDEV.S`. The `STDEV.P` function performs the above calculation but in the `STDEV.S` calculation the division is by `len(x)-1` rather than `len(x)`. Research these Excel functions, writing a note in a Markdown cell about the difference between them. Then use `numpy` to perform a simulation demonstrating that the `STDEV.S` calculation is a better estimate for the standard deviation of a population when performed on a sample. 
    4. Use `scikit-learn` to apply `k-means` clustering to Fisher’s famous Iris data set. Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris.



For more information please visit the Githib repository: 
https://github.com/JuliaMal/Machine_learning_and_stats_Assessment

The Github repository contains the following files:
   1. Tasks.ipynb - This is a Jupyter notebook that contains the main body of work, explanations, notes. references. etc.
   2. iris.csv - This is the Fisher's iris dataset used for analysis.
   3. ReadMe.md - This is a Markdown file, containing explanation what is saved in the Github repository and instructions how to run Jupyter notebook.
   4. .gitignore - This file tells git which files (or patterns) should be ignored. In our case it's Python.
   5. LICENSE - This is an open source license. As this repository is mainated as PUBLIC, a license needs to be in place, so that others are free to use, change and distribute it.

   #1 How to download this repository:

        1. Go to Github or click on the link provided earlier.
        2. Clich the "Clone or Download" button
        3. Choose between the options "Open in Desktop" or "Download ZIP"

   #2 How to run the code:

        1. The Jupyter Notebook software is included in the Python installation we obtained from Anaconda. 
        2. First you need to install Python from Anaconda.
        3. Then open a terminal window.
        4. Make sure that you're in the same directory as the saved in the repository, you have downloaded in step #1 (Type cd Path_to_the_folder, e.g. cd C:\User\GMIT\Assessment_tasks)
        5. Type jupyter notebook or jupyter lab to launch the Jupyter Notebook App.
        6. The notebook interface will appear in a new browser window or tab.
