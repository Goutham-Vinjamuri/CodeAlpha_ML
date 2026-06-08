# Handwritten Character Recognition using CNN

## Project Overview

This project focuses on recognizing handwritten English alphabet characters using Deep Learning. A Convolutional Neural Network (CNN) is trained on the EMNIST Letters dataset to classify handwritten characters from A-Z.

The model learns image patterns and predicts the corresponding alphabet with high accuracy.

---

## Objective

To build an intelligent handwritten character recognition system capable of accurately identifying handwritten English letters using a Convolutional Neural Network (CNN).

---

## Dataset

Dataset Used: EMNIST Letters Dataset

Features:

- Handwritten alphabet images
- 28 × 28 grayscale images
- 26 output classes (A-Z)

Dataset Size:

- Training Samples: 124,800
- Testing Samples: 20,800

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- EMNIST Dataset

---

## Project Workflow

1. Load EMNIST Letters Dataset
2. Data Preprocessing
   - Image normalization
   - Reshaping images
   - One-hot encoding labels
3. Build CNN Architecture
4. Train CNN Model
5. Evaluate Model Performance
6. Generate Predictions
7. Visualize Results
8. Save Trained Model

---

## CNN Architecture

The Convolutional Neural Network consists of:

- Conv2D Layer (32 Filters)
- MaxPooling Layer
- Conv2D Layer (64 Filters)
- MaxPooling Layer
- Flatten Layer
- Dense Layer (128 Neurons)
- Dropout Layer
- Output Layer (26 Classes)

---

## Results

The trained model achieved high classification accuracy on the EMNIST test dataset.

Performance Evaluation:

- Training Accuracy
- Validation Accuracy
- Test Accuracy
- Confusion Matrix
- Classification Report

---

## Result Screenshots

The Results folder contains:

- Sample_Characters.png
- CNN_Architecture.png
- Accuracy_Graph.png
- Loss_Graph.png
- Confusion_Matrix.png
- Predictions.png
- Final_Accuracy.png

---

## Model Evaluation Metrics

The project evaluates performance using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Future Improvements

- Real-time character recognition using webcam
- Recognition of words and sentences
- Deployment using Flask or Streamlit
- Support for multiple languages

---

## Project Structure

Task3_HandwrittenRecognition

├── Handwritten_Recognition.ipynb

├── README.md

├── requirements.txt

└── Results

    ├── Sample_Characters.png
    
    ├── CNN_Architecture.png
    
    ├── Accuracy_Graph.png
    
    ├── Loss_Graph.png
    
    ├── Confusion_Matrix.png
    
    ├── Predictions.png
    
    └── Final_Accuracy.png

---

## Conclusion

This project successfully demonstrates the application of Convolutional Neural Networks for handwritten character recognition. The model effectively learns visual patterns from handwritten alphabet images and predicts characters with high accuracy, making it suitable for document digitization and optical character recognition applications.

---

## 👤 Author

**Goutham Vinjamuri**

ML Intern | [LinkedIn Profile](https://www.linkedin.com/in/goutham-vinjamuri-902787326)

<small>Developed as part of the Machine Learning Internship at CodeAlpha.</small>

---

**📄 License**

<small>This project is open-source and available under the MIT License.</small>
