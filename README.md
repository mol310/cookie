# cookie
Cookie crawler (windows and .net 4.0)

This require:

Sitemap: In this format: http://www.sitemaps.org/protocol.html
Chrome: (Any version should do)
Chromedriver: http://chromedriver.storage.googleapis.com/index.html (i'm used 2.14)

Change sitemap cookie.exe.config (a local should work, untested)

Will produce a csv with all cookies found on crawled site in format:

Page, cookie_domain, cookie_name, cookie_value
