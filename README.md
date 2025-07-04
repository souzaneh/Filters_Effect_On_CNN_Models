# 🧩 Visualizing the Impact of Filter Weights in Deep Convolutional Neural Networks (CNN)

This project demonstrates how **filter weights** in different layers of **Convolutional Neural Networks (CNNs)** affect the detection of specific features in images. The goal is to visualize which parts of an image are activated by each filter and how the network interprets patterns at various layers.

---

## 🎯 Project Objective

The main objective of this project is to:
- Explore the role of **filter weights** in CNNs.
- Visualize how simple custom filters react to images by highlighting different parts based on their weights.

---

## ⚙️ Technologies and Tools Used

- **Language:** Python
- **Frameworks and Libraries:**  
  - TensorFlow  
  - Keras  
  - NumPy  
  - Matplotlib  
  - Scikit-learn  

---

## 📅 Dataset

- **Source:** CIFAR-10 Dataset
- **Images:** A subset of **10 images** from CIFAR-10 is used.
- **Image Size:** Each image is of shape **32x32x3 (RGB)**.
- **Normalization:** All image pixel values are normalized to a range between **0 and 1**.

---

## 🏗️ Methodology

1. **Filter Design:**
   - Two custom **3x3 filters** were designed.
   - Each filter has weight values of **1 along one of its diagonals** and **0 elsewhere**.

2. **Convolution Process:**
   - Each filter is applied (convolved) over the images.
   - The output of each convolution operation highlights specific parts of the images based on the filter weights.

3. **Visualization:**
   - The original images and their corresponding **filtered outputs** are plotted using **Matplotlib** to demonstrate how different filters emphasize different regions or patterns in the image.

---

## 📊 Results

- The visualizations clearly show that:
  - Each custom filter activates specific diagonal patterns in the images.
  - The choice of filter weights plays a key role in the way features are extracted in CNN layers.

---

## 🔍 Limitations & Future Work

- This project uses very **simple custom filters** for visualization purposes.
- Future work could explore:
  - Deeper networks with multiple learned filters.
  - Visualization of feature maps from **trained CNN models**.
  - Comparison of activation patterns across different datasets.

---

## 🚀 How to Run

1. Clone the repository or download the code.
2. Install the required libraries:

pip install -r requirements.txt

3. Open the notebook in:
- Google Colab
- Jupyter Notebook
4. Run the notebook to view visualizations.

---

## 👩‍💻 Author

**Souzaneh Sehati**  
GitHub: [souzaneh](https://github.com/souzaneh)

---

## ⚠️ Disclaimer

This project is for **educational and research purposes only**.

