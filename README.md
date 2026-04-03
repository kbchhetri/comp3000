# comp3000
Project comp3000 testing purposes
Anomaly Detection-Based Intrusion Detection System Using Machine Learning 
1. Abstract
Intrusion detection systems may be broadly divided into signature-based approaches and anomaly-based approaches.
2. Introduction. 
Detection of intrusion is an essential tool for delivering security and reliability in today’s computers. As we see the rise of digital technologies.
3. Background
The project is associated with network security, including various intrusion detection systems (IDS) and machine learning-based threat detection.
4.Anomalies detection based on machine Learning 
Network traffic anomalies are behaviors or data patterns that are markedly different from normal activity. Anomalies are important in intrusion detection systems because they frequently suggest cyber attacks, system abuse or unexpected behaviours
DDoS Attack. 
A Denial-of-Service (DoS) or Distributed Denial of Service (DDoS) attack may happen where the amount of traffic that is sent over a target system to cause it to become overwhelmed and unavailable for legitimate users
5. Dataset Description. 
The study works with public intrusion detection datasets — UNSW-NB15 and CICIDS2017. Both datasets have normal and malicious network packets and are extensively utilized in machine learning-based intrusion detection research. 

algorithms	UNSW-NB15	CICIDS2017
Navie Bayes	76	         98
KNN	85	                   99
SVM	83	                    99
Random Forest	87	            99
6 Project Management. 
This project was handled with a structured approach that utilized a Gantt chart with a risk management plan to structure the work and oversee the task and check the progress as the project progressed. 
6..1 Machine Learning Algorithms. 
6.1.1 Naive Bayes. 
Naive Bayes is a simple probabilistic classification algorithm based on Bayes’ theorem. It is fast and simple to implement assuming the features are independent of each other. 
6.1.2 K-Nearest Neighbours (KNN) 
The K-Nearest Neighbours (KNN) is a distance-based classification algorithm that classifies a novel data point with respect to the closest data points in the training set. 
6.1.3 Support Vector Machine (SVM).
 SVM (Support Vector Machine) is a supervised machine learning algorithm that helps to distinguish between classes by finding the best boundary
 6.1.4 Random Forest. 
Random Forest is an ensemble model combining several decision trees. Each tree makes its own prediction, and majority voting determines final predictions. 
7. Methodology:
This project follows a standard experimental methodology to make and compare machine learning models for intrusion detection
Histograms. Histograms were then used to interpret the data for the distribution of particular attributes. 
Boxplots. Boxplots were employed to compare the distribution of features in normal and at-tack classes. 
Correlation Heatmap. 
Correlation heatmap was employed to analyze the relationships between different features in the dataset.	
Principal Component Analysis (PCA). 
Principal Component Analysis (PCA) was utilized to narrow down the features while also plot-ting the data in a lower-dimensional way
7.6 Model Training and Testing. 
The 4 different machine learning algorithms used in this project include Naive Bayes, K-Nearest Neighbours (KNN), Support Vector Machine (SVM) and Random Forest. Training on network traffic was performed using a combination of normal and malicious models. 
7.7 Performance Evaluation. 
The model performance results are appraised following the established classification measures:
•	Accuracy – general accuracy of the predictions that are overall generated. 
•	Precision – the percentage of predicted attacks that are in fact attacks. 
•	Recall – number of actual attacks correctly detected. 
•	F1-score – the balance between precision and recall. 
•	 Confusion Matrix – shows:
8. Ethical, Legal, Social and Professional Issues

This paper has addressed ethical, legal, social and professional issues in the formation of a machine learning based intrusion detection system. It also has brought that the need to be ethical, legal, social and professional.
9. Prototype and Research. 
This research-oriented project was implemented based on an iterative approach, divided into phases and sprints.
10. Results and Discussion. 
The results obtained from using four machine learning techniques, namely: Naive Bayes, K-Nearest Neighbours (KNN), Support Vector Machine (SVM), Random Forest and others are provided here. On 2 intrusion detection datasets UNSW-NB15 and CICIDS2017. #
11. Conclusion. 
This project designed and verified a machine learning-based anomaly detection system for intrusion detection in the two most popular datasets used, UNSW-NB15 and CICIDS2017. The goal was to evaluate how good different kinds of machine learning algorithms could classify normal or malicious network traffic, and how to identify an appropriate model approach for intrusion detection.
