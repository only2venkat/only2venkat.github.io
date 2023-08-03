## Modeling For Home-Credit

### Business problem and project objective
Home Credit is a multinational financial institution that specializes in providing loans to individuals with inadequate credit history. They aim to promote financial inclusion by offering accessible financial services to underprivileged populations. Home Credit develops creative financing solutions by using non-traditional data sources and other alternative techniques to evaluate creditworthiness. Their customer-centric approach and fast, convenient lending process empower individuals to make important purchases and build a positive credit history. Home Credit reduces the risks involved with lending to borrowers with spotty credit histories by using advanced risk management models. Overall, they strive to democratize access to financial services and create a positive social impact.

The business problem that the Home Credit seeks to address is how to predict which loan applicants are more likely to default. This is a critical problem for Home Credit, as it allows them to make more informed lending decisions and reduce the risk of default.

The primary objective of this project is to develop a predictive model that can accurately assess the creditworthiness of loan applicants based on various features and historical data provided by Home Credit.

### Our solution to the business problem.
The XGBoost (XGB) model, trained on upsampled data, showed promising results in predicting loan defaulters, with an accuracy of 0.71 and AUC ROC of 0.8482. Homecredit can use this model to assess credit risk and make informed lending decisions. As they continuously generate historical data, the model can be tuned regularly to stay up-to-date with changing borrower behaviors. Furthermore, with the XGB model's ability to handle large datasets and evolving business requirements, Homecredit can easily incorporate additional predictors to improve predictive performance. Leveraging the model's accuracy and robustness, Homecredit can optimize their loan approval process, minimize credit losses, and enhance overall lending practices.

### My Contribution
In this group project, I Worked on data loading, data cleaning, outliers identification and removal, data files merger, encoding and normalization by using google colab with python. By using raw as well as normalised data, I have developed logistic regression model and randomforest model with different features and feature interactions

### The business value of the solution.
The proposed XGBoost (XGB) model for predicting loan defaults holds immense business value for Homecredit. Currently, Homecredit experiences losses of approximately $13.85 billion, which accounts for about 7.52% of the total approved loan amount of $184.208 billion. By implementing the XGB model, Homecredit can accurately predict 63.5% of these defaulters and potentially save an impressive amount of $8.8 billion. With the ability to fine-tune the model by incorporating additional predictors, Homecredit can further increase their savings and improve the effectiveness and sustainability of their business model. This enhanced capability enables Homecredit to extend its services to more people while maintaining a robust and efficient lending process.

### Difficulties we encountered along the way.
Developing a model to predict loan defaults was both challenging and a valuable learning experience. Despite achieving good accuracy in predicting likely defaulters, we encountered several hurdles along the way. Firstly, the dataset's vast size required considerable time to understand, and its data quality was compromised by numerous missing values and outliers. Secondly, the data imbalance concerning the target variable posed difficulties during exploratory data analysis. Additionally, feature engineering proved challenging due to significant variability in the fields. Furthermore, trying different models was time-consuming, and we had to address overfitting and underfitting issues with each model. Despite these challenges, we successfully developed a high-performing model by carefully addressing these concerns..

### learnings from the project
The loan default prediction model provided valuable learnings in handling complex datasets, addressing class imbalance, and conducting effective feature engineering. We gained expertise in evaluating models using relevant metrics and mitigating overfitting and underfitting issues through fine-tuning. Additionally, the practical application of the model demonstrated its real-world impact on improving risk management strategies and generating substantial savings for the company. These insights will guide us in future projects, ensuring the accurate and effective application of predictive analytics to diverse business challenges across different industries.
