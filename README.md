# Python-Code-For-Sending-Mail-Advertisment-Mail
The code sends promotional emails with personalized titles, messages, and embedded images using Gmail's SMTP server. It prompts the user for input and sends the email with an HTML content format.
# Features
- Sends promotional emails using Gmail's SMTP server.
- Allows customization of email title, message, and recipient.
- Creates HTML-formatted email content with CSS styling.
- Embeds an image in the email for visual appeal.
- Handles errors during the email sending process.
- Establishes a secure connection (TLS) to the SMTP server.
- Provides user prompts for inputting email details.
- Displays a success message when the email is sent successfully.
- Simplifies the process of sending personalized promotional emails.
# Usage
Import the necessary modules:

smtplib for establishing an SMTP connection and sending emails.
MIMEMultipart for creating the email message object with multiple parts.
MIMEText for creating the email content in various formats.
Define the send_email function that takes the email title, message, and recipient as parameters.

Set the sender's email and password in the sender_email and sender_password variables.

Create the email message object (email_message) and set the subject, sender, and recipient.

Create the HTML content of the email using a multi-line string with placeholders for the title and message.

Attach the HTML content to the email message object.

Attempt to send the email by establishing an SMTP connection with Gmail's SMTP server.

If the connection is successful, login using the sender's email and password, and send the email message.

If any error occurs during the process, handle the exception and print an error message.

Prompt the user to input the email title, message, and recipient email address.

Call the send_email function with the provided input to send the email.

Note: Before running the code, make sure to replace the sender_email and sender_password with your own Gmail credentials.

The code allows for customizable email content and sending promotional emails using Gmail's SMTP server. It provides user prompts for inputting the email details, simplifying the process of sending personalized promotional emails.
