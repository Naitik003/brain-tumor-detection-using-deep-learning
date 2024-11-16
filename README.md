Brain Tumor Detection using Deep Learning
This project aims to build a deep learning model for detecting brain tumors from MRI scan images. The goal is to develop a Convolutional Neural Network (CNN) model that can accurately classify brain images as tumor or non-tumor, and further deploy it as a web application using Flask.

🧠 Project Workflow
1. Data Preparation
The dataset of brain MRI scans is sourced from Kaggle.
It includes images labeled as tumor and no tumor.
2. Exploratory Data Analysis (EDA)
Perform analysis to understand data distribution, image characteristics, and class imbalance.
3. Data Augmentation
Address the class imbalance issue using augmentation techniques.
Augmentations include rotation, flipping, and zooming to generate more diverse training data.
4. Data Preprocessing
Utilize OpenCV for preprocessing tasks such as resizing, normalization, and grayscale conversion.
5. Data Splitting
Split the dataset into three parts: training, validation, and testing sets to ensure robust model evaluation.
6. Model Building
Build a Convolutional Neural Network (CNN) model for image classification.
The architecture includes convolutional layers, pooling layers, and dense layers to extract features and make predictions.
7. Model Fine-Tuning
Apply techniques like unfreezing layers and adjusting learning rates to improve the model's accuracy.
8. Flask Application
Develop a Flask-based web application to provide a user-friendly interface for uploading MRI scans and getting predictions.
🛠️ Tech Stack
Python: Core programming language used for data processing and model building.
OpenCV: For image preprocessing and transformations.
TensorFlow / Keras: For building and training the CNN model.
Flask: Backend framework for developing the web application.
Jupyter Notebook: For exploratory data analysis and iterative model building.
Pandas & NumPy: For data manipulation and numerical computations.
Matplotlib & Seaborn: For visualizing data insights and model performance.
🚀 Getting Started
Prerequisites
Python 3.x
Required libraries can be installed using:
Copy code
pip install -r requirements.txt
Running the Application
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/Brain-Tumor-Detection.git
Navigate to the project directory:
bash
Copy code
cd Brain-Tumor-Detection
Start the Flask application:
Copy code
python app.py
Open a browser and go to http://127.0.0.1:5000 to access the web app.
