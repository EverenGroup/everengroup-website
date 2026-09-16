EVEREN GROUP WEBSITE
Production upload package

Contact form:
The Contact form no longer opens the visitor's email application.
It submits the enquiry through FormSubmit's AJAX endpoint to info@everengroup.co.th.
Visitors remain on the EVEREN website after submitting.

IMPORTANT FIRST-TIME ACTIVATION:
FormSubmit requires the destination email address to be confirmed the first time the form is used. Submit a test enquiry after deployment and confirm the activation email sent to info@everengroup.co.th. After activation, future website enquiries will be forwarded to that mailbox.

The form uses:
- Name
- Company
- Email
- Project Requirement
- Subject: EVEREN GROUP — Project Enquiry
- Table email template
- Honeypot field for basic bot filtering

No visitor-side mailto action is used by the Contact form.

Deployment:
Upload index.html to the website root. The page is self-contained and does not require an assets folder.
