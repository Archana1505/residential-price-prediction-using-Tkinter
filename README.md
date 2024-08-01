# residential-price-prediction-using-Tkinter
The House Price Prediction project aims to develop a machine learning model that predicts the price of a house based on various features such as area, number of bedrooms (BHK), number of bathrooms, furnishing status, locality, parking availability, property status, transaction type, property type, and price per square foot. The project involves data preprocessing, model training, and building a graphical user interface (GUI) to make predictions easily accessible.
Objectives
Data Collection: Collect and prepare a dataset containing relevant features and target variables (house prices).

Data Preprocessing: Clean and preprocess the data, including handling missing values, encoding categorical features, and normalizing numerical features.

Model Training: Train a machine learning model to accurately predict house prices based on input features.

Model Evaluation: Evaluate the model's performance using metrics.

GUI Development: Develop a user-friendly GUI using Tkinter that allows users to input features and obtain house price predictions.
Data Description

The dataset used in this project consists of various features that influence house prices. Key columns include:

Area: The total area of the house in square feet.
BHK: The number of bedrooms.
Bathroom: The number of bathrooms.
Furnishing: The furnishing status of the property (e.g., furnished, semi-furnished, unfurnished).
Locality: The location of the property.
Parking: The availability of parking space.
Status: The current status of the property (e.g., ready to move, under construction).
Transaction: The type of transaction (e.g., new, resale).
Type: The type of property (e.g., apartment, villa).
Per_Sqft: The price per square foot.
Machine Learning Model
Model Selection: A Linear Regression model was chosen for its simplicity and interpretability.
Feature Engineering: Categorical features were encoded using one-hot encoding, and numerical features were normalized.
Training and Testing: The dataset was split into training and testing sets to evaluate the model's performance. The model was trained using the training set and evaluated on the testing set.
Graphical User Interface (GUI)
Technology: Tkinter, a standard Python library for creating GUI applications.
Features: The GUI allows users to:
Select or input values for various features (Area, BHK, Bathroom, etc.) using dropdown menus and entry fields.
Click a "Predict" button to generate a house price prediction based on the input features.
Display the predicted price on the interface.
Implementation Details
Data Loading: The data is loaded from an Excel file using Pandas.
Model Saving and Loading: The trained model is saved as a .pkl file using pickle, allowing for easy loading and use in the GUI.
Prediction: The GUI collects user input, formats it appropriately, and uses the loaded model to predict the house price, which is then displayed to the user.
Conclusion
The House Price Prediction project provides a practical application of machine learning in the real estate domain. By leveraging data analysis and machine learning techniques, the project offers valuable insights into property pricing and facilitates informed decision-making for potential buyers and sellers. The user-friendly GUI ensures accessibility and ease of use, making the tool valuable for a wide range of users, including real estate agents, investors, and homebuyers.

Future Work
Future enhancements could include:

Incorporating Additional Features: Adding more features like neighborhood amenities, proximity to schools, and market trends.
Model Improvements: Exploring advanced models like Gradient Boosting, Random Forest, or Neural Networks for better accuracy.
Deployment: Deploying the application as a web or mobile app for broader accessibility.
