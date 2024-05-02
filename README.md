This project aims to predict laptop prices using machine learning techniques. We have developed a complete machine learning pipeline to achieve this goal. Through extensive exploratory data analysis (EDA) and preprocessing, we gained insights into the relationship between laptop prices and various features. It was observed that SSD and RAM had the most significant influence on price increases.

Dataset
The dataset used in this project contains a limited number of instances but provides sufficient information for our analysis and prediction. It includes various features such as processor type, RAM size, storage type, screen size, etc., along with the corresponding laptop prices.

Methodology
Exploratory Data Analysis (EDA): We conducted EDA to understand the distribution of features, identify correlations, and uncover insights into the dataset.
Preprocessing: Preprocessing steps included handling missing values, encoding categorical variables, scaling numerical features, and splitting the data into training and testing sets.
Model Selection: We experimented with various machine learning algorithms, but ultimately, a random forest model was chosen due to its robustness and performance.
Model Training: The selected model was trained on the training data to learn the patterns and relationships between features and laptop prices.
Model Evaluation: The model's performance was evaluated using appropriate metrics, with a focus on R2 score to assess the variance explained by the model.
Prediction: Finally, the trained model was used to predict laptop prices on unseen data.
Results
Using the random forest model, we achieved an impressive R2 score of approximately 85%. This performance exceeded our expectations, considering the limitations of the dataset. It demonstrates the effectiveness of our approach in predicting laptop prices based on the available features.


Future Work
While achieving a high R2 score is promising, there are still opportunities for improvement and further exploration:

Feature Engineering: Experiment with creating new features or transforming existing ones to potentially improve model performance.
Hyperparameter Tuning: 
