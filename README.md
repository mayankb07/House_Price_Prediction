# House-Price-Prediction

  # Description:
   Creating a website which can be used to predict the house prices using different attributes like location, size, total_sqft, BHK etc. We will be using the data set from kaggle and build a machine learning model using linear regression and sklearn. Flask server will be used for serving the http requests, also at the end we need to deploy the application to AWS EC2
   
   Data set used : https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data
   
   ![image](https://user-images.githubusercontent.com/85644097/146944860-aad7c82d-1174-459d-adde-cf780b91cc03.png)

   
  
  # The key tasks of project includes:
  * Peformed data cleaning on various atrributes and applied aggregate function
  * Feature engineering on data set for extracting additional details which can help in better results
  * Analyzed and removed various outliers from the data sets which may impact result
  * Applied techniques like K fold validation, GridSearchCV and improved model score from 83% to 86%
  * Exported the model in pickle file, used Nginx server and Python flask that used the saved model for serving http requests.
  * Build a website which take parameters like Area, BHK, location and provide result using HTML, CSS, JS etc
  * Created an AWS EC2 instance and deployed the application 
    
