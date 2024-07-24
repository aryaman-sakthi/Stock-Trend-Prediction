<div class="Image" align="center">
  <img src="https://miro.medium.com/v2/resize:fit:626/0*SaNg8uUaKCMQSS5g.jpg" alt="Logo" width="220" height="120">
</div>
<h1 align="center"><b>Stock Trend Prediction</b><br> 
Using Candlestick Charting and Ensemble Machine Learning Techniques
</h1> 

## About:
![](https://github.com/aryaman-sakthi/Stock-Trend-Prediction/blob/main/assets/CandelStick_Charting.png) <br><br>
This project aims to predict stock trends using a combination of candlestick charting and ensemble machine learning techniques. The stock market is a complex and dynamic financial marketplace where predicting stock price movements can provide valuable insights for investors. By combining traditional candlestick charting with advanced machine learning algorithms, we aim to create a robust prediction framework.

## Proposed Model:
This paper proposes an adaptive prediction framework using an ensemble of machine learning models to predict the 
direction of the closing price, which is shown in the Figure Below.  

First, the Moving average and Exponential Moving average is calculated in the Stock data set. Then, all featured data is passed as input to multiple machine learning models and the method with the highest prediction accuracy is recorded.  

Finally, the data is passed through an Ensemble model that aggregate the predictions of the individual models and verifies the prediction accuracy of each pattern by processing the data.

<div class="Image" align="center">
  <img src="https://github.com/aryaman-sakthi/Stock-Trend-Prediction/blob/main/assets/Proposed%20Model.jpg" alt="Model" width="800" height="480">
</div>

## Key Objectives:
* **Data Preprocessing:** Clean and prepare stock price data for analysis.
* **Candlestick Charting:** Utilize candlestick patterns to capture historical price movements.
* **Feature Engineering:** Extract relevant features from the data to enhance the predictive power of the models.
* **Ensemble Learning:** Implement and compare different ensemble machine learning techniques to predict stock trends.
* **Model Evaluation:** Assess the performance of the models using various metrics and visualization techniques.

## Model Accuracy: 
![](https://github.com/aryaman-sakthi/Stock-Trend-Prediction/blob/main/assets/Model_Accuracy.png)

## Built With:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-F37626?logo=jupyter&logoColor=fff&style=for-the-badge)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) 
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) 
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) 

## Conclusion:
Stock trend prediction is a challenging yet rewarding task that can provide significant insights for investors and traders. This project successfully combines traditional candlestick charting methods with modern machine learning techniques to create a predictive framework.  
Through rigorous data preprocessing, feature engineering, and model evaluation, we have demonstrated the effectiveness of our approach in predicting stock price movements. Future work could involve integrating more advanced machine learning models and expanding the dataset to improve prediction accuracy.
