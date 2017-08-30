# About
#### Drug Selection for Treating High BP and CHolestrol patients - sample application takes inputs found to be primary predictors in drug selection for treating High BP and CHolestrol based heart problems and predicts the drug it believes to be the best choice for the patient.

# Prerequisites
#### Model available in \model subdirectory (Drug1n.str) has to be uploaded to the Watson Machine Learning instance using Dashboard (drag and drop). Make sure that uploaded model is named correctly (contextID=drug1N).
#### Drug1n.str --> drug1N

#### For reference please see screenshot below.

![alt text](https://github.com/irhms/Heartrate-/tree/master/public/img/drug_dashboard.jpg "Dashboard")

#### After successful models upload deployed application should provide scoring capability as shown below.

![alt text](https://github.com/irhms/Heartrate-/tree/master/public/img/heart_app.jpg  "Application")


# Deploying the HeartRate Health Statistics app in a Click
For a fast start, the app can be deployed to Bluemix by clicking the following button:

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/irhms/Heartrate-&appName=heartrate&branch=master)

Note that the application is fully functional only if bound to an instance of the *Watson Machine Learning* service, which must be done manually.
