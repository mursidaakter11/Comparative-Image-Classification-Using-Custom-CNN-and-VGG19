Comparative Image Classification Using Custom CNN and VGG19

📌 Project Overview

This project presents a comparative study of two Deep Learning models for image classification: Custom Convolutional Neural Network (CNN) and VGG19.

The main objective is to compare the performance of a Custom CNN model trained from scratch with a pre-trained VGG19 model using Transfer Learning.

This project focuses on classifying images into two categories: Cats and Dogs.
The entire project is implemented and executed using Google Colab.

🎯 Objectives
Develop a Custom CNN model for Cats and Dogs image classification.
Implement VGG19 using Transfer Learning.
Train and evaluate both models using the same dataset.
Compare model performance using different evaluation metrics.
Analyze the classification results.

🧠 Models Used
1. Custom CNN
A custom Convolutional Neural Network designed and trained from scratch for Cats and Dogs image classification.

2. VGG19
A pre-trained CNN architecture used with Transfer Learning to classify Cats and Dogs images.

🛠️ Technologies Used
Python
TensorFlow / Keras
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Google Colab
Google Drive

📂 Project Structure
Comparative-Image-Classification/
│
├── Dataset/
│   ├── cats/
│   │   ├── cat1.jpg
│   │   ├── cat2.jpg
│   │   └── ...
│   │
│   └── dogs/
│       ├── dog1.jpg
│       ├── dog2.jpg
│       └── ...
│
├── Comparative_Image_Classification.ipynb
│
└── README.md

📊 Dataset
The dataset contains two image categories:
Cats: Images of cats.
Dogs: Images of dogs.
The dataset is stored in Google Drive inside the MyDrive directory and accessed through Google Colab.

🚀 How to Run the Project (Google Colab)
Step 1: Open Google Colab
Visit: https://colab.research.google.com/

Step 2: Open the Notebook
Open Comparative_Image_Classification.ipynb in Google Colab.

Step 3: Upload Dataset to Google Drive
Upload the Dataset folder to your Google Drive (MyDrive).

Your Google Drive structure should look like this:
MyDrive/
│
└── Dataset/
    ├── cats/
    └── dogs/

Step 4: Mount Google Drive
Run the following code in Google Colab:

python
from google.colab import drive
drive.mount('/content/drive')

Step 5: Set Dataset Path
python
dataset_path = '/content/drive/MyDrive/Dataset'

Step 6: Enable GPU
Go to Runtime.
Select Change runtime type.
Choose T4 GPU (if available).
Click Save.
Step 7: Install Required Libraries
python
!pip install tensorflow numpy pandas matplotlib seaborn scikit-learn

Step 8: Run the Notebook
Run all cells sequentially in Google Colab.
The notebook will train and evaluate both Custom CNN and VGG19 models for Cats and Dogs image classification.

📈 Evaluation Metrics
Both models are evaluated using:
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
Training and Validation Accuracy
Training and Validation Loss
🏆 Results and Comparison
Evaluation Metric	Custom CNN	VGG19
Accuracy	Add Result	Add Result
Precision	Add Result	Add Result
Recall	Add Result	Add Result
F1-Score	Add Result	Add Result
Replace the placeholder values with your actual experimental results.

🔍 Conclusion
This project compares Custom CNN and VGG19 for Cats and Dogs image classification.
The experimental results help evaluate the effectiveness of a custom-built CNN model compared to a pre-trained VGG19 model using Transfer Learning.

👨‍💻 Author
Mursida Akter
GitHub: @mursidaakter11
GitHub Profile: https://github.com/mursidaakter11

📄 License
This project is developed for educational and research purposes.