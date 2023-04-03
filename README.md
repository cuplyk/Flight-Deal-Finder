[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
#Flight Tracker

## 🛠️ Project Description
The Flight Tracker is a python project that tracks the cheapest flights available for different locations. The program takes data from a Google sheet that contains various locations and their lowest prices that we want to visit. Then, it feeds this data into a flight search API, which searches for the cheapest flights available in the next six months. When the program finds a flight that's lower than our predefined price, it sends the date and price via our Twilio SMS module to our mobile phone so that we can book it right there and then.

## ⚙️ Installation
1.Clone the repository to your local machine.
```bash
git clone https://github.com/username/repo-name.git
```
2.Navigate to the project directory.
```bash
cd repo-name
```
3.Install the required packages using pip.
```text
pip install -r requirements.txt
```
## 🌟 Configuration
Create a Google sheet that contains various locations and their lowest prices that you want to visit.
Set up a Google Cloud Platform project with the Google Sheets API enabled.
Create a service account for your project and download the JSON key file.
Share the Google sheet with the email address associated with the service account.
Set up a Twilio account and create a new project.
Copy the ACCOUNT_SID, AUTH_TOKEN, and Twilio phone number to your environment file.
Store the key file and environment file outside of the project directory to keep them secure.
Usage
Set up your environment by storing the necessary credentials in your environment file.
