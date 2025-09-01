🌱 AI-Powered Plant Disease Detection
📌 Project Overview

This project was developed as part of my Edunet Foundation Internship (AICTE) under the theme Sustainable Agriculture.
The aim is to build an AI-powered system that detects plant diseases from leaf images using computer vision techniques. By enabling early detection, farmers can minimize crop loss, reduce excessive pesticide use, and adopt sustainable farming practices.

🎯 Objectives

- Apply Artificial Intelligence (AI) in agriculture for disease identification
- Train a deep learning model using plant leaf images
- Provide a simple tool (Colab/Streamlit) for users to upload an image and receive predictions
- Promote sustainability by reducing waste, cost, and chemical overuse

📂 Dataset

Source: Kaggle – New Plant Diseases Dataset

Size: ~3 GB

Classes: Multiple crop species (healthy + diseased leaves)

Preprocessing: Resizing, normalization, and data augmentation for robustness.

⚙️ Tech Stack

Programming Language: Python 🐍

Libraries/Frameworks: TensorFlow, Keras, NumPy, OpenCV, scikit-learn, Matplotlib

Platform: Google Colab (training & experimentation)

Deployment (Optional): Streamlit / Flask for interactive demo

🛠️ Workflow

Data Preprocessing

Load dataset from Kaggle/Drive

Resize & normalize images

Augmentation (rotation, flip, zoom)

Model Development

Transfer Learning (MobileNet, ResNet, EfficientNet)

Training & Validation

Save trained model

Evaluation

Accuracy, Precision, Recall, F1-score

Confusion matrix & visualization

Deployment (Optional)

Build a simple interface (Streamlit)

Upload leaf image → get disease prediction

📊 Results (Expected)

Classification Accuracy: ~90%+ (depending on model & training)

Ability to distinguish between healthy vs diseased leaves

Practical tool for agriculture and sustainability research

🚀 How to Run

Clone this repository:

git clone https://github.com/your-username/plant-disease-detection.git
cd plant-disease-detection


Install dependencies:

pip install -r requirements.txt


Open and run the Jupyter Notebook in Google Colab:

Upload dataset (or download via Kaggle API)

Train the model

(Optional) Run the web app:

streamlit run app.py

🌍 Sustainable Agriculture Impact

Early detection reduces major crop losses.

Minimizes pesticide use, leading to eco-friendly farming.

Supports farmers in improving yield & income.

Encourages AI-driven solutions in agriculture for long-term sustainability.

📌 Future Enhancements

Develop a mobile app for farmers (offline use).

Add real-time camera detection.

Expand dataset with more crops & diseases.

👨‍💻 Author

Your Name

Internship: Edunet Foundation Internship (AICTE)

Theme: Sustainable Agriculture
