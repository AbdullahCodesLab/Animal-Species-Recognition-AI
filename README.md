# Animal Species Recognition AI

A deep learning-based web application built with Streamlit that classifies animal images using pretrained convolutional neural networks such as ResNet50 and VGG16.

---

## Features

- Upload an image of an animal
- Predict the animal category using deep learning
- Uses pretrained models (ResNet50 and VGG16)
- Simple and interactive Streamlit interface
- Saves prediction results in CSV format

---

## Technologies Used

- Python
- Streamlit
- TensorFlow / Keras
- NumPy
- Pandas
- PIL (Python Imaging Library)

---

## Project Structure

Animal-Species-Recognition-AI/
│── app.py  
│── vg16.py  
│── requirements.txt  
│── test.ipynb  
│── testmodel.ipynb  
│── README.md  
│── .gitignore  

---

## How to Run the Project

1. Clone the repository

git clone https://github.com/AbdullahCodesLab/Animal-Species-Recognition-AI.git  
cd Animal-Species-Recognition-AI  

2. Install dependencies

pip install -r requirements.txt  

3. Run the app

streamlit run app.py  

---

## Note

This project uses pretrained ImageNet models for classification.  
It is not a custom-trained dataset model, so predictions may sometimes be general.

---

## Future Improvements

- Train a custom dataset for better accuracy  
- Improve UI design  
- Add more model options  
- Deploy the app online  

---

## Author

Muhammad Abdullah  
GitHub: https://github.com/AbdullahCodesLab