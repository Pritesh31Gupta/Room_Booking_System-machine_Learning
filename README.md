This Project Is AI Room Booking System
Instruction
Download or Clone this repo on your local machine

Create your IBM Cloud Account at https://cloud.ibm.com/registration If you already have an IBM Cloud Account, login here https://cloud.ibm.com/login
Provision your IBM Watson Assistant at https://cloud.ibm.com/catalog/services/watson-assistant Name your IBM Watson Assistant service and Click on create.
Click on launch Watson Assitant to open the tool.
Then Click on "Create assistant" Button to create your IBM Watson Assistant.
Name your assistant. If you want, you can give description for ypur assistant.
Click on "Add an actions or dialog skill"
Go to "upload skill" tab and choose the skill-Room-Booking.json
We completed the chatbot. Let's set our IBM Cloud Function to send an email when someone sends a booking request. Go to https://cloud.ibm.com/functions/actions and Click on "Create" Button and click on "Action"
Prove a name for your Action. Leave "Enclosing Package" as default. And Choose python 3.7 as your runtime. Then Finally, Click on "Create".
You will see a Text area to enter your python code. Just copy the python from IBM_Cloud_Function.py and past it in the text area of IBM Cloud Funtion.
Now go to your Google Account Security at https://myaccount.google.com/security. Enable 2 step verification. Then Go to "App password" under "Signing in to Google".
Select "Mail" as app and "Other" as "Other" as device. Enter any name for your custom device. example: IBM Cloud Fumction
Copy the app password and back to our IBM Cloud Function. Enter the app password in the python program on 10 line.
Click on "Endponits" from the side bar of IBM Cloud Function Action Click on "Enable as Web Action" and Copy the URL.
Come Back to your IBM Watson Assistant. Go to "Option > Webhooks" from the side bar of your IBM Watson Assistant. Then past the URL (Note: Add .json at the end of the URL).
That's it. We have successfully developed our AI Room Booking Chatbot.