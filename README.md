# TextToSpeech
I am going to create a website that will translate text into multiple languages using Artificial Intelligence(AI). I'll use Flask framework for the Front end and Azure Cognitive Services(collection of AI services) for the Back end.
To get started writing our Flask application with Python, we need to set up our development environment.

Step 1: Creating the project directory,  We can create a project directory from a command or terminal.

For Windows :

md FlaskAiApp
cd FlaskAiApp

Step 2: Creating the Python virtual environment.

Python’s virtual environment isn’t necessarily as complex as it sounds. Instead of creating a virtual machine or container, create a virtual environment which  is a folder containing all the libraries we need to run our application, including the Python runtime itself. By using a virtual environment, we make our applications modular, allowing us to keep them separate from each other and avoid versioning issues.

For Windows :

# Create the environment
python -m venv venv

# Activate the environment
.\\venv\\scripts\\activate

Step 3: Installing Flask and other libraries
With our virtual environment created and activated, the library Flask that we need for our website can now be installed. We will install Flask by following a common convention to create the requirements.txt file. The requirements.txt file is not special in and of itself; it is a text file where we list the libraries required for our application. But the convention is typically used by developers, making it easier to manage applications where multiple libraries are dependent.

Return to the command prompt or terminal window and perform the installation by using pip to run the following command :-

pip install -r requirements.txt

Step 3: Installing Flask and other libraries
With our virtual environment created and activated, the library Flask that we need for our website can now be installed. We will install Flask by a convention to create the requirements.txt file. The requirements.txt file is not special in and of itself; it is a text file where we list the libraries required for my application. But the convention is typically used by developers, making it easier to manage applications where multiple libraries are dependent.

Step 4: Creating app.py
Usually, a file called app.py is an entry point for Flask applications. Create a file name app.py in the project directory. 

After creating app.py file add the following code :

from flask import Flask, render_template
  
app = Flask(__name__)

Step 5: Create the HTML template
Let us create the Jinja (the templating engine for Flask). First, create the folder name templates and create the index.html file inside the templates folder.

Thank You
