#EMPLOYEE CHURN PREDICTION
In this project,I have predicted the Employee Churn.
Here I have predicted who is going to leave the company.I have trained a model in Azure machine learning which predicts the probablity of Employee Churn .
I have predicted churn in terms of probability and determined what factors made Employee leave his/her job.

STEPS:
I have downloaded the HR Dataset from Kaggle and imported it to my azure ml platform.
In that file I have selected some columns using 'select column in dataset' component.
Using 'Edit Metadata' component I have converted the string columns into categorical feature.
Then I have splited the data into training and testing data.
For this I used 20% of my data as testing data.
Then I implemented Two class decision forest to predict who will leave the company.
I have trained the model using'Train model'component and to find accuracy I have used 'Score model' component 
Then I evaluated and have Run the model.


![Screenshot (292)](https://user-images.githubusercontent.com/70439471/166973964-b77bad5e-5bfb-41b4-9421-7d178c4d5c9c.png)
![Screenshot (293)](https://user-images.githubusercontent.com/70439471/166973969-1ab284cf-dcb4-4671-bd8e-3700a33af1c9.png)
![Screenshot (294)](https://user-images.githubusercontent.com/70439471/166973979-024c2fc1-47d0-48a6-b02c-7893c6e6f090.png)
![Screenshot (295)](https://user-images.githubusercontent.com/70439471/166973982-1175c509-01e1-436d-8c9d-159c1b684a28.png)
![Screenshot (295)](https://user-images.githubusercontent.com/70439471/166973987-1d50c5de-9636-44fb-8770-344ac20b5555.png)
