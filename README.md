# Market Basket Analysis Using Apriori and Association Rules

This project performs market basket analysis on transaction data using the Apriori algorithm and association rule mining. It processes the data from a CSV file, generates frequent itemsets, and then extracts association rules with various metrics to help identify important relationships between products.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)


## Overview

This repository contains a Python script designed to analyze transaction data from a CSV file. It performs the following tasks:

- Reads and preprocesses transaction data.
- Converts transactions into a one-hot encoded format suitable for analysis.
- Applies the Apriori algorithm to identify frequent itemsets.
- Generates and displays association rules along with important metrics such as support, confidence, lift, leverage, and conviction.

## Features

- **Data Import:** Reads transactions from a CSV file.
- **Data Preprocessing:** Cleans and transforms transaction data into a list format and then into a one-hot encoded DataFrame.
- **Frequent Itemset Mining:** Uses the Apriori algorithm to find item combinations that occur frequently in the dataset.
- **Association Rule Mining:** Extracts rules that show how the purchase of certain items is associated with others.
- **Interpretation Metrics:** Outputs support, confidence, lift, and several additional metrics to help in the analysis.

## Prerequisites

- Python 3.x
- [Pandas](https://pandas.pydata.org/)
- [mlxtend](http://rasbt.github.io/mlxtend/)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/viznuv/market-basket-analysis.git
   cd market-basket-analysis
