# House-price-prediction-using-machine-learning-
Creating a chatbot for house price prediction using machine learning involves the following steps:

1. Define the purpose and scope of your chatbot: Determine the specific goal of your chatbot, which is to predict house prices. Identify the scope of the chatbot, such as whether it will focus on a specific location or type of property.

2. Collect and preprocess training data: Gather a dataset of historical house sales data that includes relevant features such as location, size, number of rooms, amenities, and sale prices. Preprocess the data by cleaning, normalizing, and formatting it. This may involve handling missing values, removing outliers, and encoding categorical variables.

3. Choose a machine learning model: Select a suitable machine learning model for house price prediction. Regression models like linear regression, decision trees, or ensemble methods (e.g., random forest) are commonly used for this task. Consider factors like model performance, interpretability, and scalability when choosing the model.

4. Split the data into training and testing sets: Divide your dataset into two parts: a training set and a testing set. The training set will be used to train the machine learning model, while the testing set will be used to evaluate its performance.

5. Train the model: Use the training set to train the chosen machine learning model. Feed the model with the input features (e.g., location, size) and corresponding target variable (i.e., house prices). Adjust the model's parameters to minimize the difference between predicted prices and actual prices.

6. Evaluate and fine-tune the model: Assess the performance of your trained model by evaluating its accuracy and other metrics on the testing set. Use techniques like cross-validation or grid search to fine-tune hyperparameters and improve the model's performance. This may involve adjusting regularization parameters, changing feature representations, or trying different algorithms.

7. Deploy the chatbot: Once you are satisfied with the trained model's performance, deploy it to a server or platform where it can interact with users. Build a chatbot interface that takes input features from users (e.g., location, size) and uses the trained model to predict house prices. Ensure that the deployment environment is scalable and provides a seamless user experience.

8. Continuously improve and update the chatbot: Monitor the predictions made by the chatbot and collect feedback from users. Regularly update your training data to include new house sales data and retrain the model to improve its accuracy. Consider incorporating user feedback into the training process to make the chatbot more accurate over time. Stay updated with advancements in machine learning techniques and incorporate them into your model if necessary.

Remember, developing a chatbot for house price prediction using machine learning requires ongoing monitoring, evaluation, and refinement to ensure accurate predictions and user satisfaction.The dataset contains 20640 entries and 10 variables.
*	Longitude
*	Latitude
*	Housing Median Age
*	Total Rooms
*	Total Bedrooms
*	Population
*	Households
*	Median Income
*	Median House Value
*	Ocean Proximity

**Median House Value is** to be predicted in this problem.

I have done this project in two parts. First part contains data analysis and cleaning as explained in **EDA and data cleaning.ipynb**. Second is training of machine learning models explained in **Training Machine Learning Algorithms.ipynb**.

## 1) EDA and Data Cleaning
I have done the exploratory data analysis and done following manipulations on data.
*	Creating new features
*	Removing outliers
*	Transforming skewed features
*	Checking for multicoliniearity

## 2) Training machine learning algorithms:
Here, I have trained various machine learning algorithms like
*	Linear Regression
*	Ridge Regression
*	Support Vector Regression
*	Gradient Boosting Regression
*	Stacking of various models
