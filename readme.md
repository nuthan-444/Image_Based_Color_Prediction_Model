<h1>🎨 Color Prediction Using Images</h1>

<h2>📌 Description</h2>
<p>
This project is a Machine Learning-based system that predicts the dominant color of an image using pixel-level features. The model is trained using a Random Forest classifier on labeled image data and is capable of classifying new unseen images into predefined color categories.
</p>

<p><b>Model Accuracy:</b> 0.75 (75%)</p>

<h2>🛠️ Tools and Technologies Used</h2>
<ul>
    <li>Python</li>
    <li>OpenCV (cv2)</li>
    <li>NumPy</li>
    <li>Scikit-learn</li>
</ul>

<h2>📊 Dataset</h2>
<p>
Dataset contains images organized into color folders (red, blue, green, etc.).
Images are resized to 64x64 and flattened into feature vectors.
</p>

<p>
<b>Dataset Link:</b>
<a href="https://www.kaggle.com/datasets/ayanzadeh93/color-classification">
Kaggle Dataset
</a>
</p>

<h2>📁 Folder Structure</h2>
<pre>
ColorPredictionProject/
├── ColorClassification/
│   ├── Red/
│   ├── Blue/
│   └── ...
├── For_Testing/
│   └── 85.jpg
├── model.ipynb
├── ColorClassifier.pkl
└── README.md
</pre>

<h2>📈 Model Performance</h2>
<ul>
    <li>Algorithm: Random Forest</li>
    <li>Accuracy: 0.75</li>
    <li>Train-Test Split: 80-20</li>
    <li>Features: 64x64x3 flattened pixels</li>
</ul>