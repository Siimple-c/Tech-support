✅Step 1: Access server via Cpanel and locate the file manager, this will have the wordpress installation file. 
Search for [public_html]

✅ Step 2: Enable debugging by opening the file named wp-config.php.
Search for the line that says 
[/* That's all, stop editing! Happy publishing. */
]
Add the following lines of code before the line above
<!-- define('WP_DEBUG', true);
define('WP_DEBUG_LOG', true);
define('WP_DEBUG_DISPLAY', false); -->

This  activates debug mode, logs all errors to a file and still keeps the frontend clean without aaffecting visitors.

✅ Step 3: Trigger the Error by logging into the dashboard via /wp-admin, but now, the logs are being recorded behind the scenes.

✅ Step 4: Go to your cpanel and use the file manager to access /wp-content/debug.log
Download the file and look for lines containing [PHP fatal error] this will tell you what plugin is responsible.

✅ Step 5: Disable the plugin by entering the /wp-content/plugins/ . Rename the folder to from plugins to plugins_disabled. 

✅ Step 6: Go back to /wp-admin and log in. Once you regain access, from there update the plugin or change it completely.