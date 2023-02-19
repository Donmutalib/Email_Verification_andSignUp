# Email_Verification_andSignUp
Email verification is used to ensure whether the provided email corresponds to an existing user. 

Clone this project to follow along

Explanation: 
App.js contains the route to generate tokens and send an email
I use Gmail as a service for simplification.   

In the first line I have imported the nodemailer package and then a transporter object to send mail.
The sendMail method of the transporter object simply sends the mail to the given address.
Run the server with node app.js
