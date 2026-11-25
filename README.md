## Bank Deposit Creation Prediction

Here In this project, we compare different machine learning classification algorithms which will predict whether the customer will agree to create
to a term deposit based on the finanacial , demographic information.

The objective is to identify the best machine learning models that can be used for the Bank Marketing Dataset.

## Dataset : Bank Marketing Dataset
## Source : Kaggle

Total of 11,162 recors and 16 input features with 1 target variable.
The Target Variable will be "deposit" with a value Yes or No .

## Data Preprocessing

For data preprocessing the following steps were performed :
          1.   Data Quality assesment
          2.   Train-test split (80:20)
          3.   Missing Value Analysis
          4.   Creation of pre processing pipeline
          5.   Feature Target seperation

## Model Comparison 
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Model</th>
      <th>Accuracy</th>
      <th>Precision</th>
      <th>Recall</th>
      <th>F1 Score</th>
      <th>MCC</th>
      <th>AUC</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Random Forest</td>
      <td>0.8513</td>
      <td>0.8190</td>
      <td>0.8809</td>
      <td>0.8488</td>
      <td>0.7047</td>
      <td>0.9173</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Logistic Regression</td>
      <td>0.8262</td>
      <td>0.8278</td>
      <td>0.7996</td>
      <td>0.8135</td>
      <td>0.6513</td>
      <td>0.9071</td>
    </tr>
    <tr>
      <th>2</th>
      <td>K-Nearest Neighbors</td>
      <td>0.8222</td>
      <td>0.8282</td>
      <td>0.7883</td>
      <td>0.8077</td>
      <td>0.6433</td>
      <td>0.8881</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Decision Tree</td>
      <td>0.8110</td>
      <td>0.8093</td>
      <td>0.7864</td>
      <td>0.7977</td>
      <td>0.6207</td>
      <td>0.8798</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Naive Bayes</td>
      <td>0.7232</td>
      <td>0.7170</td>
      <td>0.6871</td>
      <td>0.7017</td>
      <td>0.4442</td>
      <td>0.8007</td>
    </tr>
  </tbody>
</table>
</div>
