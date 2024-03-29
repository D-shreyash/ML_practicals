# ML_practicals
<h2 style="font:bold">Following are problem statement for the practicals</h2>
1. Data preparation:
Download heart dataset from following link.
https://www.kaggle.com/zhaoyingzhu/heartcsv
Perform following operation on given dataset.
a) Find Shape of Data
b) Find Missing Values
c) Find data type of each column
d) Finding out Zero's
e) Find Mean age of patients
f) Now extract only Age, Sex, ChestPain, RestBP, Chol. Randomly divide dataset in training
(75%) and testing (25%).
Through the diagnosis test I predicted 100 report as COVID positive, but only 45 of those were
actually positive. Total 50 people in my sample were actually COVID positive. I have total 500
samples.
Create confusion matrix based on above data and find
I. Accuracy
II. Precision
III. Recall
IV. F-1 score
<br/>
<br/>
2. Assignment on Regression technique
Download temperature data from below link. https://www.kaggle.com/venky73/temperatures-
of-india?select=temperatures.csv
This data consists of temperatures of INDIA averaging the temperatures of all places month
wise. Temperatures values are recorded in CELSIUS
a. Apply Linear Regression using suitable library function and predict the Month-wisetemperature.
b. Assess the performance of regression models using MSE, MAE and R-Square metrics
c. Visualize simple regression model.
<br/>
<br/>
3. Assignment on Classification technique
Every year many students give the GRE exam to get admission in foreign Universities. The data
set contains GRE Scores (out of 340), TOEFL Scores (out of 120), University Rating (out of 5),
Statement of Purpose strength (out of 5), Letter of Recommendation strength (out of 5),
Undergraduate GPA (out of 10), Research Experience (0=no, 1=yes), Admitted (0=no, 1=yes).
Admitted is the target variable.
Data Set Available on kaggle (The last column of the dataset needs to be changed to 0 or 1)Data
Set : https://www.kaggle.com/mohansacharya/graduate-admissions
The counselor of the firm is supposed check whether the student will get an admission or not
based on his/her GRE score and Academic Score. So to help the counselor to take appropriate
decisions build a machine learning model classifier using Decision tree to predict whether a
student will get admission or not.
Apply Data pre-processing (Label Encoding, Data Transformation….) techniques if
necessary.
Perform data-preparation (Train-Test Split)
C. Apply Machine Learning Algorithm
D. Evaluate Model.
<br/>
<br/>
4. Assignment on Improving Performance of Classifier Models
A SMS unsolicited mail (every now and then known as cell smartphone junk mail) is any junk message
brought to a cellular phone as textual content messaging via the Short Message Service (SMS). Use
probabilistic approach (Naive Bayes Classifier / Bayesian Network) to implement SMS Spam Filtering
system. SMS messages are categorized as SPAM or HAM using features like length of message, word
depend, unique keywords etc.
Download Data -Set from : http://archive.ics.uci.edu/ml/datasets/sms+spam+collection
This dataset is composed by just one text file, where each line has the correct class followed by
the raw message.
a. Apply Data pre-processing (Label Encoding, Data Transformation….) techniques if
necessary
b. Perform data-preparation (Train-Test Split)
c. Apply at least two Machine Learning Algorithms and Evaluate Models
d. Apply Cross-Validation and Evaluate Models and compare performance.
e. Apply Hyper parameter tuning and evaluate models and compare performance.
<br/>
<br/>
5. Assignment on Clustering Techniques
Download the following customer dataset from below link:
Data Set: https://www.kaggle.com/shwetabh123/mall-customers
This dataset gives the data of Income and money spent by the customers visiting a Shopping Mall.
The data set contains Customer ID, Gender, Age, Annual Income, Spending Score. Therefore, as
a mall owner you need to find the group of people who are the profitable customers for the mall
owner. Apply at least two clustering algorithms (based on Spending Score) to find the group of
customers.
a. Apply Data pre-processing (Label Encoding , Data Transformation….) techniques if
necessary.
b. Perform data-preparation( Train-Test Split)
Curriculum for Third Year of Information Technology (2019 Course), Savitribai Phule Pune University
TE (Information Technology) Syllabus (2019 Course) 42
c. Apply Machine Learning Algorithm
d. Evaluate Model.
e. Apply Cross-Validation and Evaluate Model
<br/>
<br/>
6. Assignment on Association Rule Learning
Download Market Basket Optimization dataset from below link.
Data Set: https://www.kaggle.com/hemanthkumar05/market-basket-optimization
This dataset comprises the list of transactions of a retail company over the period of one week. It
contains a total of 7501 transaction records where each record consists of the list of items sold in
one transaction. Using this record of transactions and items in each transaction, find the
association rules between items.
There is no header in the dataset and the first row contains the first transaction, so mentioned
header = None here while loading dataset.
a. Follow following steps :
b. Data Preprocessing
c. Generate the list of transactions from the dataset
d. Train Apriori algorithm on the dataset
e. Visualize the list of rules
F. Generated rules depend on the values of hyper parameters. By increasing the
minimum confidence value and find the rules accordingly
<br/>
<br/>
7. Assignment on Multilayer Neural Network Model
Download the dataset of National Institute of Diabetes and Digestive and Kidney Diseases from
below link :
Data Set: https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-
diabetes.data.csv
The dataset is has total 9 attributes where the last attribute is “Class attribute” having values 0
and 1. (1=”Positive for Diabetes”, 0=”Negative”)
a. Load the dataset in the program. Define the ANN Model with Keras. Define at least two
hidden layers. Specify the ReLU function as activation function for the hidden layer and
Sigmoid for the output layer.
b. Compile the model with necessary parameters. Set the number of epochs and batch size
and fit the model.
c. Evaluate the performance of the model for different values of epochs and batch sizes.
d. Evaluate model performance using different activation functions Visualize the model using
ANN Visualizer.
