# OpenFoodFacts_Analysis

This project relies on a source dataset that can be found [here](https://world.openfoodfacts.org/data).
You simply have to upload it to the 

To use this repo's notebooks, you can download the CSV dataset from the above link namely 'en.openfoodfacts.org.products.csv' and place it in the [Data directory](data/).

# Notebooks 
1. [reduce_data](reduce_data.ipynb)</br>
This notebook takes the original dataset as input. It transforms it to a smaller dataset by filtering out the unecessary columns.

2. [process_data](process_data.ipynb)</br>
This notebook is dedicated to the pre processing of the data.

3. [analyze_data](analyze_data.ipynb)</br>
This final notebook is dedicated to the computing and interpretation of the different products' embeddings.</br>
In the last cell, you will be able to input any product name (that exists in the database) to find its most similar ones.