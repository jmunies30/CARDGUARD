# Card Guard
## Project Repositories

- **Frontend:** [Card Guard Frontend](https://github.com/jmunies30/rapidexplain-frontend)
- **Backend and Model:** [Card Guard Backend](https://github.com/jmunies30/rapidexplain-backend)
## About the Project
RAPIDEXPLAIN is an AI-powered credit card fraud detection project developed for the Veritas AI International High School Hackathon 2026.

Card Guard provides an interactive interface for analyzing transactions and identifying potentially fraudulent activity using a trained machine learning model.

## How It Works

1. A user enters transaction data into the Card Guard interface.
2. The frontend sends the transaction data to the backend.
3. The backend processes the data using the trained machine learning model.
4. The model returns a prediction: **FRAUD** or **NOT FRAUD**.
5. Card Guard displays the prediction to the user.

## Technologies Used

- Python
- Google Colab
- LightGBM
- FastAPI
- Bolt
- GitHub
- Render

## Testing

The application was tested by comparing predictions from the deployed application with predictions from the original Google Colab model using the same transaction data.

## Important Limitations

The model uses anonymized transaction features from its training dataset. Its predictions should be treated as experimental and not as definitive determinations of fraud.

## Project Purpose

The goal of Card Gaurd is to demonstrate how machine learning can help identify potentially fraudulent credit card transactions through an accessible interactive application.
