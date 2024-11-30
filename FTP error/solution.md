✅ I had to find out if they had used the method to upload files before, to which they confirmed they had done.

✅ I then proceeded to send them a one-time link for remote access via the [HELPWIRE] app. 

✅ After investigation, it turned out that passive mode was disabled in Filezilla and their firewall was blocking active FTP connections. 
So I enabled passive mode and adjusted firewall rules to allow Filezilla on public and private networks then I retried the upload, which worked perfectly without the error.