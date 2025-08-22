Pneumonia Detection from Chest X-ray Images
<img width="1318" height="789" alt="image" src="https://github.com/user-attachments/assets/37137b16-584f-4b17-b750-be567b3d513a" />

A deep learning-powered web application to detect pneumonia from chest X-ray images. This tool provides a fast, accessible way to leverage AI for medical image analysis, classifying images as either "Normal" or "Pneumonia".

<!--
IMPORTANT: Add a screenshot or a GIF of your application here!
It makes a huge difference. You can drag and drop the image into the README editor on GitHub.
-->

Caption: A quick look at the user interface.

📋 Table of Contents
Features

How It Works

Tech Stack

Local Setup

Dataset

More Projects

License

✨ Features
Image Upload: Simple and intuitive interface to upload chest X-ray images (.jpeg, .png).

AI-Powered Prediction: Utilizes a trained Convolutional Neural Network (CNN) model to analyze the uploaded image.

Instant Results: Delivers a clear prediction ("Normal" or "Pneumonia") in seconds.

Responsive Design: Fully functional on both desktop and mobile devices.

🧠 How It Works
The application follows a simple workflow:

The user uploads a chest X-ray image through the web interface.

The image is pre-processed to match the input requirements of the deep learning model (e.g., resizing, normalization).

The pre-processed image is passed to the pre-trained CNN model for inference.

The model outputs a prediction, which is then displayed back to the user on the results page.

🛠️ Tech Stack
Backend: Python, Flask

Deep Learning: TensorFlow, Keras

Frontend: HTML, CSS, JavaScript

Deployment: Render

🚀 Local Setup
To run this project on your local machine, follow these steps:

Clone the repository:

git clone https://github.com/amanchauhan786/pneumonia-project.git
cd pneumonia-project

Create and activate a virtual environment:

# For Windows
python -m venv venv
.\venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate

Install the required dependencies:

pip install -r requirements.txt

(Note: If a requirements.txt file is not present, you may need to create one by running pip freeze > requirements.txt after installing the necessary libraries like Flask, TensorFlow, etc.)

Run the application:

python app.py

Open your web browser and navigate to http://127.0.0.1:5000.

📊 Dataset
This model was trained on the Chest X-Ray Images (Pneumonia) dataset available on Kaggle. It contains thousands of pre-labeled chest X-ray images, categorized into Pneumonia and Normal classes.

Link to the dataset on Kaggle

🌐 More Projects
Check out some of my other deployed applications:

LegalKH: [Live Demo](https://legalkh.onrender.com/)

Dicmicro: [Live Demo](https://dicmicro.onrender.com/)

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
(Note: You'll need to create a file named LICENSE in your repository and add the MIT License text to it for this link to work.)

