Crop Disease Predictor
Welcome to the Crop Disease Predictor repository! This project utilizes a convolutional neural network (CNN) to accurately predict diseases in potato and tomato crops with an impressive 99% accuracy.

Overview
The Crop Disease Predictor is an advanced machine learning model designed to assist farmers and agricultural experts in identifying diseases in potato and tomato plants. By leveraging the power of convolutional neural networks, the model can analyze images of crop leaves and provide precise predictions about potential diseases, enabling timely intervention and better crop management.

Features
High Accuracy: Achieves 99% accuracy in predicting diseases in potato and tomato crops.
Image-Based Analysis: Analyzes images of crop leaves to determine the presence of diseases.
Multiple Disease Detection: Capable of identifying a variety of diseases affecting potato and tomato plants.
User-Friendly: Easy to use, making it accessible for farmers and agricultural professionals.
How It Works
Image Input: Upload a clear image of a potato or tomato leaf.
Model Prediction: The CNN model processes the image and predicts the disease affecting the crop.
Output: The application provides the predicted disease along with confidence levels.
Installation
To run the Crop Disease Predictor locally, follow these steps:

Clone the Repository:

sh
Copy code
git clone https://github.com/yourusername/crop-disease-predictor.git
cd crop-disease-predictor
Install Dependencies:

sh
Copy code
pip install -r requirements.txt
Download the Pretrained Model:
Download the pretrained model file from this link and place it in the model directory.

Run the Application:

sh
Copy code
streamlit run app.py
Usage
Open the application in your browser.
Upload a photo of a potato or tomato leaf.
Click on the "Predict Disease" button to get the prediction.
View the predicted disease and the confidence level.
Example

Technologies Used
Convolutional Neural Networks (CNN): For building the disease prediction model.
TensorFlow/Keras: For training and deploying the neural network.
Streamlit: For creating the web application interface.
Python: The core programming language used.
Dataset
The model was trained on a dataset containing labeled images of healthy and diseased potato and tomato leaves. The dataset includes a variety of common diseases such as:

Potato: Early Blight, Late Blight, Healthy
Tomato: Bacterial Spot, Early Blight, Late Blight, Leaf Mold, Septoria Leaf Spot, Spider Mites, Target Spot, Yellow Leaf Curl Virus, Mosaic Virus, Healthy
Model Training
The model was trained using convolutional neural networks with several layers, including convolutional layers, pooling layers, and dense layers. It achieved a 99% accuracy rate on the validation set, indicating its effectiveness in real-world scenarios.

Contributing
We welcome contributions from the community! If you'd like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a Pull Request.
