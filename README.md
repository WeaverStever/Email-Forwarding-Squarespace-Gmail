# Email-Forwarding-Squarespace-Gmail
How to use Squarespace domain email forwarding for Gmail send as.


<b>GMAIL must have two factor identification enabled.</b>
https://support.google.com/accounts/answer/185839

<b>Create your forwarding addresses in the domain section of Squarespace.</b><br>
<i>(If you need to use a free email as the recipient email address, squarespace recommends Gmail.)</i><br>
https://support.squarespace.com/hc/en-us/articles/19000909092237-Email-forwarding-with-a-Squarespace-domain

<b>Follow these instructions to allow forwarding addresses to authenticate.</b><br>
https://support.squarespace.com/hc/en-us/articles/360001280748-Verifying-third-party-domains-for-Email-Campaigns

<b> Add a reverse lookup to DNS </b><br>
https://www.geeksforgeeks.org/reverse-dns-lookup/

<b>Follow these instructions to configure Gmail for Reply As:</b>

1. Go to https://myaccount.google.com/apppasswords

2. Let google verify your identity

3. Where it says "app name" in the gray box enter a unique name (this may need to be your gmail address)

4. copy the 16 character app code that is generated -- paste into a text document -- remove blank spaces(????).

5. open gmail settings (settings wheel on upper right, "see all settings", accounts and import)

6. click "Add Another Email Address"

7. in the Yellow box type the domain email address you want to use ex. name@yourdomain.com
make sure the Treat as alias box is checked, and the port is 587 TLS.

8. Press Next Step and it the following box change the SMTP Server to smtp.gmail.com

9. Enter your app name (from step 3) as the Username (this may need to be your gmail address)

10. Enter the app code copied (step 4) as the Password

11. Press Add Account

12. You should receive a Verification Email from google. Follow the link and use your domain email as a gmail alias.


<b>Forwarding to gmail source document</b><br>
Taken from https://forum.squarespace.com/topic/296578-squarespace-email-forwarding-defaults-for-ex-google-domains-mailgun/

After my MX records were changed to mailgun.org I was able to get my original google domain email address to work as in alias in regular gmail google using the following instructions for app passwords. (It seems there is a bug in google that is making the app passwords work differently than on their guidance page.) 
