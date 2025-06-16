# ML Image Classification

---

## ℹ️ About the Project

**ML Image Classification** is project that analyzes:

- Classify Cat Images based on Species and evaluates Accuracy, Training Time, and Testing Time, using:
  - fastAI
  - CNN with raw image input
  - CNN with cropped image input (though YOLO5)
  - YOLO11 (Ultralytics)

---

## 🛠️ Built With

- [Python](https://www.python.org/) — primary programming language
- [PyCharm](https://www.jetbrains.com/pycharm/) — IDE

- [Scikit-learn](https://scikit-learn.org/stable/) — machine learning
- [TensorFlow](https://www.tensorflow.org/) — Keras dependecies
- [Pandas](https://pandas.pydata.org/) — data manipulation
- [NumPy](https://numpy.org/) — number operations
- [Matplotlib](https://matplotlib.org/) — plotting
- [Seaborn](https://seaborn.pydata.org/) — data visualization
- [fastAI](https://www.fast.ai/) — fastAI model
- [Keras](https://keras.io/) — CNN model
- [Ultralytics](https://www.ultralytics.com/) - YOLO11 and YOLO5 model

---

## 📦 Getting Started

### Prerequisites

To run the project locally, you'll need:

- PyCharm (2025.1.1.1 or newer)

---

### Installation & Setup

1. **Install the necessary libraries:**

   ```bash
   pip install pandas numpy matplotlib seaborn scipy geopandas kaggle

2. **Download dataset through the terminal:**

   ```bash
   kaggle datasets download -d ramzanlafir/cat-breed-classification-11-classes

3. **Extract the dataset zip:**

   ```bash
   with zipfile.ZipFile("cat-breed-classification-11-classes.zip", "r") as zip_ref:
      zip_ref.extractall("cat-breed-classification-11-classes")

4. **Run the code:**

   Run the provided `code.py`

---

## 📊 Results

![Alt text](Figure_1.jpg?raw=true "Title")
![Alt text](Figure_2.jpg?raw=true "Title")
![Alt text](Figure_3.jpg?raw=true "Title")
![Alt text](Figure_4.jpg?raw=true "Title")
![Alt text](Figure_5.jpg?raw=true "Title")
![Alt text](Figure_6.jpg?raw=true "Title")
![Alt text](Figure_7.jpg?raw=true "Title")
![Alt text](Figure_8.jpg?raw=true "Title")
![Alt text](Figure_9.jpg?raw=true "Title")
![Alt text](Figure_10.jpg?raw=true "Title")
![Alt text](Figure_11.jpg?raw=true "Title")

## 📃 License

This project is licensed under the MIT License. See the `LICENSE.txt` file for more information.
