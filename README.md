# Pipelines_Exercise


For this task, you will use the cereals dataset. This dataset shows popular cereals by brand and manufacturer along with nutrition facts.  The machine learning question is: 

How well can the calories be predicted based on the Manufacturer, cereal type, grams of fat, grams of sugars, and weight in ounces per one serving of the cereal?  

At this point, you are just completing the pre-processing steps for this assignment.

You will need to:

Define features (X) and target (y).
X should only include the Manufacturer, cereal type, grams of fat, grams of sugars, and weight in ounces columns.
Train test split the data to prepare for machine learning.
Identify each feature as numerical, ordinal, or nominal. (Please provide this answer in a text cell in your Colab notebook).
Use pipelines and column transformers to complete the following tasks:
Impute any missing values. Use the ‘mean’ strategy for numeric columns and the ‘most_frequent’ strategy for categorical columns.
One-hot encode the nominal features.
Scale the numeric columns.
All preprocessing steps should be contained within a single preprocessing object.
Use your preprocessing object to transform your data appropriately, avoiding data leakage, to make it ready for modeling. Show the resulting Numpy array.


