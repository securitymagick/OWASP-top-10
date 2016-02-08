#Sensitive Data Exposure

Objective 1: Map out all the sensitive data in the application, and decide how that data should be protected.  (IE Encrypted / Hashed / Not Displayed / Truncated / What algorithms will you use? / How will your keys be derived?)

Objective 2: Complete cas-tutorials number 3 and change the registration and password reset options to support the password hashing.

Objective 3: Complete the cas-tutorial number 4, and change the registration and passsword reset options to support password hashing algorithms matching the cas tutorials.

Objective 4: Update the DVOCCA other pieces of sensitive data appropriately.

Note:  If you are running CAS without a domain and trying to set up SSL to work with your CAS server and your DVOCCA there are several common problems that you may run into.  Please look at the CAS troubleshooting guides SSL section before trying to set this up to avoid several common problems.  
http://jasig.github.io/cas/4.1.x/installation/Troubleshooting-Guide.html
If you do have a domain avoid the problems caused by a self-signed certificate by getting a cert from a CA.  StartSSL will give you a free SSL cert good for 1 year. 
https://www.startssl.com/

Please read:
https://www.owasp.org/index.php/Top_10_2013-A6-Sensitive_Data_Exposure

For a walkthrough please see:
To be added soon.

