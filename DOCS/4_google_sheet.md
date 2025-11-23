- First, create a new workflow inside n8n.
- A form submission is used to trigger the first workflow.
- After the user submits the form, the submitted data is inserted as a new row into Google Sheets.
- When this new row is added, the Google Sheets Trigger automatically activates.
- The triggered workflow then uses the Gmail node to send an email, using the information stored in the newly added row.
## ScreenShot:
<img width="1919" height="994" alt="Screenshot 2025-11-23 104855" src="https://github.com/user-attachments/assets/55e50ec4-4ca9-4da4-9a38-55a5ff06167c" />
