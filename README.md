# Machine-Learning-Encoding
Encoding is a crucial step in Machine Learning to process data. Especially when to deal with **Categorical** values and in some cases for the sake of **consistency** in data we need encoding.

It's basically converting a non-numeric data into a format that can be used in a **Machine Learning** Algorithms.

Here we used some encoding techniques using python built in ML model and also implement them menually using loop and some basic condition  
- **Replace:** In this encoding method we just simply replaces the categorical values into a numeric form to train the model.
- **Label Encoding:** Assigns a unique integer to each category in a categorical variable. This method is suitable when the categories have a meaningful ordinal relationship (e.g., "low," "medium," "high").  

- **One-Hot Encoding:** Creates binary columns for each category, where a '1' represents the presence of the category and '0' its absence. This is useful for nominal (unordered) categorical data but can lead to high dimensionality in the data.  
- **Ordinal Encoding:** Assigns integer values to categories based on a predefined order or ranking. This method is suitable for ordinal data (e.g., "cold," "warm," "hot").


