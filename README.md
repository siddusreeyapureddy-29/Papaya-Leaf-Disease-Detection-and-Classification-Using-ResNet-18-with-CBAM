# Papaya-Leaf-Disease-Detection-and-Classification-Using-ResNet-18-with-CBAM
Papaya Leaf Disease Detection and Classification project
# Papaya Leaf Disease Detection and Classification Using ResNet-18 with CBAM

## 📌 About the Project

Papaya Leaf Disease Detection and Classification is a deep learning-based project designed to identify and classify different diseases affecting papaya leaves using image processing and deep learning techniques.

The proposed system uses a **ResNet-18 architecture integrated with Convolutional Block Attention Module (CBAM)** to improve feature extraction by focusing on important channel-wise and spatial features.

The model uses transfer learning with pretrained ImageNet weights to classify papaya leaf images into eight different categories, helping support early disease identification and agricultural disease management.

## 🎯 Objectives

- Develop an automated system for papaya leaf disease detection.
- Classify papaya leaves into different disease categories.
- Improve classification performance using ResNet-18 with CBAM.
- Utilize transfer learning to improve feature extraction.
- Apply channel attention and spatial attention mechanisms.
- Support early identification of papaya leaf diseases.

## ✨ Key Features

- **Deep Learning Architecture:** Uses ResNet-18 integrated with CBAM.
- **Transfer Learning:** Utilizes pretrained ImageNet weights.
- **Attention Mechanism:** Focuses on important image features through channel and spatial attention.
- **Multi-Class Classification:** Identifies eight different papaya leaf categories.
- **Image Preprocessing:** Applies resizing, normalization, and data augmentation.
- **Performance Evaluation:** Evaluates the model using precision, recall, F1-score, and accuracy.

## 🌿 Disease Categories

The proposed model classifies papaya leaf images into the following eight categories:

1. Anthracnose
2. Bacterial Spot
3. Leaf Curl
4. Healthy
5. Mite Disease
6. Mealy Bug
7. Mosaic
8. Ring Spot

## 🧠 Model Architecture

The proposed architecture combines ResNet-18 with the Convolutional Block Attention Module (CBAM).

**ResNet-18:**
- Uses residual connections to improve deep feature learning.
- Extracts important features from papaya leaf images.
- Uses pretrained ImageNet weights through transfer learning.

**CBAM (Convolutional Block Attention Module):**
- Channel Attention: Identifies important feature channels.
- Spatial Attention: Highlights important spatial regions in the image.
- Helps the network focus on relevant disease patterns.

## 📊 Dataset Details

The project uses a combined papaya leaf disease image dataset, including the BDPapayaLeaf dataset (2024).

| Dataset | Number of Images |
|---|---:|
| Training Images | 14,504 |
| Testing Images | 3,626 |
| Total Images | 18,130 |
| Number of Classes | 8 |

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Deep Learning Framework:** PyTorch
- **Model Architecture:** ResNet-18
- **Attention Mechanism:** CBAM
- **Libraries:**
  - Torch
  - Torchvision
  - NumPy
  - Pandas
  - Matplotlib
  - Scikit-learn
  - OpenCV

## ⚙️ Image Preprocessing

The following preprocessing and augmentation techniques are used:

- Image Resizing (224 × 224).
- Random Resized Crop.
- Random Horizontal Flip.
- Random Vertical Flip.
- Random Rotation.
- Color Jitter.
- Image Normalization.
- Random Erasing.

## 📈 Model Evaluation

The proposed model is evaluated using the following performance metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

The model demonstrates strong classification performance across the eight papaya leaf disease categories.

## 🚀 Installation and Execution

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the Project Directory

```bash
cd Papaya-Leaf-Disease-Detection
```

### 3. Install Required Libraries

```bash
pip install torch torchvision
pip install numpy pandas matplotlib scikit-learn opencv-python
```

### 4. Run the Project

Open the project notebook or Python script in Jupyter Notebook, Google Colab, or VS Code and execute the cells.

## 🔮 Future Enhancements

- Develop a web-based disease detection application.
- Integrate the trained model with Flask or FastAPI.
- Build a mobile application for farmers.
- Provide disease-specific treatment recommendations.
- Extend the dataset with additional papaya disease samples.
- Deploy the model for real-time disease prediction.

## 👨‍💻 Project Information

**Project Title:** Papaya Leaf Disease Detection and Classification Using ResNet-18 with CBAM

**Project Domain:** Artificial Intelligence and Deep Learning

**Project Type:** Final Year Academic Project

**Team Size:** 4 Members

**Role:** Team Leader

**Programming Language:** Python

**Framework:** PyTorch

## 📜 License

This project was developed for academic and educational purposes.
