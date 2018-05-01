
Here's the resulting documentation for our testing of the Postfix service.


--------------------------------------------


**Confirming Installation:**

1. We're currently testing to make sure that Postfix has been installed on the server and we know how to access it.

2. Right now we're checking the status of the service and making sure that we both know its location and have access to it.

3. We're also making sure that it's been configured and if not to configure it.

4. We're currently running a command to see if the Postfix has been configured properly.

// sudo dpkg-reconfigure postfix

5. Looks like the Postfix is configured, we simply used a different variable for the email when testing the sending function.

// Instead of using example.com we'll use csci2461.com as an email to accept from and send to.


--------------------------------------------


**Configuring the Postfix mail server:**


6. We made the virtual file and edited contact information to help us in our configuration process.

// Contact: klor0610@sootsplash.csci2461.com 

7. To check that the mail was sent properly, we typed in

// mail

This will show us whether there were new messages or how many were received.

8. To view the contents of a message we just pressed enter as shown in the attached picture.


--------------------------------------------


**Testing process and presentation:**


9. We'll do final checks in sending out emails to our fellow users on sootsplash.

10. Our fellow users simply have to just type in

// mail

And they'll get information upon the mail that we've send to them and can press enter to view further.
