🌿 Plant Disease Recognition System
A Deep Learning-based web application for identifying plant diseases from leaf images. This system helps farmers, agricultural professionals, and researchers quickly detect plant health issues using computer vision and image classification.

🚀 Features
Upload leaf images to detect diseases
Trained Convolutional Neural Network (CNN) for image classification
Supports multiple plant types and common diseases
User-friendly web interface (Flask-based)
Option to retrain with custom datasets

🏗️ Project Structure
php
Copy
Edit
Plant-Disease-Recognition-System-main/
├── model/                  # Pretrained model (.h5)
├── static/                 # CSS, JS, and image assets
├── templates/              # HTML pages
├── dataset/                # (Optional) Training dataset
├── app.py                  # Flask web application
├── train_model.py          # Script to train the CNN
└── README.md               # Project description
🖼️ Sample Predictions
Upload a leaf image, and the system will display the predicted disease name and confidence level.

🧪 Technologies Used
Python

TensorFlow / Keras

Flask

OpenCV

HTML, CSS, JavaScript

📦 Installation
bash
Copy
Edit
git clone https://github.com/yourusername/Plant-Disease-Recognition-System-main.git
cd Plant-Disease-Recognition-System-main
pip install -r requirements.txt
python app.py
Open browser at http://127.0.0.1:5000/

📚 Dataset
The model is trained on the PlantVillage Dataset. You can replace or extend it with other labeled plant image datasets.

🛠️ Future Improvements
Mobile app integration (Android/iOS)

Multi-language support

Real-time webcam detection

More plant species and diseases

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to fork and submit a pull request.

📜 License
This project is licensed under the MIT License.

