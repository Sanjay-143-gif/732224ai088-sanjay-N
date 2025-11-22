- First, create a new workflow inside n8n.
- A form submission is used to trigger the first workflow.
- After the user submits the form, the submitted data is inserted as a new row into Google Sheets.
- When this new row is added, the Google Sheets Trigger automatically activates.
- The triggered workflow then uses the Gmail node to send an email, using the information stored in the newly added row.
* # screenshot
* <img width="888" height="496" alt="Screenshot 2025-11-21 121227" src="https://github.com/user-attachments/assets/ca6e23ce-ab3f-4d05-985d-491c4f13105f" />

