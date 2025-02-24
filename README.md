# Delivery Time Prediction 📦  

This is a Streamlit web application that uses a pre-trained Gradient Boosting Regressor (GBR) model to predict delivery times based on various input features such as location details, time information, GPS data, and distance. Simply input the required values, and the app will provide a predicted delivery time along with a summary of the input features.  

## Features  
- User-friendly interface with organized input fields grouped by category.  
- Real-time prediction of delivery times using a pre-trained GBR model.  
- Detailed input feature descriptions for better user understanding.  
- Expandable sections for input features and additional information.  
- Error handling for model loading and prediction processes.  

## Requirements  
- Python 3.x  
- Streamlit  
- scikit-learn  
- numpy  
- pandas  
- joblib  

## Installation  
1. Clone the repository:  
    ```bash
    git clone https://github.com/your-username/delivery-time-predictor.git
    cd delivery-time-predictor
    ```
2. Install the required dependencies:  
    ```bash
    pip install -r requirements.txt
    ```
3. Ensure the pre-trained model file (`best_gbr_model_v1.pkl`) is in the root directory.  

## Usage  
Run the app using the following command:  
```bash
streamlit run app.py
