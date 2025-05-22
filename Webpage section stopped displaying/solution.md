✅ I asked if he had done anything recntly on the site and he said no, also pointing to the fact that he isn't too "tech-savvy" especially in the area of web development, so he had no reason to tinker with things.

✅ With this in mind I requested for login credentials and accessed the page to see what was going on.
From the admin login section, everything seemed fine but from a visiors perspective it won't show up.
I checked to see if it was a visibility issue and it wasn't, then I proceeded to check the plugins version from the developers changelog and realised that the plugin had recently been updated. 

✅ I requested for CPanel access, and created a staging site where I then proceeded to uninstall the plugin, clear the cache and reinstall it and that didn't solve the issue.
I proceeded to deactivate all plugins one by one and the issue persisted.

✅ I then proceeded to inspect the page using [DEVTOOLS] and then discovered that the plugin was indeed active but had a negative offset on the X-axis that threw it to the left of the screen.
I zoomed out to 40% and the section was visible.

✅ After further inspection it was determined that this was a plugin error, so I deactivated it, uninstalled it and installed an alternative plugin that was compatible, error-free and performed the exact same task for that section.