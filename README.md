# Zoho-CRM-Google-Sheets-Integration
This project integrates Zoho CRM with Google Sheets using Zoho Flow to automate the transfer of contact information. When a new contact is created in Zoho CRM, their details are automatically synced with a Google Sheets document, reducing manual data entry and improving efficiency in managing contact data.
Goal:
Automate the synchronization of contact information between Zoho CRM and Google Sheets to streamline the data management process.

##Technologies & Tools Used
Zoho CRM – Customer Relationship Management platform.

Google Sheets – A cloud-based spreadsheet application.

Zoho Flow – A no-code platform to automate workflows between different apps and services.

Google Sheets API – Used to interact with Google Sheets programmatically (through Zoho Flow).

##Step-by-Step Instructions
1. Setting Up Zoho CRM
In Zoho CRM, I created fields to store contact information such as First Name, Last Name, Email, and Phone. This allowed me to structure the data consistently, ensuring all necessary information is captured for each contact.

2. Creating the Google Sheets Document
I created a Google Sheets document with columns to store the contact details. The columns I used were:

First Name
Last Name
Email

This sheet was set up to match the data fields in Zoho CRM for easy mapping.

3. Connecting Zoho Flow with Google Sheets
In Zoho Flow, I created a new flow to automate the process of transferring contact data from Zoho CRM to Google Sheets. The flow was triggered when a new contact was added to Zoho CRM.

Zoho CRM Trigger:

The flow was set to trigger whenever a new contact was created in Zoho CRM.

Google Sheets Action:

I chose the "Add Row" action in Google Sheets, where the contact information from Zoho CRM would be added to the sheet.

Mapping Fields:

I mapped the First Name, Last Name, Email, and Phone fields from Zoho CRM to the corresponding columns in the Google Sheet.

4. Testing the Integration
I tested the flow by adding a dummy contact to Zoho CRM. When the contact was created, the information was automatically populated into the Google Sheet, as expected. I did notice that the flow fired twice in some cases, which I resolved by adjusting the trigger settings.

5. Finalizing the Flow
Once I confirmed that the flow was functioning properly, I saved and finalized it. The flow now runs automatically whenever a new contact is added to Zoho CRM.

###Screenshots
Zoho CRM Trigger Configuration
![image](https://github.com/user-attachments/assets/51885865-b4cc-4893-a382-e03a0a81b15d)
this is the trigger setup in Zoho Flow, which activates the integration when a new contact is added to Zoho CRM


###Google Sheets Action Setup
![image](https://github.com/user-attachments/assets/e3a44082-03a7-4d04-82cf-f9fab1b1bd45)
![image](https://github.com/user-attachments/assets/7c58ae97-fa47-4b53-895d-81b6bd43ac9f)
This screenshot shows the action configuration, where contact details from Zoho CRM are mapped to the corresponding columns in Google Sheets
