# Text Classification With 4 Models & Ensemble
Participating in SATRIA DATA Competition (Statistics Ria and Data Science Festival), which is a manifestation of the support from the Ministry of Education, Culture, Research, and Technology for the advancement of statistical and data science knowledge. This project goes through several stages such as: data preparation (handling missing value & duplicate value), stopwords & remove unwanted words, data cleaning, feature extraction, model development, model evaluation, model comparison, conclusion.
#

**Machine Learning algorithms used:**<br>
1. Support Vector Machine (Scikit-learn)<br>
2. Naive Bayes (Scikit-learn)<br>
3. Random Forest (Scikit-learn)<br>
4. Logistic Regression (Scikit-learn)<br>
5. Ensemble SVM, Logistic Regression, Random Forest (Scikit-learn)<br>

## Data Cleaning
<br>
<strong>Before Preprocessing:</strong> <br>
plot : a rich psychiatrist with a great home life gets his cute daughter kidnapped by some bad guys who want him to extract some information from the mind of one of his nutty patients . \nof course , the patient is not cooperative and the doctor only has a few hours to comply with their demands , before they kill his daughter . \npretty good premise , no ? <br> <br>

<strong>After Preprocessing :</strong> <br>
plot rich psychiatrist great home life gets cute daughter kidnapped bad guys want extract information mind one nutty patients course patient cooperative doctor hours comply demands kill daughter
pretty good premise
<br> <br>
**Summary** <br>
Considering the accuracy of the five text classification models, it is recommended to use the Support Vector Machines (SVM) model due to its highest accuracy rate of 0.84.
<br>
|No|Model|Accuracy|
|--|---|---|
|1|SVM|0.84|
|2|Ensemble|0.84|
|3|Logistic Regression|0.83|
|4|Naive Bayes|0.82|
|5| Random Forest|0.76|



