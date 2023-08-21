✅ Step 1: Visit the site on different devices and browsers then look for the padlock icon next to the URL. 
If you dont see the padlock or see a red warning, click it and check the error message.

✅ Step 2: Use SSL Labs to analyze the certificate. [https://www.ssllabs.com/ssltest/] <<--Use link.
Once it completes, review the SSL Grade, certificate chain and compatibility across browsers.
Look for error "incomplete chain".
Scroll down to the "Certification paths" section. If the chain ends prematurely or is missin intermediates, that is the culprit.

✅ Step 4: Download the correct certificate bundle from the SSL provider:
Server certificate
Intermediate certificate(s)

✅ Step 5: Reinstall the SSL certificate om thE hHosting panel.
Go to the SSL management section and input the values into the correct fields which are:
Private key
Certificate(CRT)
CA bundle

✅ Step 6: Retest and validate by running the site through SSL labs to confirm if the error shows up again or if you've successfully solved the problem.