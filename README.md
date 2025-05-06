# Final_Year_Project_A3
Materials for Final year project assessment 3

Final_Year_Project_2.ipynb
- This Jupyter notebook was used for data analysis, model training, and evaluation. It helped compare different machine learning models and select the final ensemble.

model.py
- This script trains the final ensemble model (Voting Classifier) and saves it using pickle. It prepares the model for use in the web application.

model.pkl
- This is the saved (serialized) version of the trained model. It is loaded by the Flask app to make predictions without retraining.

app.py
- This is the backend Flask application that connects the model to the web interface. It processes user inputs and returns fraud predictions.

index.html
- This HTML file provides the user interface for inputting transaction data. It displays prediction results by communicating with the Flask backend.
