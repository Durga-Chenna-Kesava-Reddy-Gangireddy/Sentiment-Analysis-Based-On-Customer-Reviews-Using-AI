# **Reference-Model-For-Sentiment-Analysis-Based-On-Customer-Reviews-Using-AI**
## **Predicting Restaurant Review Sentiment or Customer Feedback**

<img src="![image](https://github.com/user-attachments/assets/b5e36f7c-145d-4cbb-a377-4cd780463a44)
" width="600">

## **Understanding The Project**
---
### **The Dataset**
***
![Dataset](https://github.com/manthanpatel98/Restaurant-Review-Sentiment-Analysis/blob/master/README-Resources/Screenshot%20(96).png)

---
## **Overview**
* Dataset has **10000 rows** and **8 columns**.
* We have to predict whether a review is **"Positive"** or **"Negative"**.
* **PortStemmer** method has been used for **Stemming**.
* I have also tried **WordEmbedding** with **LSTM**.
* I have applied many different algorithms **LSTM**, **Bi-Directional LSTM**, **RandomForestClassifier**, **MultinomialNB**, **SVM** and **KNN**.

---
## **Details**
* From this Dataset, To Perform NLP Project, I decided to take **"Review"** and **"Rating columns"**.
* Later After cleaning the columns, I converted **"Rating"** Column, which is actually a numerical column, into the column that has two labels **"Positive"** and **"Negative"**.
* I considered Rating **Above 3** as **"Positive"** and **Below 3** as **"Negative"**.
* To understand detailed Project approach, check my [**Restaurant-Review.ipynb**](https://github.com/manthanpatel98/Restaurant-Review-Sentiment-Analysis/blob/master/Restaurant-Review.ipynb) or [**model.py**](https://github.com/manthanpatel98/Restaurant-Review-Sentiment-Analysis/blob/master/model.py)
* This project has around **10,000** Reviews, so for CountVectorizer, **max_features=9000** gave best results after trying values like 2500, 5000, 7500... Which I think is most important thing to achive higher accuracy value. 
***
### **Applied Algorithms & Their Accuracy**
***
| Algorithm | Accuracy |
| ---    | ---    |
| Random Forest | 89.28% |
| MultinomialNB | 90.84% |
| SVM | 76.68% |
| KNN | 81.44% |
| LSTM | 87.56% |
| Bi-Directional LSTM | 89.36% |
* After Checking Accuracy for these Foure Algorithms, I decided to use **MultinomialNB** in **Web App**.
"# Sentiment-Analysis-Based-On-Customer-Reviews-Using-AI" 
