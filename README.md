# Spectrum

This project was made as a part of Spectrum Club Internship in our college.
In this project, We were provided with a data-set of students with their grades and other attributes associated with the students, 
like their age,gender,address,freetime,studytime and many others.
Our Job was to make a Machine Learning model that could predict the students marks upto an acceptable accuracy by discarding the factors
which don't play a vital role in the grades received.

As our Machine Learning Model only understandes numerical values, so we first converted all columns with binary data into 
numerical categories using Label Encoder. Then we used LinearRegression Model to predict the student marks using all attributes.

Finally in order to enhance the accuracy of our model, we checked how each attribute in the data affected the student Grades 
and tried to discard all irrelevant columns and predict the marks using only the most vital factors.
