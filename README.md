# Automated-Certificate-Generator-Email-Sender
This project automates the creation and distribution of personalized certificates for students in the Career Pathways Program using Google Apps Script, Google Slides, Google Sheets, and Gmail. It was designed to save time and reduce errors when generating certificates for 100+ students, eliminating the need for manual copy-paste edits in Google Slides.

## **Technology Used**
- Google Apps Script (JavaScript-based)
- Google Sheets & Slides API
- Google Drive API

## **How It Works**
1. Prepare a Google Slides certificate template with placeholders:
   {{FirstName}}
   {{LastName}}
2. Add participant data (first name, last name, email) to a Google Sheet.
3. Highlight the rows you want to generate certificates for.
4. Run the script via the custom menu: Certificate Tools → Generate & Send Certificates.

The script will:
- Make a copy of the template for each participant
- Replace placeholders with their actual name
- Convert the slide to a PDF
- Email the certificate as an attachment
