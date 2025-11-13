📘 Overview

This project predicts whether a person is likely to buy insurance based on their age using the Logistic Regression algorithm.
It’s a simple binary classification model built with Python, Pandas, Matplotlib, and Scikit-learn.

The main goal is to demonstrate how logistic regression can classify outcomes (Yes/No) and visualize the relationship between data features.

📂 Project File

ageInsurance_model.ipynb — Main Jupyter Notebook containing the complete workflow, from data preprocessing to model prediction.

⚙️ Requirements

Make sure the following Python libraries are installed before running the notebook:

pip install pandas matplotlib scikit-learn

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/junaid56o/ageInsurance-model.git


Open the project folder:

cd <ageInsurance-model>


Launch the notebook:

jupyter notebook ageInsurance_model.ipynb

🧩 Workflow Summary

Import Libraries – Pandas, Matplotlib, and Scikit-learn

Load Dataset – Age vs. Bought Insurance data

Data Preprocessing – Convert categorical values (“Yes”/“No”) into numeric (1/0)

Visualization – Scatter plot showing the relationship between age and insurance purchase

Model Training – Logistic Regression model using train_test_split() and fit()

Predictions – Predict if a person with a given age is likely to buy insurance

📊 Sample Predictions
Age	Prediction	Meaning
19	0	Not likely to buy insurance
30	1	Likely to buy insurance
60	1	Likely to buy insurance
🧠 Concepts Demonstrated

Logistic Regression for binary classification

Data preprocessing using Pandas

Data visualization using Matplotlib

Model training and testing with Scikit-learn

Basic ML workflow understanding

📈 Insight

The model shows that individuals above age 30 have a higher probability of buying insurance, while those younger than 30 are less likely to purchase one.

🧰 Technologies Used

Python 3.x

Pandas

Matplotlib

Scikit-learn

Jupyter Notebook

🤝 Contributing

You can fork this repository, modify the dataset, or try additional features like gender, income, or location to improve model performance.

📄 License

This project is licensed under the MIT License.
Feel free to use and modify it for educational or research purposes.
