✅ Go to CPanel file manager navigate to your wordpress root folder [public_html] and create a file named [.maintenance] and add the following line:
<?php
$upgrading = time();

save the file.

✅ Visit your website and you'll see "Briefly unavailable for scheduled maintenance. Check back in a minute."
Try accessing  wp-admin and you'll see the same message appearing.