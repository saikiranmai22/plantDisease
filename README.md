---

## Plant Disease Detection using Deep Learning

This project detects crop diseases from leaf images using a Convolutional Neural Network built with TensorFlow and Keras. The trained model predicts 38 different plant disease categories.

---

### About Dataset

This dataset is recreated using offline augmentation from the original dataset. The original dataset can be found on its respective GitHub repository.

This dataset consists of about 87K RGB images of healthy and diseased crop leaves categorized into 38 different classes. The total dataset is divided into an 80/20 ratio of training and validation sets while preserving the directory structure.

A new directory containing 33 test images is created later for prediction purposes.

#### Dataset Content

1. train (70,295 images)
2. test (33 images)
3. validation (17,572 images)

---

### Project Structure

```
├── main.py                     # Streamlit application
├── trained_model.h5 / .keras   # Trained model
├── training_hist.json          # Model training history
├── plantimage.jpg
├── Train_plant_disease.ipynb   # Notebook used for model training
└── Test_Plant_Disease.ipynb    # Notebook used for testing predictions
├── train/                      # Training dataset
├── valid/                      # Validation dataset
└── test/                       # Testing dataset
```

---

### Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib
* Streamlit

---

### Installation

1. Clone the repository:

```
git clone https://github.com/saikiranmai22/plantDisease.git
cd plantDisease
```

2. Install dependencies:

```
pip install -r requirements.txt
```

---

### Running on Streamlit

Execute the command below in the project directory:

```
streamlit run main.py
```

---

