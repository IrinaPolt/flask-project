## Project Description:
Flask web application that features an authentication system. The application includes signup and login forms where users can enter their name, email and password. If the input is incorrect, the application displays an error message. Upon successful login, a "Logout" button provided. Clicking the "Logout" button redirects the user back to the login page.

## Clone and run

Clone the repository from GitHub:
```
git clone git@github.com:IrinaPolt/flask-project.git
```
Navigate to the project directory:

```
cd flask_app
```
Create a virtual environment (recommended but optional):
```
python -m venv venv
```
Activate the virtual environment:
On Windows:
```
venv\Scripts\activate
```
On macOS and Linux:
```
source venv/bin/activate
```
Install the required dependencies using pip:
```
pip install -r requirements.txt
```
Set up the environment variables:
```
export FLASK_APP=project
export FLASK_DEBUG=1 # or 0
```
Run the Flask application:
```
flask run
```
Open a web browser and navigate to http://127.0.0.1:5000 to access the login page.
