- create a new work flow in n8n
- Trigger: The workflow starts when the "Execute workflow" button is clicked.
- Get Data: The next step involves retrieving data from a specific Google Sheet with the "Get row(s) in sheet" action.
- Conditional Check: An If condition is used to check a specific condition (likely based on the data retrieved).
- True Path: If the condition is true, a row is appended to "Append row in sheet" (likely one sheet).
- False Path: If the condition is false, a different row is appended to "Append row in sheet1" (likely another sheet).
## ScreenShot:
<img width="1904" height="987" alt="Screenshot 2025-11-23 105515" src="https://github.com/user-attachments/assets/f950bb35-5ff3-47fc-9df3-08f8422ee3aa" />
