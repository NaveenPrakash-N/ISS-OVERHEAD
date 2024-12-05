# **ISS Tracker**

This Python application tracks the International Space Station (ISS) and sends an email notification when it is overhead in the user's location at night. The program uses the Open Notify API to track the ISS's current position and the Sunrise-Sunset API to check if it's nighttime.

## Features:

* Tracks ISS position
* Checks for night time
* Sends an email notification when ISS is overhead at night

## Requirements:

* Python 3.x
* requests library
* smtplib
* Setup:
* Clone the repository.
* Install dependencies using pip install -r requirements.txt.
* Set up the .env file for sensitive information (email and password).
* Run the script.
