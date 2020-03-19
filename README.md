# Property Maintenance Fine Prediction

The Michigan Data Science Team (MDST) and the Michigan Student Symposium for Interdisciplinary Statistical Sciences (MSSISS) have partnered with the City of Detroit to help solve one of the most pressing problems facing Detroit - blight. Every year, Detroit issues millions of dollars in fines to residents that fail to maintain their property (called blight violations), and every year, many of these fines remain unpaid. Enforcing unpaid blight fines is a costly and tedious process, so the city wants to know: how can we increase blight ticket compliance?

The first step in answering this question is understanding when and why a resident might fail to comply with a blight ticket. This is where predictive modeling comes in. In the prediction task - **predict whether a given blight ticket will be paid on time**. 

All data for this competition has been provided to us through the Detroit Open Data Portal. This resource will be crucial throughout the task completion

#### Additional resources to take a look at are:
Building Permits
Trades Permits
Improve Detroit: Submitted Issues
DPD: Citizen Complaints
Parcel Map

The evaluation metric for used for this task is the Area Under the Receiver Operating Characteristic (AUROC). The True Positive Rate (TPR) and False Positive Rate (FPR) of my predictions will be determined by the classification performance when the probability is thresholded at different values. The threshold is varied from 0 to 1, forming the ROC (tpr vs. fpr) curve.
