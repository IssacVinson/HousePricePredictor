1. This step imports all the libraries we need to work with data, build a machine learning model, and evaluate it — we chose these tools because they’re widely used and beginner-friendly.

2. This step loads the housing data from a CSV file into a pandas DataFrame — we use pandas because it makes handling tables of data really easy.

3. This step shows the first few rows of the dataset — we do this to quickly check what kind of data we’re working with and make sure it loaded correctly.

4. This step selects the most important columns (bedrooms, bathrooms, square footage, garage spaces, and year built) — we chose these because they are commonly used to estimate house prices.

5. This step separates the data into features (X) and the target value (y), which is the house price — we do this so the model can learn how the features relate to the price.

6. This step splits the data into a training set and a test set — we do this to train the model on one part of the data and test it on a different part to see how well it learned.

7. This step builds a pipeline that first scales the feature values — we do this because the numbers (like square feet and year) are on very different scales, and scaling helps the model treat them fairly.

8. This step adds a Random Forest Regressor to the pipeline — we chose Random Forest because it’s more accurate and flexible than simpler models like linear regression.

9. This step trains the model using the training data — we do this so the model can learn patterns between house features and their prices.

10. This step uses the model to predict prices for the test data and calculates the root mean squared error (RMSE) — we use RMSE to measure how far off the model’s guesses are from the actual prices.

11. This step defines a function to predict house prices based on new input like number of beds or size — we created it so users can test different house setups easily.

12. This step runs the prediction function with an example input — we included this so we could immediately see how the model performs on a custom example.

