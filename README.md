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
- **Keras**: Integrated with TensorFlow to construct and optimize the ANN.
- **Pandas**: For data manipulation and preprocessing.
- **NumPy**: For numerical operations and feature scaling.
- **Scikit-learn**: For data splitting, scaling, and model evaluation metrics.
- **Seaborn** & **Matplotlib**: For data visualization and model performance tracking.

## How to View the Project:
To dive deeper into the methodology and code, explore the **Employee_Attrition_Prediction.ipynb** file in Jupyter Notebook.

[Link to the Jupyter Notebook on GitHub](https://github.com/idrismo45/Employee-Attrition-Prediction/blob/main/Employee_Attrition_Prediction.ipynb)

**Final Thoughts**

This project tackles a pressing business issue: employee attrition. Replacing employees can cost thousands of dollars and take several weeks, significantly impacting productivity and team morale. The goal was to harness predictive analytics to assist HR teams in identifying employees at risk of leaving and implementing effective retention strategies.

By evaluating three models—Logistic Regression, Random Forest Classifier, and Artificial Neural Networks (ANNs)—we assessed their performance in predicting employee attrition.

### **Model Comparison:**

- **Logistic Regression**: Achieved a robust weighted average F1-score of 0.88. This model effectively handled class imbalance but had lower recall for predicting employees likely to leave (Class 1). This indicates that while it was good at identifying those who would stay, it was less effective at spotting potential leavers.

- **Random Forest Classifier**: Showed comparable accuracy to Logistic Regression but had notably lower recall for Class 1, meaning it was less effective at flagging employees who might leave. It performed better in predicting employees likely to stay but missed many at-risk individuals.

- **Artificial Neural Network (ANN)**: Although it offered flexibility and could model complex relationships, it did not significantly outperform the simpler models in terms of accuracy (0.86). The ANN struggled with recall for Class 1, suggesting that while it can capture intricate patterns, it needs further refinement to improve its predictions of at-risk employees.

### **Key Insights for Implementation:**

- **Identify High-Risk Employees**: Focus on employees predicted as at-risk (Class 1) or those with lower confidence in staying (Class 0). These employees are more likely to leave and require targeted support.

- **Actionable Steps**: Provide additional support and personalized interventions to these at-risk employees. This could include offering extra benefits, career development opportunities, or improved work conditions to enhance their job satisfaction and retention.

### **Next Steps:**

- **Model Enhancement**: Further refine the ANN model to improve recall for predicting at-risk employees. Consider techniques such as SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance, or explore alternative model architectures for better performance.

- **Integrate Insights**: Apply predictive insights directly into HR strategies. Develop and implement tailored retention strategies based on the model's predictions to proactively address potential attrition, optimize resource allocation, and improve overall employee satisfaction.

- **Ongoing Evaluation**: Continuously monitor and evaluate the effectiveness of the retention strategies. Gather feedback from employees and adjust interventions as necessary to ensure they are meeting their goals and effectively reducing turnover.

**Conclusion**

This project demonstrates the potential of predictive analytics in managing employee attrition. While the ANN model provides a solid foundation, further improvements are necessary to enhance its predictive accuracy. By focusing on at-risk employees and implementing targeted strategies, companies can reduce turnover, save costs, and foster a more stable and engaged workforce.
