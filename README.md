kabam-plugin-welcome
===================

Plugin to show login screen when user is not logined, and show other routes when logined

Disclaimer
===================

This plugin is needed to test in action the passport.js integration to mwc_kernel application.
Later, this plugin will be merged to other plugins or deleted.

Works
===================

 - Login/Password
 - Google
 - Github (with MY github GITHUB_CLIENT_ID and GITHUB_CLIENT_SECRET)
 - Twitter (with MY github TWITTER_CONSUMER_KEY and TWITTER_CONSUMER_SECRET)
 - Hash (account confirmation)
 - Email notification

Do not works for now
===================

 - Facebook - because of ideological reasons i cannot register there (Anatolij).
 - LinkedIn - not tested
 - Custom header (for iOS applications)
 - Heroku deployment - because it CANNOT install npm modules from github...


Captcha integration
===================
First, we need to install node-canvas. For me it was tricky first time and i wrote a wiki about it(fedora) -
[https://github.com/learnboost/node-canvas/wiki](https://github.com/learnboost/node-canvas/wiki)

Responsibility guidelines
================
Every kabam plugin and package has the responsible developer. His duties are

- Maintain the package - fix and found bugs from upgrading modules included or nodejs version change
- React on bug reports
- Accept/deny pull request.

The `Push` and `npm publish` privilege is the right of the `Responsible developer`, but the `fork` - is for everybody.

Responsible developer for this package is  [Anatolij Ostroumov](https://github.com/vodolaz095)
