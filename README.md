
# Property-price-Predication

This challenge asks us to predict the sale price of houses in Ames, Iowa, based on a set of information provided, such as size, neighborhood, condition, etc.

A real estate agent might be able to do this based on intuition and experience, but a computer – lacking this ability and knowledge – might just accomplish the same. This dataset was compiled by Dean De Cock for use in data science education.


# The Data:

81 Columns, each describing a feature of the property like building type, size, no. of fireplaces, neighborhood etc.
1460 entries, each corresponding to a house.

# Data Preprocessing:
The data was not suitable for training, to tackle that, I did the following:

1-Drop the attributes with a majority of null values.

2-Fill out the missing values with mean (for integers) and mode(for categorical attributes).

3-Encode the categorical attributes into leabel encoding.

4-Scale all the numeric values between zero and one.

5-Split the Data into train set and validation set, then split them into batches.
