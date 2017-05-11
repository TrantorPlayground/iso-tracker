# iso-tracker
----------------------------------
To interact with Google drive you need to download client_secret.json file and add it to src folder. To generate client_secret.json file follow the steps below:

#Use "https://console.developers.google.com/start/api?id=drive" to create or select a project in the Google Developers Console and automatically turn on the API. Click Continue, then Go to credentials.
#On the Add credentials to your project page, click the Cancel button.
#At the top of the page, select the OAuth consent screen tab. Select an Email address, enter a Product name if not already set, and click the Save button.
#Select the Credentials tab, click the Create credentials button and select OAuth client ID.
#Select the application type Other, enter the name "ISOTracker", and click the Create button.
#Click OK to dismiss the resulting dialog.
#Click the file_download (Download JSON) button to the right of the client ID.
#Move this file to your working directory and rename it client_secret.json.
-----------------------------------
You also need to create database named as "isotracker".
