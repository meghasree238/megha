Workflow 1: Form submission → Save in Google Sheets
Step 1: Create Trigger
Add the trigger “On form submission1.”
This trigger activates whenever a user submits the form.

Step 2: Add Google Sheets Action
Click + next to the trigger.
Select Google Sheets → Append row in sheet.
Connect your Google account.

Step 3: Configure Sheet Details
Select the spreadsheet file.
Choose the worksheet name.
Map the form fields (Name, Email, etc.) to the sheet columns.

Step 4: Save and Test
Submit the form once.
The submitted data automatically appears as a new row in Google Sheets.

Workflow 2: New row added → Send Gmail message
Step 1: Create Google Sheets Trigger
Add Google Sheets Trigger – rowAdded.
Select the same spreadsheet and worksheet.

Step 2: Add Gmail Action
Click + and select Gmail → Send a message.
Enter:
To: Recipient email
Subject: “New Form Submission”
Message: Notification text including row details.

Step 3: Save and Test
Add a new row in the sheet.
The system automatically sends an email notification.

![1000091728](https://github.com/user-attachments/assets/dde5d40b-ac9b-4e27-a63a-93ebe7c79db9)
