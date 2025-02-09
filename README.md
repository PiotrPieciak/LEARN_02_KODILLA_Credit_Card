# Credit Card Defaulter Prediction
## Description of project
This project is my first independent work, completed at the end of a five-month AI and Machine Learning course at Kodilla. My goal was to predict credit card fraud using bank data.

I started by exploring the dataset to understand patterns and possible fraud indicators. Then, I processed the data to improve model performance.

To find the best model, I tested and compared six different machine learning approaches, from simple to advanced:

1. Logistic Regression
2. Decision Tree Classifier
3. Support Vector Machine (SVM)
4. Random Forest Classifier
5. XGBoost
6. Deep Learning

For the first five models, I used a data processing pipeline and Grid Search to find the best parameters. For Deep Learning, I used a pipeline and applied SMOTE to balance the dataset and improve fraud detection.

The main goal was to optimize the performance for fraud cases, focusing on a specific score that measures how well the models detect fraud.

This project was fully completed by me and based on knowladge and skills leaned during five-month course. In my analysis, I compare different methods and share insights on what works best for detecting credit card fraud.

I achieved weighted avg F1-score 0.776 with recall 0.622 and precision 0.479 for class 1 (frauds). Recall was increased 74% compared to basic model with the cost of precision. 

## Dataset 
The dataset was provided by Kodilla and I received permission to share it on the public GitHub repository.

**Source:** [Kodilla](https://kodilla.com/)
## Installation & Setup
To run this project, you need **Python** and **Jupyter Notebook** installed and the required libraries. Follow these steps using **Anaconda Prompt**:

1. Download the repository
Click on the **Code** button and select **Download ZIP** or clone the repository using Git:	
 	```
	git clone https://github.com/PiotrPieciak/LEARN_02_KODILLA_Credit_Card.git
	cd LEARN_02_KODILLA_Credit_Card
 	```
  
3. Create and activate a Conda environment (optional but recommended)
	```
	conda create --name Credit_Card python=3.10
	conda activate Credit_Card
	```
 
4. Instal required dependencies:
	```
	pip install -r requirements.txt
 	```
 
5. Open Jupyter Notebook:
	```
 	jupyter notebook
  	```
 
6. Run the project
* Open LEARN_02_KODILLA_Credit_Card_Defaulter_Prediction.ipynb in Jupyter Notebook.
* Run all cells to execute the analysis.

**Note:**  The dataset (default_of_credit_card_clients.xls) must be in the same folder as the notebook for the code to work correctly.

## Dependencies
* imbalanced-learn==0.12.4
* matplotlib==3.9.2
* numpy==1.26.4
* pandas==2.2.2
* scikit-learn==1.5.1
* seaborn==0.13.2
* tensorflow==2.18.0
* xgboost==2.1.2
