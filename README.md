# IBMPlasmaDonor

# Plasma Donor Application
This is a web application that connects plasma donors and recipients in India. It is developed using Python Flask framework and IBM Cloud services. It is part of the Naan Mudhalvan Project, which aims to create social impact through technology.

## Features
Users can register as plasma donors or recipients by providing their personal and medical details.
Users can search for plasma donors or recipients based on their location, blood group, and COVID-19 status.
Users can contact each other through email or phone to arrange for plasma donation or transfusion.
Users can view and edit their profile and donation history.
Users can rate and review their plasma donation or transfusion experience.

## Installation
To run this application locally, you need to have Python 3.6 or higher and pip installed on your system. You also need to have an IBM Cloud account and create the following services:

IBM Cloudant: A fully managed NoSQL database service that stores and queries the user data.
IBM Watson Assistant: A conversational AI service that provides a chatbot interface for the application.
IBM App ID: An authentication and authorization service that secures the application and manages user roles.
To install this application, follow these steps:

Clone this repository to your local machine using the command:

[git clone https://github.com/naan-mudhalvan/plasma-donor-app.git](https://github.com/rakeshprasanna/IBMPlasmaDonor.git)

Navigate to the project directory and create a virtual environment using the command:

cd plasma-donor-app
python -m venv venv

Activate the virtual environment using the command:

venv\Scripts\activate

Install the required dependencies using the command:

pip install -r requirements.txt

Create a .env file in the project directory and add the following environment variables with your IBM Cloud service credentials:

CLOUDANT_URL=<your cloudant url>
CLOUDANT_API_KEY=<your cloudant api key>
CLOUDANT_DB_NAME=<your cloudant database name>
ASSISTANT_API_KEY=<your watson assistant api key>
ASSISTANT_URL=<your watson assistant url>
ASSISTANT_ID=<your watson assistant id>
APP_ID_TENANT_ID=<your app id tenant id>
APP_ID_CLIENT_ID=<your app id client id>
APP_ID_SECRET=<your app id secret>
APP_ID_OAUTH_SERVER_URL=<your app id oauth server url>
APP_ID_REDIRECT_URI=<your app id redirect uri>

Run the application using the command:

python app.py

Open your browser and go to http://localhost:5000 to access the application.

## Usage
To use this application, you need to register as a plasma donor or recipient by filling out a form with your personal and medical details. You will receive a verification email with a link to activate your account. Once you activate your account, you can log in to the application and access the following features:

Dashboard: You can view your profile and donation history, and edit your details if needed.
Search: You can search for plasma donors or recipients based on your location, blood group, and COVID-19 status. You can also filter and sort the results by distance, availability, and rating.
Contact: You can contact the plasma donors or recipients by clicking on their name and sending them an email or calling them on their phone. You can also view their profile and rating before contacting them.
Chatbot: You can interact with the chatbot by clicking on the chat icon at the bottom right corner of the screen. The chatbot can answer your queries about plasma donation or transfusion, and provide you with useful information and resources.

## Contribution
This application is open source and welcomes contributions from anyone who wants to improve it. If you want to contribute to this project, please follow these steps:

Fork this repository to your GitHub account.
Create a new branch for your feature or bug fix.
Make your changes and commit them with a descriptive message.
Push your branch to your forked repository.
Create a pull request to the main repository with a clear description of your changes.
Wait for your pull request to be reviewed and merged.
