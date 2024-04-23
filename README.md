## Phishing Detection Using ML 

## Title
Phishing Detection Solutions Using Artificial Intelligence: A Comprehensive Analysis of Feature-Based Algorithms

## Overview
Detecting phishing attacks in real-time is a formidable challenge due to the ever-evolving tactics employed by cybercriminals to evade traditional security measures. To address this issue, Artificial Intelligence (AI) has emerged as a promising solution, harnessing its ability to analyze vast amounts of data, identify patterns, and make informed decisions without explicit programming. This project present a comprehensive analysis of various AI-driven feature-based algorithms for phishing detection.

## Working
Here are some points about how phishing detection using machine learning algorithms works based on the provided implementation:

1. Website URL Input: Phishing detection begins with the user providing a website URL as input.

2. Feature Extraction: The system extracts relevant features from the website. These features could include characteristics such as the presence of HTTPS, the length of the URL, the age of the domain, the presence of certain keywords, etc. These features are crucial for training the machine learning model to distinguish between safe and malicious websites.

3. Feature Reshaping: Once the features are extracted, they are reshaped into a suitable format for input into the machine learning model. In this case, the features are reshaped into a 1x32 vector, presumably containing 32 different features.

4. Machine Learning Algorithms: Various machine learning algorithms are employed to train a model using the extracted features. Common algorithms used for phishing detection include Random forest, Support Vector Machines (SVM), K-Nearest Neighbors (KNN), Gradient Boosting Classifier (GBC) and a custom ensemble Voting Classifier.

5. Prediction: After training the model, it is used to make predictions on new websites. The model analyzes the extracted features of the website and predicts whether it is safe or malicious.

6. Safety Check: If the prediction indicates that the website is safe, the system displays a message confirming that it is a safe website. However, if the prediction indicates that the website is malicious, the system raises a cautionary alert indicating that a malicious website has been detected.

7. Evaluation and Feedback Loop: The performance of the machine learning model is continuously evaluated using metrics such as accuracy, precision, recall, and F1-score. Feedback from users regarding the accuracy of predictions can be used to refine the model and improve its performance over time.


Overall, phishing detection using machine learning algorithms involves extracting relevant features from website URLs, training a model to classify websites as safe or malicious based on these features, and using the model to make predictions in real-time to protect users from potential phishing attacks.

## Presentation
Here is the pdf for you all to refer:

[Phishing Detection using ML Algorithms.pdf](https://github.com/Hack3r1234/Phishing-Detection-Using-ML/blob/main/Phishing%20Detection.pdf)

## Dataset Collection
Dataset are collected from different sites such as PhishTank, OpenPhish, Kaggle and many more. So for reduction of overall time complexity of the model the urls are converted into binary.

[Phishing.csv](https://github.com/Hack3r1234/Phishing-Detection-Using-ML/blob/main/phishing.csv), [Phishing Dataset](https://prod-dcd-datasets-cache-zipfiles.s3.eu-west-1.amazonaws.com/n96ncsr5g4-1.zip), [Phish Tank](https://phishtank.org/), [OpenPhish](https://openphish.com/)

## Future Work
This project can be further be extended to make web browser plugin or extension or it can even launched as a product.

## Conclusion
This project contributes to the growing body of knowledge on AI-driven phishing detection and provides a foundation for future developments in the field of cybersecurity. Our work aims to empower individuals, organizations, and security professionals with advanced tools to safeguard against the ever-present threat of phishing attacks and protect the integrity and privacy of sensitive information.


[![Twitter](https://img.shields.io/twitter/follow/DhruvPatel?style=social)](https://x.com/Dhruv0x01/)
[![Linkedin](https://img.shields.io/badge/-dhruvpatel-blue?style=flat-square&logo=linkedin&logoColor=white&link=https://linkedin.com/in/dhruv-patel07b163214)](https://linkedin.com/in/dhruv-patel07b163214/)
[![Blogspot](https://img.shields.io/badge/-Dhruv%20Patel-red?style=flat-square&logo=blogger&logoColor=black)](https://spywar364.blogspot.com/)
