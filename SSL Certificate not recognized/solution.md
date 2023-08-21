✅ I verified their claim of it being an SSL issue by running the domain through SSL LABS, which confirmed that the SSL chain was incomplete. The root certificate was fine but the intermediate certifcate was missing.

✅ I requested for the full certificates which they got from Sectigo, then I accessed the hosting panel, and navigated to the SSL management secrion. I re-uploaded the :
Domain certificate
Complete CA bundle

✅ I re-ran the SSL labs test to confirm what I had done, and there were no errors.