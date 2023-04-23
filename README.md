# How to Run an App

### step 1: create a virtual environment in your PC and run each command in terminal

Windows:
1) Installing virtual environment:
> py -m pip install --user virtualenv

2) Create virtual environment:
> py -m venv env

3) Activate virtual environment:
> .\env\Scripts\activate

Mac OS:
1) Installing virtual environment:
> python3 -m pip install --user virtualenv

2) Create virtual environment:
> python3 -m venv env

3) Activate virtual environment:
> source env/bin/activate

### step 2: Installing all required Libraries
> pip install -r requirements.txt

### step 3: Running the app
> python run.py

### step 4: How to see the app
goto port localhost:5000/ in your browser for viewing app.

## Note:
if you want to deactivate virtual environment simply run
> deactivate

Whenever you install any new package in app please run this command
> pip freeze > requirements.txt


## Preview

#### Start(Home) Page:
![image](https://user-images.githubusercontent.com/104631814/233820195-a455fc7b-9740-4b1d-9aa5-4034ee7ecfe8.png)

#### Single Date Prediction:
![image](https://user-images.githubusercontent.com/104631814/233820225-7ce33904-f9f2-4657-a31a-dc68fe40351d.png)

#### Date Range Prediction:
![image](https://user-images.githubusercontent.com/104631814/233820250-56b2a2fd-9617-4b64-98bb-db43bcbc45ad.png)

#### Graph Section for analysis of Exchange Rate (USD to INR):
![image](https://user-images.githubusercontent.com/104631814/233820297-bd405114-ba53-428d-b797-0f51d5904cd3.png)
![image](https://user-images.githubusercontent.com/104631814/233820342-dadda325-8244-4bd2-a8ec-5d4a997ebd45.png)
