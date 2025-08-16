# Gmail Invoice PDF Reply Script (Google Apps Script)

This Google Apps Script:
1. Renames a Google Sheet temporarily
2. Exports a specific tab as PDF
3. Replies to a Gmail thread with the PDF attached
4. Restores the original sheet name

## Setup

1. Open [script.google.com](https://script.google.com/) and create a new project.
2. Paste the code from `renameAndReplyWithSheetPDF.gs`.
3. Replace:
   - `YOUR_SHEET_ID_HERE` with your Google Sheet ID
   - `YOUR_SHEET_NAME_HERE` with the target tab name
   - `YOUR_EMAIL_THREAD_ID_HERE` with the Gmail thread message ID
4. Run the script and authorize permissions.

## Notes
- Keep sensitive IDs private. Do not commit them to public GitHub.
- You can store these IDs in [Script Properties](https://developers.google.com/apps-script/guides/properties) instead of hardcoding.
- This script uses the Gmail and Spreadsheet services and requires authorization.

