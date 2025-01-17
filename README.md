
# Decision Tree Classifier: Predicting Diabetes

This project demonstrates the use of a Decision Tree Classifier to predict diabetes outcomes based on the Pima Indians Diabetes dataset. The project includes steps for loading data, training the model, evaluating accuracy, and visualizing the decision tree.

## Table of Contents
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Usage](#usage)
- [Results](#results)
- [Visualizations](#visualizations)


---

## Dataset
The Pima Indians Diabetes dataset contains diagnostic measurements related to diabetes. The dataset includes the following columns:
- `pregnant`: Number of times pregnant
- `glucose`: Plasma glucose concentration
- `bp`: Blood pressure (mm Hg)
- `skin`: Skin thickness (mm)
- `insulin`: Insulin level
- `bmi`: Body mass index
- `pedigree`: Diabetes pedigree function
- `age`: Age (years)
- `label`: Target variable (0 = no diabetes, 1 = diabetes)

Data file location: ### Decision Tree (Default Parameters)
![Data](https://github.com/GOHOUEDE/Decision-tree-classification/blob/main/pima-indians-diabetes.csv)

---

## Requirements
This project requires the following Python libraries:
- `pandas`
- `scikit-learn`
- `matplotlib`

Install the requirements using:
```bash
pip install pandas scikit-learn matplotlib
```

---

## Usage
1. Clone this repository:
    ```bash
    git clone https://github.com/GOHOUEDE/Decision-tree-classification.git
    ```
2. Navigate to the project directory:
    ```bash
    cd decision-tree-diabetes
    ```
3. Place the dataset (`pima-indians-diabetes.csv`) in the `data` folder.


---

## Results
The Decision Tree Classifier was trained and tested using the Pima Indians Diabetes dataset. Two models were trained:

1. **Default Decision Tree**:
   - Accuracy: **70.13%**

2. **Decision Tree with Criterion = "Entropy" and Max Depth = 3**:
   - Accuracy: **77.06%**

---

## Visualizations
### Decision Tree (Default Parameters)
![Decision Tree Default](plots/graphic1.png)

### Decision Tree (Entropy, Max Depth = 3)
![Decision Tree Entropy](plots/graphic2.png)

The visualizations display the decision-making process of the trained classifiers.

---

