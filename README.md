===================
WordPress Blog
===================

===================
TABLE OF CONTENTS
===================
1) Introduction
2) Requirements
3) Setup


===================
1) INTRODUCTION
===================

An Android app for WordPress blogs.


===================
2) REQUIREMENTS
===================

Requires the JSON API plugin to be installed and activated, which can be found here:
http://wordpress.org/extend/plugins/json-api/


===================
3) SETUP
===================

To setup the app for your own website first edit site.xml in res>values>.
Most importantly, you must edit the URL of your website, site_url, or it won't show your website.
Also, you must edit the package name from the default one or you won't be able to submit it to the Google Play Store.
You can do this by editing AndroidManifest.xml and changing the package attribute in the <manifest> tag.
