🌽 Corn Leaf Disease Detection using Vision Transformers

This project uses a Vision Transformer (ViT) model to detect and classify diseases in corn plant leaves from images. The model learns visual patterns such as discoloration, spots, and texture changes to identify whether a leaf is healthy or diseased.

A Streamlit web application is built on top of the trained model, allowing users to upload a corn leaf image and get instant predictions. This project helps in early disease detection, improving crop health and reducing agricultural losses.

🚀 Technologies Used

Python

TensorFlow / Keras

Vision Transformer (ViT)

Streamlit

Google Colab

⚙️ How to Run

Clone the repository

Install required dependencies

Run the Streamlit app

Upload a corn leaf image to get predictions
Project structure
Corn-Leaf-Disease-Detection/
│
├── dataset/
│   ├── train/
│   ├── test/
│
├── model/
│   └── vit_model.h5
│
├── app.py              # Streamlit application
├── train_model.ipynb   # Model training notebook
├── requirements.txt    # Required libraries
└── README.md

