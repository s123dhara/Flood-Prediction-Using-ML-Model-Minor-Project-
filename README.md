# Flood Prediction Using ML Model (Random Forest Algorithm)

This project uses a machine learning model based on the Random Forest algorithm to predict floods. The application is a web-based solution where users can interact with the model through a Node.js and Express.js backend. The model's predictions are made by a Python Flask server that processes the data and sends it back to the Node.js server for rendering and display.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This application leverages machine learning to predict floods using a trained Random Forest model. Users interact with the web app by sending a request with input data, which is processed by the Python Flask server where the ML model makes predictions. The results are then rendered on the front-end using EJS templates.

### Workflow:
1. **User Interaction**: The user submits a request through the Node.js web application.
2. **Request Handling**: The request is forwarded to a Python Flask server.
3. **Prediction**: The Flask server processes the request, passes it through the trained Random Forest model, and returns the predicted results.
4. **Display**: The Node.js server receives the prediction and renders it on the web page using EJS templates.

## Features

- **Flood Prediction**: Predicts the likelihood of floods based on the provided data.
- **User-Friendly Interface**: A simple web interface that displays the prediction results to the user.
- **Real-time Processing**: Fast prediction using the Random Forest model.
  
## Technology Stack

- **Backend**: Node.js, Express.js
- **Frontend**: EJS (Embedded JavaScript templates)
- **Machine Learning**: Python, Flask, Random Forest Algorithm (using `scikit-learn`)
- **Deployment**: Local or cloud servers for Node.js and Python Flask
- **Communication**: HTTP requests between Node.js and Flask servers

## Installation

### Prerequisites
Ensure you have the following installed:
- Node.js
- Python 3.x
- pip (Python package installer)
- Dependencies (listed below)

## Dependencies

### Node.js Modules
- **express**: A fast, unopinionated, minimalist web framework for Node.js.
- **ejs**: A simple templating engine for rendering HTML views with embedded JavaScript.
- **path**: Provides utilities for working with file and directory paths.
- **body-parser**: Middleware to parse incoming request bodies.
- **cors**: A package to enable Cross-Origin Resource Sharing.
- **axios**: Promise-based HTTP client for making requests from the browser or Node.js.

### Python Modules
- **scikit-learn**: A Python module for machine learning, providing simple and efficient tools for data mining and data analysis.
- **pickle5**: A backport of the `pickle` module used for serializing and deserializing Python objects, particularly the trained machine learning model.
- **flask**: A lightweight WSGI web application framework in Python.
- **dotenv**: A module to load environment variables from a `.env` file.
- **os**: A Python module for interacting with the operating system, such as file and directory handling.
- **pandas**: A fast, powerful, flexible, and easy-to-use open-source data analysis and manipulation tool.



### Clone the repository
```bash
git clone git@github.com:s123dhara/Flood-Prediction-Using-ML-Model-Minor-Project-.git
cd Flood Prediction Using ML Model Minor Project

```
## Images
 ![Home 1](https://github.com/user-attachments/assets/f37445b5-1b82-45e4-938e-637b5d22d072)

 ![Home 2](https://github.com/user-attachments/assets/6c9cfff5-8ec0-4e5d-b0fb-56e58b951e1e)

 ![Home 3](https://github.com/user-attachments/assets/de20eef4-69c9-4c63-8edb-145dbda36796)

 ![Prediction Form page 1](https://github.com/user-attachments/assets/f4a882b1-b672-4f66-bcf4-d13228647bdb)

 ![Prediction Form Page 2](https://github.com/user-attachments/assets/e39cd500-b113-4f90-b4ac-aea8d3d31f68)
 
 ![Prediction Form Page 3](https://github.com/user-attachments/assets/455213dc-afd1-43e5-a06e-272335f4ddba)

 ![Blog Page](https://github.com/user-attachments/assets/b4e4cf16-6685-4994-a847-f3fe71c28b58)

  ![About Page](https://github.com/user-attachments/assets/b99f4e57-57cb-44fd-94d3-e282307f1e34)







