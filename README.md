# Employee Review Predictor

Utilized a Glassdoor employee reviews dataset to create an MLP neural network and a random forest regressor for predicting the star ratings (between 1-5) that an employee would give to their employer. I constructed key features using text and sentiment analysis based on employee reviews to train both models and observed better performance from the random forest model. The `data` folder contains both the training and test data, as well as the predicted ratings.

## Analysis
Based on the reviews and their sentiment scores, it was observed that the worst reviews with low ratings were due to inadequate work-life balance, long working overs, high turnover rates and poor management styles, in comparison to the best reviews which highlighted high pay, flexible working hours, strong work-life balance and great opportunities to learn. Further insights into the reviews can be found inside the `graphs` folder.

## How to Run
1. Clone the repository
2. Run `pip install -r requirements.txt`
3. Unzip the files in the `data` folder (compressed due to size constraints)
4. Run the `main.ipynb` Jupyter notebook
