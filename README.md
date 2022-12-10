# googleSheetDB
Use google sheet as Database

Requirement:

You have to make a database using google sheets. The following functionalities should be there:

1. User enters name, mobile number through a webpage on front-end
2. On submitting his details, data should get recorded in google sheets.


Solution:
1. Created a blank google sheet with name and mobile number fields.
2. Created a basic html file containing a form with name and mobile number fields.
3. Inside code.gs of App Script, added scripts to read data from the request and append row to the google sheet. Need to provide the google sheet link to this script. Deployed the script as web app and pasted the web app link to the client side html script_url.
4. Tested with few inputs.
5. Deployed
