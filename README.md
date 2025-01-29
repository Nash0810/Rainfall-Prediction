# Rainfall Prediction

## Description
This project predicts rainfall using machine learning techniques. It processes historical rainfall data and applies an XGBoost model to make predictions. A web-based interface allows users to input data and receive predictions.

## Features
- Predicts rainfall based on input data
- Uses an XGBoost machine learning model
- Web interface for user-friendly interaction
- Trained on historical rainfall data

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Rainfall-Prediction.git
   cd Rainfall-Prediction-main
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python app.py
   ```

4. Open your browser and go to:
   ```
   http://127.0.0.1:5000
   ```

## Usage
- Enter required weather parameters in the input fields.
- Click the 'Predict Rainfall' button.
- View the prediction results.

## Project Structure
```
Rainfall-Prediction-main/
│── app.py  # Main application script
│── e.py  # Additional script
│── Rainfall.csv  # Dataset used for training/testing
│── xgboost_model.pkl  # Pretrained ML model
│── static/
│   ├── style.css  # Stylesheet for the web app
│── templates/
│   ├── index.html  # Frontend HTML file
```

## Contributing
If you'd like to contribute, feel free to fork the repository and submit a pull request with your changes.

## Contact
For any queries, contact nashco9900@gmail.com or open an issue in the repository.

