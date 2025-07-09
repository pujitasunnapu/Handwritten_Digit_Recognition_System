# 🧠 Handwritten Digit Recognition with CNN

A Deep Learning Model to Accurately Classify Digits from Images (MNIST Dataset)

---

## ❓ Business Questions

* How can we automate digit recognition for scanned handwritten forms and documents?
* Can a neural network match or exceed human-level accuracy in recognizing digits?
* What architecture best balances high accuracy with computational efficiency?
* How does the model perform on real-world handwriting, not just curated datasets?
* What mistakes does the model make, and why?

---

## ⚡ TL;DR – Summary of How I Solved It

* Built a **deep CNN** model using Keras with LeakyReLU, Dropout, BatchNorm, and MaxPooling
* Preprocessed and split the **MNIST dataset** into training, validation, and test sets
* Achieved **>99.4% test accuracy** with no significant overfitting
* Evaluated using accuracy/loss plots, confusion matrix, and real handwritten images
* Included **top-2 prediction logic** for interpretability and edge-case handling

---

## 🧰 Data & Tools Used

* **Dataset**: [MNIST original] (https://www.kaggle.com/datasets/avnishnish/mnist-original)
* **Libraries**: Python, NumPy, Matplotlib, Seaborn, OpenCV, SciPy
* **Modeling**: TensorFlow / Keras (Sequential CNN)

---

## 🔍 Key Features of the Project

* 4-layer **Convolutional Neural Network** with \~670K parameters
* Dropout and BatchNormalization to prevent overfitting
* Visualizations:

  * Training vs Validation Accuracy/Loss Curves
  * Correct and Incorrect Predictions (with confidence scores)
  * Confusion Matrix (clear model performance insights)
* Tested on **real handwritten digits** outside the MNIST dataset

---

## 🖼️ Screenshots or Demo

### Model Performance

![Screenshot 2025-07-09 170308](https://github.com/user-attachments/assets/e9b9a181-49a0-4c81-96b2-d8c8f36c654d)


### Confusion Matrix

![Screenshot 2025-07-09 170443](https://github.com/user-attachments/assets/7c038298-1449-49c5-80d7-26a6a9dacf03)


### Real Digit Predictions

![Screenshot 2025-07-09 174113](https://github.com/user-attachments/assets/fb1080de-49a3-44ee-b271-8cc0f98c17da)


---

## 💼 Outcome / Business Value

* Achieves near-perfect digit classification: **99.4% test accuracy**
* Reduces manual data entry for digit-based forms like:

  * Bank checks
  * Exam sheets
  * Zip codes or IDs in scanned forms
* Demonstrates a reusable pipeline for document digitization and OCR pre-processing
* Can be extended to full OCR solutions or mobile image classification apps

---

## ▶️ How to Use the Project

1. Clone the repo:

   ```
   git clone https://github.com/pujitasunnapu/Handwritten_Digit_Recognition_System
   cd Handwritten_Digit_Recognition_System
   ```
2. Install dependencies (preferably in a virtual environment):

   ```
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook or Python script:

   * `Handwritten Digit Classification.ipynb` (with visual outputs)
4. (Optional) Replace real image paths in the last section to test with your own handwriting samples

---

## 🔮 Next Steps or Improvements

* Deploy using **Flask** or **Streamlit** for real-time predictions
* Add **data augmentation** for better robustness on distorted handwriting
* Train on **EMNIST** to expand to alphabets
* Build a mobile-friendly interface or digit recognition API
