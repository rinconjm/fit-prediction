# CSE 158: Clothing Fit Prediction 
A binary classifier to predict whether a clothing item will fit or not fit a given user.

### Project Overview

This project uses real-world clothing fit datasets from ModCloth and RentTheRunway to build a predictive model.
Given a user–item pair (user measurements + item attributes), the task is to determine:
    **Will this item fit the user?**
    Output: `fit` or `not fit` (binary classification)

This type of model can help reduce returns, improve recommendations, and enhance shopping experiences.

### Datasets

We use the widely-cited Clothing Fit Data collected from ModCloth and RentTheRunway.
These datasets include details such as user measurements, reviews, ratings, and categorical attributes.

**Basic Statistics**
|Dataset|Users|Items|Transactions|
|---|---|---|---|
|ModCloth|47,958|1,378|82,790|
|RentTheRunway|105,508|5,850|192,544|


**Metadata Includes**
- Ratings and reviews
- Fit labels (small / fit / large)
- User body measurements (bust, height, weight, age, etc.)
- Item measurements and attributes
- Category information

### Download Links

ModCloth Dataset:
https://mcauleylab.ucsd.edu/public_datasets/data/modcloth/modcloth_final_data.json.gz

RentTheRunway Dataset:
https://mcauleylab.ucsd.edu/public_datasets/data/renttherunway/renttherunway_final_data.json.gz

If you use this dataset in your work, please cite the following paper:

**Decomposing fit semantics for product size recommendation in metric spaces**
Rishabh Misra, Mengting Wan, Julian McAuley
*RecSys*, 2018