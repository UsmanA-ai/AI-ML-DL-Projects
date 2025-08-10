# 🌸 Iris Classification using Random Forest

This project classifies iris flowers into three species — *Setosa*, *Versicolor*, and *Virginica* — using the famous Iris dataset and a **Random Forest Classifier** from scikit-learn.

## 📂 Project Structure
```
Iris-Classification/
│
├── data/
│   └── Iris.csv                # Dataset
│
├── iris_classification.ipynb   # Main Jupyter Notebook
├── README.md                   # Project documentation
└── requirements.txt            # Required Python packages
```

## 🚀 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Iris-Classification.git
   cd Iris-Classification
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook iris_classification.ipynb
   ```
4. Run the notebook cells to train and evaluate the model.

## 📊 Dataset
The dataset contains 150 samples with 4 features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target variable:
- **Species**: Setosa, Versicolor, Virginica

## 🧠 Model Used
We use **RandomForestClassifier** with:
- `n_estimators=100`
- `random_state=42`

## 📈 Results
The model achieves **~97% accuracy** on the test data.

## 📜 License
This project is open-source under the MIT License.
