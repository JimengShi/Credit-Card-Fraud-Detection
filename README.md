# Credit-Card-Fraud-Detection
Based on the data of credit card transaction records, a classification model is built to predict which transaction records are abnormal and which are normal.

## Task Flow:
- Load the data and observe the problem
- Provide solutions to problems
- Build logistic regression model
- Compare evaluation methods
- Analyze modeling results
- Adjust logistic regression model
- Scheme effect comparison

<div align="center">
<img src="https://github.com/JimengShi/Credit-Card-Fraud-Detection/blob/master/images/Workflow.png" alt="Workflow" >
</div>

## Model Performance:
The performance of model is good, precision rate is 99.17%, recall rate is 99.97% and the F1 score is 0.99.
- Class 0: normal transaction record
- Class 1: abnormal transaction record
- Left: performance with under-sampling
- Right: performance with over-sampling

<div align="center">
<img src="https://github.com/JimengShi/Credit-Card-Fraud-Detection/blob/master/images/Evaluation%20with%20under-sampling.png" height="300px" alt="Evaluation with under-sampling" ><img src="https://github.com/JimengShi/Credit-Card-Fraud-Detection/blob/master/images/Evaluation%20with%20over-sampling.png" height="300px" alt="over-sampling" >    
</div>

<div align="center">
<img src="https://github.com/JimengShi/Credit-Card-Fraud-Detection/blob/master/images/Confusion%20Matrix.png" height="300px" alt="Evaluation" >
</div>

## How to Run:
**Environment:**
- Window 10
- Anaconda 4.8.3, built in Jupyter Notebook, Numpy, Pandas, Matplotlib
- Python 3.7.4 with some necessary libraries, like sklearn

Because the dataset is kind of big that cann't be uploaded. Please check out the `dataset` folder and download the dataset online. Then put it in the same path with '.ipynb' file, now I believe it's okay to run the '.ipynb' file in Jupyter Notebook.
