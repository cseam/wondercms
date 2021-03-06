# WonderCMS 2.3.2
- WonderCMS is a flat file CMS built with PHP, jQuery and Bootstrap (HTML/CSS).
## [Demo](https://www.wondercms.com/demo) • [Download](https://github.com/robiso/wondercms/releases/download/2.3.2/WonderCMS-2.3.2.zip) • [Documentation](https://github.com/robiso/wondercms/wiki#wondercms-documentation) • [Themes](https://wondercms.com/themes) • [Plugins](https://wondercms.com/plugins)

<a href="https://www.wondercms.com" title="WonderCMS website"><img src="https://www.wondercms.com/WonderCMS-intro.png?v=5" alt="WonderCMS quick intro" /></a>

### Installation
- unzip and upload anywhere you wish to install WonderCMS

### Requirements
- PHP 5.5 or higher
  - cURL extension (for local servers, install a certificate to avoid [the persistent "Update" message error](https://github.com/robiso/wondercms/wiki/Persistent-%22New-WonderCMS-update-available%22-message))
  - mbstring extension
  - ZipArchive extension
- htaccess support (on Apache)
  - using NGINX instead of Apache? [Use this NGINX server config](https://github.com/robiso/wondercms/wiki/NGINX-server-config)
  - using IIS instead of Apache? [Use this IIS server config](https://github.com/robiso/wondercms/wiki/IIS-server-config)

### What's new in 2.3.2
- two additional ISSET checks to prevent PHP notices
- changed HTTP 1.0 headers to HTTP 1.1
- updated links to themes and plugins in the Settings panel (new links are: https://wondercms.com/themes and https://wondercms.com/plugins)
- removed converted case for page titles
- core code in WonderCMS prettified - providing a better level of readability
- minor text changes

What's new history: https://wondercms.com/whatsnew

### Features
 - no configuration required, unzip and upload
 - simple click and edit functionality
 - one click update and backup
 - lightweight - runs on a couple hundred lines of code and 5 files
 - easy plugin/theme install and update
 - custom login URL
 - custom homepage
 - better password protection
 - highlighted current page
 - mobile responsive, easy to theme, 404 pages, clean URLs
 - easy page creating and deleting
 - better SEO support - custom title, keywords and description for each page
 - optional functions.php file - includes itself when you create it (the location of the functions.php should be inside your theme folder)
 - no known vulnerabilities - special thanks to yassineaddi, hypnito, and other security researchers

### [List of common errors](https://github.com/robiso/wondercms/wiki/List-of-common-errors)

### Links
- [WonderCMS website](https://wondercms.com)
- [Community](https://wondercms.com/forum)
- [Twitter](https://twitter.com/wondercms)
- [Donate](https://wondercms.com/donate)
