# Loan Prediction 
This python webapp is developed to check the probability of loan applied by the user will be approved or not based on of the input parameters.
The app is built with the help of flask and deployed in cloud using Heroku.

# Dataset and Model Creation
The dataset contains the following columns:
![image](https://user-images.githubusercontent.com/76935226/148782436-a1872c35-eaca-40bf-a6ca-40c866dbcce1.png)

The image shows us the details that the user needs to input which will be used to predict the loan status.
The user needs to input the details according to the columns as mentioned in the dataset. There are various columns related to loan prediction raniging from residential area to co applicant income.
After the dataset is loaded the data is checked for null and other details. Various pre preocessing techniques are applied on the data and visualisations are used to draw inference from the dataset. We replace the null values with the mode and median of the data points wherever necessary. The categorical columns are encoded as we cannot use the data in original format for prediction.

After the data is ready for model building we use Randon Forest Algorithm and obtain the accuracy and metrics. In order to get optimised parameters for Random Forest we apply RandomizedSearchCV on Random Forest and obtain the best parameters for Random Forest. Then we will check the metrics and other  scores. The model is accurate about 85%.We save  the model as a pickle file and then the file will be used to predict the loan status.

# Deployment
Then GUI was designed by the help of HTML/CSS and bulit upon Flask Framework. The app was deployed in web with the help of Heroku.
![kisspng-flask-python-web-framework-bottle-microframework-django-5b3d0ba62504c0 3512153115307273341516](https://user-images.githubusercontent.com/76935226/148791161-269cad5c-7045-4faa-9dd9-c6e74d266df0.jpg)
![image](https://user-images.githubusercontent.com/76935226/140600298-11b355f2-f0f1-453a-a860-a984817597b5.png)
![image](https://user-images.githubusercontent.com/76935226/150634420-34207f18-c7c7-4694-b08b-e5d02dc78d41.png)
![image](https://user-images.githubusercontent.com/76935226/150634387-eabfa5dd-32d9-4167-925c-b55e3ddf8699.png)




You can check out the app:

https://loanpredictorwebapp.herokuapp.com/



![Screenshot (172)](https://user-images.githubusercontent.com/76935226/148762440-674d6a0e-4c4e-4097-b42d-66f22d344f0c.png)
![Screenshot (173)](https://user-images.githubusercontent.com/76935226/148762456-194aa04a-f5cb-4bfb-8455-015f83d7be9e.png)
![Screenshot (174)](https://user-images.githubusercontent.com/76935226/148762472-17379c80-935c-4def-9eba-dfb2955cdab1.png)
![Screenshot (175)](https://user-images.githubusercontent.com/76935226/148762490-94820b8d-351d-4a9f-a66f-5e015417823c.png)
