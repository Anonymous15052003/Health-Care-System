# Disease Predictor

This project is a simple disease prediction tool that uses machine learning algorithms to predict potential diseases based on given symptoms. It uses a graphical user interface (GUI) built with Tkinter, allowing users to enter symptoms and predict the disease using three different models: Decision Tree, Random Forest, and Naive Bayes.

## Project Overview

The tool is designed to help users quickly identify a possible disease based on selected symptoms. The following are the primary components of this project:

- **Symptom Selection:** Users can select up to five symptoms from a predefined list.
- **Machine Learning Models:** The project includes three models: Decision Tree, Random Forest, and Naive Bayes.
- **GUI:** The GUI allows users to interact with the system, input their symptoms, and view the predicted result.

## Installation

To run this project on your local machine, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/disease-predictor.git
   cd disease-predictor
2. Set Up a Virtual Environment (Optional but Recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
3. Install Dependencies:
   ```bash
   pip install -r requirements.txt

## Usage
To run the application:

1. Start the Tkinter GUI:
   ```bash
   python disease_predictor.py
2. Enter Your Information:
- Fill in your name.
- Select up to five symptoms from the drop-down menus.

3. Predict the Disease:
- Click on the "Result 1" button for the Decision Tree prediction.
- Click on the "Result 2" button for the Random Forest prediction.
- Click on the "Result 3" button for the Naive Bayes prediction.

4. View the Results:
- The predicted disease will be displayed in the corresponding result box.

## Model Accuracy
During training, the models achieved the following accuracy scores:

- Decision Tree: 95.1%
