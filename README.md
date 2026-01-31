# A-Priori Algorithm for Frequent Itemset Mining

## Project Overview
This project implements the A-Priori algorithm, a fundamental technique in data mining used for frequent itemset mining and association rule learning over transactional databases. The main goal is to identify sets of products that frequently appear together in purchase transactions and derive meaningful association rules from these patterns.

## Dataset
The project utilizes a groceries dataset containing approximately 9,835 transaction baskets. Each basket represents a collection of items purchased together, such as milk, vegetables, fruit, and snacks.

## Key Features
- Implementation of the A-Priori algorithm to find frequent itemsets of varying sizes.
- Calculation of support and confidence metrics for association patterns.
- Generation of association rules based on frequent itemsets.
- Analysis of item relationships within the grocery transaction data.

## Technologies Used
- Python: The primary programming language for implementing the algorithm.
- Jupyter Notebook: Used for interactive development, documentation, and visualization of results.
- NumPy: Utilized for efficient numerical computations and data structures.
- Google Colab: Supported for cloud-based execution and easy access to drive storage.

## Implementation Details
The implementation follows these logical steps:
1. Data Loading: Importing the transaction data from a CSV file.
2. Data Preprocessing: Organizing transactions into an in-memory basket structure.
3. Frequent Itemset Generation: Iteratively finding itemsets that meet a predefined support threshold.
4. Rule Extraction: Generating association rules from the frequent itemsets and filtering them based on confidence.

## Usage
To run this project:
1. Ensure Python and Jupyter are installed on your system.
2. Install the required NumPy package if it is not already available.
3. Open the B25CHKH034_Nguyen_Hoang_Lan_m2_ds_algods_frequent (1).ipynb notebook in a Jupyter environment.
4. Follow the steps outlined in the notebook cells to execute the mining process.

## Student Information
This work was completed as part of the Data Mining (Khai pha du lieu) course.
Author: Nguyen Hoang Lan
Class: CS Master
