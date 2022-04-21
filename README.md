# Simple Flask Web Application
Simple webapp created in Flask (and using a MySQL database) and tested for deployment using Docker. Created as part of the following Kodekloud corse: [Docker for the Absolute Beginner](https://kodekloud.com/courses/docker-for-the-absolute-beginner/)

The steps required to run/deploy the app are listed below.

## 1. Update apt Repos and Install apt Dependencies
```bash
apt update
apt install -y python3 python3-setuptools python3-dev build-essential python3-pip python3-mysqldb
```

## 2. Install Python dependencies
```bash
pip install flask
pip install flask-mysql
```

## 3. Configure Web Server
- Copy code for application
- Set up credentials and parameters for database

## 4. Initialize Web Server
Start the web server:
```bash
FLASK_APP=app.py flask run --host=0.0.0.0
```

## 5. Test Web App
Visit the following URL in a browser:
```
http://<IP>:5000                                  # The welcome site of the app.
htpp://<IP>:5000/how%20are%20you                  # Page shows "I am good, how are you?"
```
