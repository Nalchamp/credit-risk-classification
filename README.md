# Credit-Risk-Classification

# Summary
Based on the results described above, following are some key summary points:

The random over sampled model seems to perform a better job as it has better accruacy score and balanced accuracy score compared to the model where logistic regression was performed on the oversampled data.

The random over sampled method also does a better job in the correct prediction of loans as it has higher recall scores especially for the high-risk loans 1 and an equally good job for the healthy loans 0. For any lending service company or credit grantor, the correct identification of a high-risk loan is much more important as it reduces the probabilty of defaultors by placing importance on correct analysis of their creditworthiness, thereby impacting the overall profitability of the company. The oversampled model does a better job in correct classification of the high-risk loanswhen they were actually positive by catching the incorrect labelling of high-risk loans as healthy.

Taking into consideration the above key factors, my recommendation will be to use the RandomOverSampler method to resmaple the data in this scenario based on the overweighting towards healthy loans and then perform the Logistic Regression. This method gives better accuracy and recall scores which are crucial decision metrics for a lending service company.
