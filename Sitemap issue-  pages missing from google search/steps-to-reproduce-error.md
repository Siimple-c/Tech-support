✅ Open the command line and run [curl -I https://clientsite.com/sitemap.xml]
You should get a 404, 403, or anything other than a 200, this tells you that the sitemap is not accessible

✅ To check the robots.txt to see if the sitemap isn't linked, add the robots file at the end of the client site URL [https://clientsite.com/robots.txt] and you should get one of the following:
No sitemap line at all
Sitemap pointing to an outdated domain or a block directive like [Disallow]

✅ Open any browser and insert the site URL followed by sitemap_index
[https://clientsite.com/sitemap_index.xml]
Look for one or more of the following:
Blank page
404 Not found
HTML content instead of XML
Error message like "Forbidden" or "Blocked by firewall"?

If any of the above appear, then the sitemap isn't working as expected.

