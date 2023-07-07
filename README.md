# Heart Disease Prediction

## Introduction: 
The Heart Disease Prediction System is a machine learning-based solution that aims to predict the risk of heart disease for individuals. The system utilizes Azure Machine Learning with AutoML for model training and deployment, and integrates with Power BI for dynamic visualization of the predictions. This documentation provides an overview of the project, its components, and the steps to deploy and use the system effectively.
Problem Statement: 
Heart disease is a significant health concern globally, and accurate prediction of its risk is crucial for early detection and prevention. The challenge lies in developing a reliable prediction model that can analyze various medical indicators and provide accurate predictions.
## Solution Overview: 
The Heart Disease Prediction System leverages Azure Machine Learning with AutoML to automate the process of model selection, feature engineering, and hyperparameter tuning. The system follows these key steps:<br>
a. Data Preparation: Collect and clean relevant datasets that include features such as age, gender, blood pressure, cholesterol levels, and other medical indicators associated with heart disease. Ensure that the data is properly formatted and suitable for training the machine learning model. <br>
b. Azure Machine Learning Studio: Set up an Azure Machine Learning Studio workspace to create, train, and deploy machine learning models. This environment provides a rich set of tools and resources for building robust predictive models. <br>
c. AutoML Configuration: Configure AutoML in Azure Machine Learning Studio to automatically select the best model and hyperparameters for heart disease prediction. Specify the target variable, feature types, and any constraints or preferences. <br>
d. Model Training: Launch the AutoML experiment to train and evaluate multiple models using different algorithms and settings. AutoML will handle feature engineering, model selection, and hyperparameter tuning to find the most accurate model. <br>
e. Model Evaluation: Evaluate the performance of the trained models using appropriate metrics such as accuracy, precision, recall, or F1-score. Choose the best-performing model for deployment. <br>
g. Power BI Integration: Connect Power BI to the deployed model's API endpoint to fetch real-time predictions. Power BI offers seamless integration with Azure Machine Learning services. <br>
h. Dynamic Visualization: Utilize Power BI's interactive data visualization capabilities to create dynamic charts, graphs, and dashboards. Visualize historical data, compare predictions with actual outcomes, and track heart disease risk factors over time. <br>


## Purpose and Benefits: 
The Heart Disease Prediction System addresses the need for accurate heart disease risk prediction and provides dynamic visualizations for enhanced understanding and decision-making. The system offers the following benefits: <br>
* Accurate Predictions: The system leverages machine learning algorithms and automated model selection to provide accurate predictions of heart disease risk. <br>
* Real-Time Insights: Integration with Power BI allows for real-time fetching of predictions, enabling healthcare professionals to monitor and analyze heart disease risk dynamically. <br>
* Visual Representation: Power BI's data visualization capabilities enable the creation of interactive charts, graphs, and dashboards that provide visual representations of heart disease risk factors. <br>
* Informed Decision-Making: The system empowers healthcare professionals and stakeholders to make informed decisions based on real-time insights and visual representations of heart disease risk. <br>

* To have a look at the interactive dashboard: https://drive.google.com/file/d/1mknGQjDbh3Hfwq19rRUeAyhMeRY7p8GY/view?usp=sharing

