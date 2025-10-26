# GreenerCities_Tree_Planting_Prediction
This project goes beyond my imagination, applying my knowledge in machine learning to address environmental challenges and contribute to reducing pollution and creating a healthier living environment.

Greener Cities with AI: Tree Planting Prediction 🌳🌴🌲🍃🥬🌿

Overview

This project predicts the optimal locations, number of trees, and planting distance in urban areas to reduce pollution and improve air quality. Using environmental data like PM2.5 levels, population density, traffic density, temperature, and area availability, the system recommends the type and number of trees suitable for each location.

Objective

Minimize air pollution in cities by planting trees strategically.

Maximize green cover efficiently within available urban space.

Provide actionable insights for city planners and environmental organizations.

Dataset

The dataset contains the following features:

pm2_5 – Air pollution levels

tree_cover – Existing green cover

population_density – People per unit area

traffic_density – Vehicle density

near_road – Proximity to roads

temperature – Ambient temperature

area_in_sqft – Available area for planting

planting_distance_km – Distance between trees (target)

tree_type – Suitable tree species (target)

number_of_trees – Optimal number of trees (target)

Methodology

Data Preprocessing

Handled missing values and cleaned data.

Encoded categorical features like tree_type.

Scaled numerical features for better model performance.

Model Selection & Training

Regression Models for continuous targets:

Predict planting distance and number of trees.

Classification Model for categorical target:

Predict tree type suitable for a location.

Models used:

Linear Regression / Decision Tree Regressor – Planting distance & number of trees

Random Forest / Logistic Regression / SVM – Tree type prediction

Evaluation

Regression: R² score, Mean Absolute Error (MAE)

Classification: Accuracy score, Confusion Matrix

Models were saved using Joblib for deployment.

Prediction

Input: Environmental features for a location.

Output: Recommended tree type, number of trees, and planting distance.

Can be integrated with a web app for real-time decision making.

Technologies Used

Python – Programming language

Pandas, NumPy – Data handling

Scikit-learn – Machine learning models

Matplotlib, Seaborn – Visualization

Joblib – Saving trained models

Jupyter Notebook / Google Colab – Development environment

Results

Optimal tree type, number, and planting distance predicted based on environmental conditions.

Helps urban planners make decisions to reduce pollution and maximize green cover.

Can be scaled to multiple cities with similar datasets.
