# Dog-Breed-Classification-and-Info-Generation
This project develops a deep learning model using Convolutional Neural Networks (CNNs) to classify dog breeds from images. A user-friendly interface allows image uploads, predicts the breed, and generates relevant information. It showcases the use of AI and computer vision in real-world image classification tasks.
# 🐶 Dog Breed Classification

## 📌 Project Overview  
This project is developed as part of the **Infosys Springboard Internship**.  
The goal is to build a **machine learning model** that can classify dog images into their respective breeds. The project uses **deep learning (CNN)** and image preprocessing techniques to ensure accurate classification.

## 🎯 Objectives  
- Preprocess and clean the dataset of dog images.  
- Build and train a **Convolutional Neural Network (CNN)** for breed classification.  
- Evaluate model performance using accuracy and loss metrics.  
- Deploy the trained model for easy usage.  

## 🗂 Dataset  
- **Source**: Kaggle – Dog Breed Dataset.  
- Contains images of various dog breeds with corresponding labels.  
- Preprocessing includes:  
  - Image resizing (224×224).  
  - Normalization.  
  - Data augmentation (rotation, flipping, zooming).  

## 🛠️ Tech Stack  
- **Languages**: Python  
- **Libraries/Frameworks**:  
  - OpenCV, TensorFlow/Keras, NumPy, Pandas, Matplotlib, Scikit-learn  
- **Tools**: Jupyter Notebook / VS Code  
- **Version Control**: GitHub  

## ⚙️ Installation & Setup  
```bash
# Clone the repository
git clone https://github.com/your-username/dog-breed-classification.git
cd dog-breed-classification

# Install dependencies
pip install -r requirements.txt

# Run training script
python train.py

# Run inference
python predict.py --image sample.jpg
