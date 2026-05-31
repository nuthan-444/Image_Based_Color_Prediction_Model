🎨 Color Prediction Using Images
📌 Description

This project is a Machine Learning-based system that predicts the dominant color of an image using pixel-level features. The model is trained using a Random Forest classifier on labeled image data and is capable of classifying new unseen images into predefined color categories.

Model Accuracy: 0.75 (75%)

🛠️ Tools and Technologies Used
Python 🐍
OpenCV (cv2)
NumPy
Scikit-learn
📊 Dataset

The dataset consists of images organized into folders based on their respective color labels. Each folder represents a specific color class such as red, blue, green, yellow, etc.

Images are resized to 64x64 pixels
Converted into numerical pixel arrays (flattened)
Used as input features for model training

📥 Dataset Source (Kaggle):
https://www.kaggle.com/datasets/ayanzadeh93/color-classification


📁 Folder Structure
ColorPredictionProject/
│
├── ColorClassification/        # Training dataset (color folders)
│   ├── Red/
│   ├── Blue/
│   ├── Green/
│   └── ...
│
├── For_Testing/                # Test images for prediction
│   └── 85.jpg
│
├── model.ipynb                    # Model training and prediction code
├── ColorClassifier.pkl         # Saved trained model
└── README.md                   # Project documentation
📈 Model Performance
Algorithm: Random Forest Classifier
Accuracy: 0.75 (75%)
Train-Test Split: 80-20
Features: Flattened image pixels (64 × 64 × 3 = 12288)