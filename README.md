# Feature Selection with QuickReduct

## Project Description

This project aims to select the most important attributes in a dataset. Effective selection can enhance the performance of machine learning models by eliminating unnecessary information.

We primarily use the QuickReduct algorithm, which is based on rough set theory. This algorithm identifies relevant features without requiring additional information about the data.

## How It Works

- **Rough Sets**: This method groups similar objects based on their attributes and determines which ones are truly important.
- **QuickReduct**: This algorithm analyzes the attributes and selects those that maintain the same predictive capacity as the initial set.
- **Testing and Visualization**: We apply these algorithms to datasets from the UCI Machine Learning repository and present the results in the form of graphs 📊.

## Why It’s Important

Attribute selection helps simplify models and improve their accuracy, which is crucial in various fields such as finance, healthcare, and marketing.

## Installation

To run this project, you will need:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn fuzzy-rough-learn
