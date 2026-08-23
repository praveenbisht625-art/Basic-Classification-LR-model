# 🌸 Iris Flower Classification

## 📌 About the Project

This is my first Machine Learning classification project.

The goal of this project is to build a Machine Learning model that can predict the species of an iris flower based on its sepal and petal measurements.

I used a **Decision Tree Classifier** to learn patterns from the dataset and make predictions for new flower measurements.

## 📊 Dataset

The dataset contains measurements of iris flowers along with their species.

### Features

* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

### Target

The model classifies flowers into three species:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook / Google Colab

## 🤖 Machine Learning Model

I used the **Decision Tree Classifier** from Scikit-learn.

The model learns decision rules from the flower measurements and uses those rules to predict the species of a new flower.

## 🔄 Project Workflow

```text
Dataset
   ↓
Exploring the Data
   ↓
Preparing Features & Target
   ↓
Training the Decision Tree
   ↓
Making Predictions
   ↓
Decision Tree Visualization
```

## 🌳 Decision Tree Visualization

The trained Decision Tree was visualized using `plot_tree()` to understand how the model makes classification decisions.

The visualization shows information such as:

* Features used for splitting
* Gini impurity
* Number of samples
* Class distribution
* Predicted class

## 🔮 Example Prediction

The model can take new flower measurements such as:

```python
[5.4, 3.2, 1.7, 0.2]
```

and predict the corresponding iris species.

## 📚 What I Learned

Through this project, I learned the basic workflow of a Machine Learning classification problem, including:

* Understanding a dataset
* Selecting features and target
* Training a classification model
* Making predictions on new data
* Understanding and visualizing a Decision Tree

## 🚀 Future Learning

This project is the beginning of my Machine Learning journey. I plan to learn more Machine Learning concepts and apply them to larger and more practical datasets in future projects.

---

**First ML project completed! 🌸🤖**
