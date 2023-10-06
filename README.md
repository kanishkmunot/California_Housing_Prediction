# California Housing Prediction

## Introduction

This project is a Python-based web application that predicts housing prices in California based on various input features. It uses a machine learning model, specifically a linear regression model, trained on California housing data. Users can input different features related to a house, and the application will provide an estimated house price.

The project demonstrates how to build a simple web application using Flask, create a machine learning model with scikit-learn, and deploy it using platforms like Heroku.

![Alt text]([california_housing_pred.png](https://github.com/kanishkmunot/California_Housing_Prediction/blob/main/california_housing_pred.png))

## Software and Tools Required

Before running or deploying the application, ensure you have the following software and tools installed:

1. [Github Account](https://github.com)
   - Used for version control and collaboration.

2. [VS Code IDE](https://code.visualstudio.com/)
   - A code editor for developing and modifying Python code.

## Setting Up the Development Environment

To create a new Python environment, you can use Conda:

```bash
conda create -p venv python==3.7 -y
```

This command creates a virtual environment named "venv" with Python 3.7.

## Running the Application Locally

To run the application on your local machine, follow these steps:

1. Clone the GitHub repository:

   ```bash
   git clone https://github.com/kanishkmunot/California_Housing_Prediction.git
   ```

2. Change your current directory to the project folder:

   ```bash
   cd California_Housing_Prediction
   ```

3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Start the Flask application:

   ```bash
   python app.py
   ```

5. Open a web browser and go to `http://127.0.0.1:5000/` to access the application.

## Usage

Once the application is running, you can use it to predict housing prices in California. Input various features related to a house, and the application will provide an estimated house price.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
