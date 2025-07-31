# X-Ray Fracture Classification using CNNs

This project focuses on classifying X-ray images as *fractured* or *not fractured* using Convolutional Neural Networks (CNNs). Two models are implemented and compared:
- A CNN model built *from scratch*
- A model using *transfer learning* with a pretrained network

## 🔍 Objective
To explore and compare the performance of CNNs trained from scratch versus those built on pretrained models in detecting bone fractures from X-ray images.

## 🧠 Models Used
- *Custom CNN*: A basic convolutional neural network architecture built from scratch.
- *Transfer Learning*: A pretrained model fine-tuned on our dataset for better performance and faster training.

## 📁 Dataset
- X-ray images labeled as fractured or not fractured
- The X-ray images used in this project were obtained from ( https://www.kaggle.com/datasets/bmadushanirodrigo/fracture-multi-region-x-ray-data/data )

## 🛠️ Tools & Libraries
- Python
- TensorFlow / Keras 
- OpenCV / PIL
- NumPy, Pandas, Matplotlib

## 🚀 Results
| Model             | Accuracy | Loss   |
|------------------|----------|--------|
| CNN from Scratch | 98%      | 0.04     |
| Transfer Learning| 99%      | 0.04     |


## 📈 Visualizations
- Training/validation accuracy and loss curves
