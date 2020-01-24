# Exp_Fraud_Complaint_Analysis
Set up an experiment to compare supervised to unsupervised (done by my colleague) Fraud-Complaint text analysis deploying BERT model. No doubt that the supervised learning was improved using the labeled data, the supervised model has better Precision and Recall (0.86, 0.91) on true positives (fraud cases) than the Unsupervised one (0.52 and 0.72 respectively).

![Image](https://github.com/Shahabks/Exp_Fraud_Complaint_Analysis/blob/master/wqawsqw.png)

### Note
Fraudulent activities are usually prosecuted, therefore fraudsters need to be creative and come up constantly with new ways of performing fraud. Furthermore, frauds are scarce (fortunately), and so we have few positive class patterns available for training. Because of these facts, it might make sense to build an unsupervised fraud detector. Using **only the training data**, create an anomaly detection model. one should also choose an error metric adequate for the problem, and tune the model parameters in order to optimize this error.

This model is s content analytical model that can be either given data sets of known fraudulent behavior/text and using machine learning algorithms can “learn” to recognize and flag suspicious claims, or given data sets and let the algorithms finds any patterns in the data sets. 

Raw Datasets (examples) https://surfdrive.surf.nl/files/index.php/s/m34LCElefSj6M8y

### Cost-sensitive learning 
classification can be used when the
“cost” of mislabelling one class is higher than that
of mislabelling other classes (Elkan, 2001; Kukar
et al., 1998). For example, the real cost to a bank
of miscategorising a large fraudulent transaction
as authentic is potentially higher than miscategorising (perhaps only temporarily) a valid transaction as fraudulent. Cost-sensitive learning tackles the issue of class imbalance by changing the
cost function of the model such that misclassification of training examples from the minority
class carries more weight and is thus more ‘expensive’. This is achieved by simply multiplying
the loss of each example by a certain factor. This
cost-sensitive learning technique takes misclassification costs into account during model training,
and does not modify the imbalanced data distribution directly.
