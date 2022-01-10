# Loan Prediction 
This webapp is developed to check  the probability of loan applied by the user will be approved or not based on of the input parameters.
The app is built with the help of flask and deployed in cloud using Heroku.

# Dataset and Model Creation

![image](https://user-images.githubusercontent.com/76935226/148782436-a1872c35-eaca-40bf-a6ca-40c866dbcce1.png)

The image shows us the details that the user needs to input which will be used to predict the loan status. After the dataset is loaded the data is checked for null and other details. Various pre preocessing techniques are applied on the data and visualisations are used to draw inference from the dataset. We replace the null values with the mode and median of the data points wherever necessary. 

After the data is ready for model building we use Randon Forest Algorithm and obtain the accuracy and metrics. In order to get optimised parameters for Random Forest we apply RandomizedSearchCV on Random Forest and obtain the best parameters for Random Forest. Then we will check the metrics and other cv score. We save  the model as a pickle file and then the file will be used to predict the loan status.

# Deployment
Then GUI was designed by the help of HTML/CSS and bulit upon Flask Framework. The app was deployed in web with the help of Heroku.
![kisspng-flask-python-web-framework-bottle-microframework-django-5b3d0ba62504c0 3512153115307273341516](https://user-images.githubusercontent.com/76935226/148791161-269cad5c-7045-4faa-9dd9-c6e74d266df0.jpg)
![140600193-88639597-52de-4dce-ba6a-06b80cbe94f2](https://user-images.githubusercontent.com/76935226/148791351-6a457ada-8172-48ab-a24e-b3aa86649920.png)

![image](https://user-images.githubusercontent.com/76935226/148791618-6ad1302b-0c82-49d3-b59c-753ef6a02157.png)


You can check out the app:
https://loanpredictorwebapp.herokuapp.com/



![Screenshot (172)](https://user-images.githubusercontent.com/76935226/148762440-674d6a0e-4c4e-4097-b42d-66f22d344f0c.png)
![Screenshot (173)](https://user-images.githubusercontent.com/76935226/148762456-194aa04a-f5cb-4bfb-8455-015f83d7be9e.png)
![Screenshot (174)](https://user-images.githubusercontent.com/76935226/148762472-17379c80-935c-4def-9eba-dfb2955cdab1.png)
![Screenshot (175)](https://user-images.githubusercontent.com/76935226/148762490-94820b8d-351d-4a9f-a66f-5e015417823c.png)
