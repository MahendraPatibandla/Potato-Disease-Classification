# Potato-Disease-Classification

# Overview:
This project involves the classification of potato diseases using deep learning techniques. The model is trained on the PlantVillage dataset, which includes various images of potato leaves labeled with different diseases. The final application is deployed on Google Cloud Platform (GCP) for real-time predictions.

# Tools & Technologies:
* Deep Learning Framework: TensorFlow for building and training the Convolutional Neural Network (CNN) model.
* Data Augmentation: ImageDataGenerator for enhancing the dataset with augmented images.
* Web Framework: FastAPI for developing the web application interface.
* Deployment: TensorFlow Serving for model deployment, integrated with FastAPI, and hosted on Google Cloud Platform (GCP).
* Dataset: PlantVillage Potato Disease Dataset from Kaggle.
  
# Key Features:
* Disease Classification: Accurate classification of various potato diseases using a CNN model trained on a comprehensive dataset.
* Web Interface: User-friendly web application where users can upload images of potato leaves to receive instant disease classification results.
* Cloud Deployment: Scalable deployment on GCP, ensuring the application is available to users with minimal latency.
  
# How to Run:
* Clone the repository and install the necessary Python packages from requirements.txt.
* Train the CNN model using the provided Jupyter Notebook or use the pre-trained model included in the repository.
* Deploy the model using TensorFlow Serving and integrate it with FastAPI.
* Deploy the entire application on Google Cloud Platform (GCP) using the provided deployment scripts.
* Access the web application via the GCP endpoint to classify potato leaf images.
  
![image](https://github.com/user-attachments/assets/754a4ee8-8ac2-4830-9a45-c9f04a3efca7)
