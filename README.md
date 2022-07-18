# Cement Strength Prediction

* To build a regression model to predict the concrete compressive strength based on the different features in the training data. 
* We will be deploying the model to the Pivotal Web Services Platform. 
* This is a workflow diagram for the prediction of using the trained model.
* Use `pip install -r requirements.txt` to get all the dependencies it consists of all the packages that you need to deploy the app in the cloud. 
* main.py is the entry point of our application, where the flask server starts. 
![image](https://user-images.githubusercontent.com/95335025/179607307-84e99ff3-7cc2-4f1f-91e1-35bd86cf6a9f.png)
* This is the predictionFromModel.py file where the predictions take place based on the data we are giving input to the model.

![image](https://user-images.githubusercontent.com/95335025/179607617-6cf1489d-4e4f-410c-9dc0-0656fa610c33.png)
* manifest.yml:- This file contains the instance configuration, app name, and build pack language.
![image](https://user-images.githubusercontent.com/95335025/179607776-3134894e-b0cb-4cfa-bd0e-f41a833227fe.png)
* Procfile :- It contains the entry point of the app.

* Visit the official website https://pivotal.io/platform.


![image](https://user-images.githubusercontent.com/95335025/179608036-685d767b-0a42-43bf-b8a9-0cfad3fb6c55.png)
* Click on the start trial button and the next interface will open. Then I will click on I’m ready to continue
![image](https://user-images.githubusercontent.com/95335025/179608098-aae75b2f-a470-4e4d-a687-3a0ef04543b4.png)
* Click on Download for Windows 64 bit, and then zip file will be downloaded. Keep it for future uses.
![image](https://user-images.githubusercontent.com/95335025/179608140-89f94e97-8f10-4538-b49c-f1f3e118cc81.png)
* Now click on Let’s Keep Going
![image](https://user-images.githubusercontent.com/95335025/179608219-ec6136dc-5d2e-406c-aa2f-c1e021d6718a.png)
* Click on Create Your Account
![image](https://user-images.githubusercontent.com/95335025/179608326-7539667a-79d1-4fa7-8da3-6bc0f406b0b5.png)
* Click on Pivotal Web Services
 ![image](https://user-images.githubusercontent.com/95335025/179608386-032323a7-78ba-459b-8d8d-84d666a9d86a.png)
* Give any Org/project name
![image](https://user-images.githubusercontent.com/95335025/179608491-677169ea-e37d-404c-831d-1d8f6abee29a.png)
Now you are inside your Org, and by default, development space is created in your org. You can push your apps here.
The cloud signup process is done, and the setup is ready for us to push the app.

* Previously you have downloaded the CLI.zip file. Unzip the file and install the .exe file with admin rights.
After a successful installation, you can verify by opening your CMD and type cf. 
Then you will get a screen which is shown below
![image](https://user-images.githubusercontent.com/95335025/179608600-1e3c9b03-7d24-49ad-b7da-ce343ab65dfb.png)
* If you see this screen in your CMD, the installation is successful.
Now type the command to login via cf-cli
cf login -a https://api.run.pivotal.io
Next, enter your email and password. Now you are ready to push your app.
Now let’s go to the app which we have built.
![image](https://user-images.githubusercontent.com/95335025/179608759-b0cf4ed2-dcca-4e54-8741-b26c943d3ab1.png)
* Navigate to the project folder after downloading from the given below link:-

* Then write cf push in the terminal.
* After the app is successfully deployed in the cloud, you will see the screen below with the route.
![image](https://user-images.githubusercontent.com/95335025/179608954-b61a53b4-1b7b-4243-8baa-0ee7dab98c9c.png)
Finally, the app is pushed in the cloud.
Lets Open Postman and see the result.
![image](https://user-images.githubusercontent.com/95335025/179609033-03908091-58be-45be-bec9-979ad0e5da2c.png)




