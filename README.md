OOptOut Chrome Extension
========================

What does it do?
-----------

OOptOut lets you opt out of Facebook permissions when the authorization dialog is popped.

Suppose you want to try out a sketchy app without handing over all of your data.
![](http://github.com/chadselph/OOptOut-Chrome-Extension/raw/master/screenshots/too%20many.png)

Whoa there buddy! We just met!  Why don't we just disable a few of these...

![](http://github.com/chadselph/OOptOut-Chrome-Extension/raw/master/screenshots/removing.png)

And then hit "Update"

![](http://github.com/chadselph/OOptOut-Chrome-Extension/raw/master/screenshots/gone.png)

Phew! I feel much safer now.

How Can I Use it?
-----------------

Hopefully soon-ish it will be on the Chrome web store, but for now:

*  Do a git clone of this repository
*  Open up chrome to chrome://extensions
*  Turn on "Developer Mode"
*  Click "Load unpacked extension"
*  Find the folder of your git checkout!
*  Try it out - for example at the [Vimeo Login Page](http://vimeo.com/log_in)

What needs to be done?
----------------------
*  Logo, finding a better name. Help wanted!
*  (Maybe) descriptions of what each permission does.
*  (Maybe) ability to add permissions the site isn't acually asking for.
*  Package up in a chrome extension.  Basically I'm waiting on the name and logo stuff before I submit it.

Why do some sites break when using this plugin?
----------------------------------------------
Sometimes server-side code is written without the consideration that a Facebook permission might not have been granted.  They might get a permission denied back from Facebook and not handle it gracefully.  Some sites might be more aggressive than others about checking which permissions you're missing and trying to get you to re-auth.


Links
-----
* [Hacker news conversation](https://github.com/chadselph/OOptOut-Chrome-Extension)
* [Firefox port](https://github.com/psawaya/OOptOut-Extension-Firefox)
* [cheald](http://hackerne.ws/user?id=cheald) on hackernews found this [similar project](https://chrome.google.com/webstore/detail/mlnhcepfaddcopbeggpobodmmodilgmc) although I don't think the UI is very good; and it apparently records which permissions you chose (for a good reason: their reseach; but ironic for a "privacy" application.)  I don't know if it works, I haven't tried it.