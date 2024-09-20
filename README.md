# Project Title: Homework 1 - Deep vs Shallow Models, Optimization, and Generalization

## Brief Description

This project consists of three major tasks:

### 1. Deep vs Shallow Models:

•	Simulate a Function:

We simulate a function and train several models (both shallow and deep) on this task. Multiple models with the same number of parameters but different structures are used. The training losses are plotted to compare their performance.

•	Train on Actual Task:

Multiple models are trained on real tasks, and both training loss and accuracy are plotted for comparison.
### 2. Optimization:

•	Visualize the optimization process, including observing gradient norms during training.

•	Investigate what happens when the gradient is close to zero and analyze the results of minimizing the loss over iterations.

### 3. Generalization:

•	Can Network Fit Random Labels?

Experiment with random labels and examine how well the networks generalize.

•	Number of Parameters vs Generalization:

Analyze the impact of model size on generalization by varying the number of parameters.

•	Flatness vs Generalization:

Investigate the relationship between the flatness of error surfaces and model generalization.

## Requirements
•	Jupyter Notebook
•	Python 3.x
•	Required libraries:

o	torch

o	numpy

o	matplotlib

o	scikit-learn

o	sympy

## Installation
1.	Clone the repository:
bash
git clone https://github.com/Mahmoud118/HW1
2.	Install the required libraries from the requirements.txt file:
bash
pip install -r requirements.txt
3.	Launch Jupyter Notebook and run the models:
bash
jupyter notebook
