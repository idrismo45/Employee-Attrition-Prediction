# Employee Attrition Prediction

### "An average company loses between 1% and 2.5% of their total revenue on the time it takes to bring a new hire up to speed."

- The cost of hiring a new employee averages $7,645 for small to mid-sized businesses.
- It takes 52 days on average to fill an open position.

Given these significant costs, understanding which employees are likely to leave becomes vital. By leveraging predictive analytics, companies can take proactive steps to minimize attrition, retain key talent, and reduce costs associated with turnover.

![Project Thumbnail](attrition_thumbnail.png)

In this project, we use **Artificial Neural Networks (ANNs)** to predict employee attrition, helping HR teams identify at-risk employees before they leave. With this knowledge, companies can implement retention strategies, ultimately saving time, money, and talent.

---

## Project Overview:
This project focuses on predicting employee attrition using data on various factors such as job satisfaction, workload, and performance. The aim is to provide businesses with actionable insights that can reduce turnover and improve employee retention.

### Why Predicting Attrition Matters:
- **Cost-saving**: Reduce the high cost of replacing employees.
- **Efficiency**: Prevent gaps in productivity caused by long hiring processes.
- **Employee morale**: Maintain a stable, motivated workforce.

## Key Features:
- Built an **Artificial Neural Network (ANN)** using **TensorFlow** to predict attrition likelihood.
- Preprocessed data, performed feature scaling, and evaluated the model's performance.
- Visualized data trends and model metrics using **Seaborn** and **Matplotlib**.

## Tools and Libraries:
- **TensorFlow**: For building and training the neural network.
- **Seaborn** & **Matplotlib**: For data visualization and model performance tracking.

## How to View the Project:
To dive deeper into the methodology and code, explore the **Employee_Attrition_Prediction.ipynb** file in Jupyter Notebook.

[Link to the Jupyter Notebook on GitHub](https://github.com/idrismo45/Employee-Attrition-Prediction/blob/main/Employee_Attrition_Prediction.ipynb)

### Summary Analysis: How did we get along?

This project aimed to address a key challenge for businesses: **employee attrition**. As noted, replacing an employee can cost small and mid-sized companies thousands of dollars and take weeks, impacting productivity and morale. The objective was to leverage predictive analytics to help HR teams identify at-risk employees and implement retention strategies to minimize these costs.

By comparing three models (Logistic Regression, Random Forest Classifier, and Artificial Neural Networks), we identified how effectively each could predict employee attrition. The ANN showed strong promise, particularly for identifying more nuanced patterns in the data. Although its performance was comparable to simpler models like logistic regression, it provided flexibility for future enhancement by incorporating more complex features.

#### Model Comparison:

- **Logistic Regression**: Offered a solid performance with a weighted average F1-score of 0.88. This model handled the class imbalance relatively well but struggled with recall for predicting employees likely to leave (Class 1). 
- **Random Forest Classifier**: Had an overall accuracy close to Logistic Regression but significantly lower recall for employees likely to leave. This suggests it may be better suited for identifying employees likely to stay rather than flagging potential leavers.
- **Artificial Neural Network (ANN)**: While the ANN did not significantly outperform the simpler models in terms of accuracy (0.86), its ability to capture relationships between features gives it a strategic edge in larger or more complex datasets. For the attrition prediction, however, it still struggled with recall for predicting potential attrition, scoring 0.46 for Class 1, making it necessary to explore further refinements to improve this.

### Wrapping Up the Project:

Given the results, the ANN model provides a promising foundation for attrition prediction, but further improvements are necessary, especially regarding recall for identifying at-risk employees. Next steps might include fine-tuning the model, trying different architectures, or adjusting for class imbalance using techniques such as SMOTE (Synthetic Minority Over-sampling Technique) or cost-sensitive learning. Additionally, incorporating more features related to employee sentiment or external economic conditions could further enhance model accuracy and practical utility for businesses.

In closing, this project highlights the importance of predictive analytics in reducing turnover and saving costs. However, continuous model refinement and exploration of additional data sources are critical for maintaining predictive reliability. A deeper integration of these predictions into HR workflows—such as flagging employees at risk—can empower companies to take preemptive action, ultimately leading to more effective retention strategies.
