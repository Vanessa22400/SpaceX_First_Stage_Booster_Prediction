# SpaceX First-Stage Booster Landing Prediction

## Project Overview

This project analyzes SpaceX Falcon 9 rocket launch data to identify the factors that influence the success of first-stage booster landings.

SpaceX significantly reduced launch costs by reusing the first-stage booster, the lower part of the rocket responsible for initial lift-off. Predicting whether this booster will land successfully is crucial for estimating mission costs, evaluating operational risks, and understanding which variables contribute most to landing outcomes.

In this project, I developed an end-to-end Machine Learning workflow using historical SpaceX launch data, covering data collection, exploration, modeling, and interpretation.

---

## Objectives

- Build a predictive model to classify whether the Falcon 9 first-stage booster will land successfully
- Explore and understand the features that influence landing outcomes
- Compare multiple machine learning algorithms (Logistic Regression, SVM, Decision Tree, KNN)
- Optimize model hyperparameters using GridSearchCV
- Evaluate and interpret model performance
  
---

## Project Workflow
The notebook follows a structured data science workflow:

- Data Collection (API requests and web scraping)
- Exploratory Data Analysis (EDA)
- Geospatial visualization with Folium
- Feature preprocessing and scaling
- Machine learning modeling and evaluation
- Interpretation of results and conclusions

---

## Data Source
The datasets used in this project are publicly available and provided by IBM Skills Network as part of the Data Science curriculum.

The data was originally collected via:
- SpaceX REST API
- Web scraping from Wikipedia (Falcon 9 and Falcon Heavy launch history)

For this project, the cleaned and preprocessed datasets are loaded directly via public URLs to ensure reproducibility and simplicity.

---

## Results Summary
- All models achieved a test accuracy of approximately 83%
- Flight number and operational experience were strongly associated with landing success
- Payload mass and launch site also showed relevant patterns
- Model performance should be interpreted carefully due to limited data size

---

## Future Improvements
Possible extensions of this project include:

- Incorporating additional launch data to improve model generalization
- Adding new features such as weather conditions or mission timing
- Evaluating additional metrics beyond accuracy (precision, recall, F1-score)
- Exploring ensemble models such as Random Forests or Gradient Boosting

---

## Project Origin
This project was originally based on an exercise from the IBM Data Science program.  
The notebook was restructured, expanded, and adapted for portfolio purposes, with additional analysis, improved narrative flow, and clearer model interpretation.
