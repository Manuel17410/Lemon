# Lemon Leaf Disease Classification: A CNN Powered Web App in Docker

The Lemon Leaf Disease Classification App is an innovative web application powered by a Convolutional Neural Network (CNN), deployed via Docker. This app enables users to upload an image of a lemon leaf and receive a classification of the leaf into one of the following categories:
* Anthracnose
* Bacterial Blight
* Citrus Canker
* Curl Virus
* Deficiency Leaf
* Dry Leaf
* Healthy Leaf
* Sooty Mould
* Spider Mites

With an accuracy rate of 96.8%, the app utilizes deep learning to analyze leaf images, providing quick and accurate disease identification.

Dataset used: https://www.kaggle.com/datasets/mahmoudshaheen1134/lemon-leaf-disease-dataset-lldd

## Benefits of the App

This tool provides a valuable service to the agriculture sector by:

* Enabling Early Disease Detection: Early identification of plant diseases allows for timely intervention, reducing the spread of harmful conditions and saving crops.
* Improving Crop Management: Farmers and researchers can take proactive measures to treat or manage diseases, contributing to healthier plants and improved yields.

 ## Video Demonstration of the App on YouTube

To give you a quick overview of how the app works, I’ve created a demonstration video. While setting up the app locally can take a few minutes and sometimes lead to dependency issues, this video allows you to experience the website without any setup.

[![Watch the Demo](https://img.youtube.com/vi/UfOb0P7XKpI/0.jpg)](https://www.youtube.com/watch?v=UfOb0P7XKpI)

Additionally, I am actively working on hosting the app on a cloud platform to make it even easier to access. 

## How to run the website:

1. Clone the Repository
   
git clone https://github.com/Manuel17410/Lemon-Leaf-Disease-Classification-A-CNN-Powered-WebApp-in-Docker

cd Lemon

2. Install Requirements

Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Then install dependencies:
pip install -r requirements.txt

3. Set Up Git LFS

This project uses Git LFS for large files like the trained model:

git lfs install
git lfs pull

This will download the model.keras file.

4. Run the App

Make sure you are in the project folder, then:

python server.py

The app will open in your browser where you can upload a leaf image and get predictions.
