# ML_Final

### Predicting National Happiness from Socioeconomic Indicators

Explore my machine learning project where I built and compared models to predict happiness levels of countries using data from the World Happiness Report.

Tools: Python, scikit-learn, TensorFlow (Keras), Matplotlib, Pandas
What I Did: Cleaned and analyzed socioeconomic data (GDP, health, freedom, etc.), engineered binary labels from life satisfaction scores, and trained both a Logistic Regression model and a Neural Network classifier.

# results:

Both models achieved 88–89% accuracy and ROC-AUC scores above 0.95
Logistic Regression offered strong performance with interpretability.
Neural Network captured subtle nonlinear patterns and generalized well without overfitting.
Final models revealed that GDP, social support, and health were the strongest indicators of national happiness.
This project highlights my skills in data preprocessing, model evaluation, and drawing actionable insights from real-world data.

### Installation Instructions

download: 
  Python 3.8+
  pip 
  
1: Install Required Packages
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow notebook

2: Start Jupyter Notebook
In your terminal or command prompt:
jupyter notebook
Then open the notebook file (e.g. WorldHappinessClassifier.ipynb) in your browser.
3: Add the Dataset
Make sure the dataset file is placed in the same folder as your notebook or in a data/ folder.
File needed:
WHR2018Chapter2OnlineData.csv
4: Run the Notebook
Click Cell > Run All to execute the notebook top-to-bottom.
The models will train and display performance metrics and visualizations!!!
