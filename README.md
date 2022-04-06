# IDS721 Group-Final-Project Salary Predictor




## How to Run the App

1) Clone the repo
```bash
git@github.com:xzhnshng/IDS721-group-project.git
```
2) Create & enter python virtual environment
```bash
# first cd to the project directory
# create virtual environment
python -m venv env

# enter the virtual environment
source env/bin/activate
```

3) Setup - Install the required packages
```bash
make all
```
4) Train the model
```bash
python model.py
```
5) Run the application
```bash
python main.py
```

The dataset is from https://www.kaggle.com/datasets/anandhuh/population-data-china

# Containerization
```bash
# create image
docker build -t salary-predictor:latest .

# create and run container
docker run --rm -p 5000:5000 --name salary-predictor-app salary-predictor:latest
```
Now you can access service on http://127.0.0.1:5000/

## Set up on Cloud


## Set up Continuous Deployment (CD)



## Load Testing
