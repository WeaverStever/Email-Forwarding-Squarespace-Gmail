# Email-Forwarding-Squarespace-Gmail
Howto use Squarespace domain forwarding for Gmail send as


GMAIL must have two factor identification enabled.
https://support.google.com/accounts/answer/185839





follow these instructions:

3. Go to https://myaccount.google.com/  (https://myaccount.google.com/apppasswords)

5. In the search window at the top of screen enter "app passwords"

6. Let google verify your identity

7. Where it says "app name" in the gray box enter your gmail address (email@gmail.com)

8. copy the code that is generated

9. open gmail settings (settings wheel on upper right, "see all settings", accounts and import)

10. click "Add Another Email Address"

11. in the Yellow box type the domain email address you want to use ex. name@yourdomain.com

and make sure the Treat as alias box is checked

12. Press Next Step and it the following box change the SMTP Server to smtp.gmail.com

13. Enter your gmail address exactly as entered in your app password (step 7)

14. Enter the code copied (step 8)

15. Press Add Account

16. You should receive a Verification Email from google. Follow the link and use your domain email as a gmail alias.



Taken from https://forum.squarespace.com/topic/296578-squarespace-email-forwarding-defaults-for-ex-google-domains-mailgun/

After my MX records were changed to mailgun.org I was able to get my original google domain email address to work as in alias in regular gmail google using the following instructions for app passwords. (It seems there is a bug in google that is making the app passwords work differently than on their guidance page.) 
