# Postfixers

Here's is our third and final attempt at our group project. We've learned quite a lot and have archived the previous two attempts below for reference. 

First project attempt: https://github.com/jumpingcontent/Wikinets_Research

Second project attempt: https://github.com/jumpingcontent/Wikinets_Moinmoin

For our Postfix project we'll successfully test the Postfix installation and document the entire process while taking screenshots and possibly log info to verify that the service successfully works and we understand how it works and can properly present/teach the class on this too.

----------------------------

**Some basic Postfix usage info!**

----------------------------

**To check your mail:**

1. At the terminal for our server type in the command:

mail

2. You can press the enter key to display any waiting messages or go back to the message list by typing:

h

3. You can delete an email by typing:

d

4. You can quit back to the terminal by typing:

q

----------------------------

**To send mail:**

1. Send type a message in the text edit for example:

nano ~/testmsg

2. Within the nano editing write anything for your message:

Hello

3. Then save and back at the terminal with cat you can send the mail:

cat ~/testmsg | mail -s 'Your subject line here' destinationuser@sootsplash.csci2461.com

----------------------------

**To view sent mail:**

1. mail

2. file +sent
