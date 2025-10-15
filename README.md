# AI For Grid Collapse Prediction

This project was carried out under the Deep Learning Indaba Community Challenge 2025.

it is fovused on using artificial intelligence and machine learning to build a system that preducts the probability of grid collapse at certain times based on historical data.

## Data Generation

The data used in this project was generated synthetically as actual data could not be generated due to the mode of record and time span.

## Methodology

The generted data was thoroughly cleaned and prepared forodel training. It was also subsectioned into parts like daily, hourly data.

Unsupervised learning- clustering was first employed for 5he project making use of principal component analysis.
But it produced low accuracy.

To resolve this, the "AutoGluon" model was applied to be trained on the data by employing several models under the AutoML and ranking the one that produced the best score and accuracy.
The model that performed best for the project was the Extra Trees Classifier.


## Tools

Python|AutoGluon|
