## Experiment Tracking

install necessary packages like mlflow, xgboost, hyperopts etc.

to set the backend of mlflow we need a database

for that run the following to the terminal : mlflow ui --backend-store-uri sqlite:///mlflow.db

you can see the ui here : http://127.0.0.1:5000/



mlflow.set_tracking_uri("sqlite:///mlflow.db")

mlflow.set_experiment("exp-1")

![alt text](image.png)

![alt text](image-1.png)

![alt text](image-2.png)

let this model worked best in terms of size, time, rmse

![alt text](image-3.png)

thwn we can register the model

