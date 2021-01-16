# Cyber Security
Due to the rapid advancement of modern computers and network infrastructure and our dependence on the Internet and its services which are increasing, web applications which are accessed through web browsers have become a primary target for cyber criminals. As per a report released by Symantec in 2016, about 430 million unique pieces of malware were discovered showing a growth of 36% against the year 2014. Cyber criminals use the malicious code and malicious URLs to attack individuals and organizations. The sole purpose of such attacks is for personal, financial, and political gains through damaging or disrupting normal operation of computer and systems, performing phishing attacks, displaying unwanted advertisements, and extorting money. Thus detection of such malicious code attacks becomes a top-most security challenge.

![enter image description here](https://www.greycampus.com/rails/active_storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBcDRLIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--ec75d64105a61bf310967a2f2207e68fd07440df/51947687_135925780777077_7429057953262469120_n.jpg)

Researchers recently have enlisted machine learning in the detection of malware. The advantage of using machine learning is that it can determine whether a code or a file is malicious or not in a very small time without the need of isolating it in a sandbox to perform the analysis. Machine Learning is able to detect previously unknown malware with predictive capabilities and especially useful for the detection of increasingly polymorphic nature of malware. To perform the classification of a benign and a malicious code, machine learning classifiers are used in detection through learning from patterns.
## Outline

 - The way hackers attack keeps on changing constantly and that's where Machine Learning comes into the picture.
 - In this data we will find field "isSafe" which basically tells if the request is safe or not for the app. We have looked at fields in each request and have marked a request as not safe if any of the fields contain malicious input from the user in to perform owasp top 10 attacks. Therefore, If value of isSafe is False, it means the request should be blocked.
 - The main goal is to show how we could design a Machine Learning Classifier which can identify if the request is safe or not.
 Outlines are summarized as below:
 
1.  EDA (Exploratory data analysis)
2.  Feature Extraction
3.  Data Preprocessing
4. Building the Classification Model
5.  Scoring & Metrics
6. Comparison of ML Model


[Link for Jupyter Notebook](https://github.com/nehahemane/Cyber_Security/blob/main/Cyber_Security.ipynb)







