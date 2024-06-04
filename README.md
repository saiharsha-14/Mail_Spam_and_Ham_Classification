
# Email Spam Classification

This project aims to classify emails as spam or ham (not spam) using a machine learning model. It provides a web interface where users can input email text and get a prediction.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/saiharsha-14/Mail_Spam_and_Ham_Classification.git
   cd Mail_Spam_and_Ham_Classification
   ```

2. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

4. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Flask application:

   ```bash
   python app.py
   ```

2. Open your web browser and go to `http://127.0.0.1:5000`.

3. Enter the email text in the provided textarea and click "Analyze" to see if the email is classified as spam or ham.

## Project Structure

```plaintext
Email_Spam_Classification/
│
├── templates/
│   └── index.html       # HTML file for the web interface
│
├── app.py               # Flask application file
│
├── model/
│   ├── feature_extraction.pkl  # Pre-trained feature extraction model
│   ├── logistic_regression.pkl # Pre-trained logistic regression model
│
├── Email Spam Classification Using Python.ipynb  # Jupyter notebook for training the model
│
├── mail_data.csv        # Dataset used for training
│
├── requirements.txt     # Python dependencies
│
└── README.md            # Project readme file
```