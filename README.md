# CS598DLH
CS598 DLH Final Project
This repository contains the code, data, and pdf report for our Final Projcet submission. 

The video presentationis available at https://youtu.be/IAoQO6pEZWI 

If you have any problems, contact johnh7@illinois.edu.

## Contents
- README.md  - this files
- TestCoxNeural_3.ipynb - Notebook with the final project code (start notebook and run_all)
- data.zip - contains SEER raw data (unzip creates data/seer_processed.csv used by notebook)
- requirements.txt - list of python packages needed to run the notebook

## Notebook Installation and Execution
Download the TestCoxNeural_3.ipynb notebook, requirements.txt and data.zip to your target directory.  Unzip data.zip that creates the data directory with the dataset file (./data/seer_processed.csv).  The notebook will look for the SEER data in this location. 

The notebook is self-contained and run_all preforms the following:
- Load and preprocesses the datasets (SEER, Metabric, SUPPORT)
- Trains the model for each data set
- Evaluates the model with the test sets from each dataset
- Presents the result tables and charts.
- note: the note contains a grid testing routine for hyperparameters that does not run by default.

Enjoy!



