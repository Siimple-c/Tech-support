✅ I checked the analytics data via the client admin dashboard as shown by google analytics and then cross-referenced with the raw access logs and wordpress error logs for traffic patterns over the past 1 week.
I was able to identify an abnormal request volume of 310-350 requests per minute.
I was able to confirm the bot attack patterns because of the rapid POST requests to wp-login.php and wp-admin attempts.

✅ I immediately installed Wordfence security plugin and configured rate limiting to a mximum of 10 login attempts per 5 minutes for each IP and also added a CAPTCHA on the login page. 

✅ Finally I activated 2-factor authentication for admin accounts.