
# chuck-norris-app-engine
## A flask application that displays random chuck norris facts

### Prerequisites
* [Create a GCP Project](https://cloud.google.com/resource-manager/docs/creating-managing-projects)
* [Install the Google Cloud SDK](https://cloud.google.com/sdk/docs/install)

### Documents
* [Google App Engine (Python)](https://cloud.google.com/appengine/docs/standard/python3)
* [Chuck Norris API](https://api.chucknorris.io/)
* [Flask](https://flask.palletsprojects.com/en/1.1.x/):  Flask is a micro web framework written in Python
* [app.yaml](https://cloud.google.com/appengine/docs/standard/python3/config/appref): app.yaml configuration file

### Applications
* [Minimal flask application displaying random chuck norris facts](chuck-norris/)

### App Engine Folder structure
 * app.yaml
 * templates/
 * static/
 * `main.py`
 * requirements.txt

### Details
1. [`app.yaml`](https://cloud.google.com/appengine/docs/standard/python3/config/appref): Deployment descriptor for your application
1. `templates/`: This is where you’ll put the Jinja2 templates for your app.
1. `static/`: This directory contains the public CSS, JavaScript, images and other files that you want to make public via your app. 
1. `main.py`: Python file that has the application logic
1. `requirements.txt`: This file lists all of the Python packages that your app depends on. 

### Deploying the application to App Engine
Navigate to the directory and run the following command -> `gcloud app deploy`

### View the Web Application
`gcloud app browser`