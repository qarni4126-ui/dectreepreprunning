Decision Tree Classifier with Pre-Pruning on Digits Dataset

This project implements a Decision Tree Classifier with pre-pruning techniques (such as max_depth, min_samples_split, and min_samples_leaf) using the Digits dataset from scikit-learn.
The goal is to prevent overfitting by restricting the growth of the tree before it fully expands.

📌 Project Overview

Decision trees tend to overfit when grown without limitations.
Pre-pruning introduces constraints during tree construction, leading to better generalization.

This repository includes:

Training an unpruned (baseline) decision tree

Applying multiple pre-pruning strategies

Comparing performance between baseline vs. pruned models

Visualizations of accuracy vs. pruning parameters

🧰 Technologies Used

Python

scikit-learn

NumPy

Matplotlib

📂 Dataset

The Digits dataset from scikit-learn contains 8×8 pixel handwritten digits (0–9).
It is a 10-class classification problem with 1,797 samples.
