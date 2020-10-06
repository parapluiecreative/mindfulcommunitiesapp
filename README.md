Mindful Communities
=================

This is the primary repository of source code for the Mindful Communities App

License
-------
Moodle is used under the Apache License 2.0.

This app is (c)2020 Parapluie Creative, and is provided under Exclusive License to the Mindful Communities Group

Building for iOS (for the first time)
-----------
1) Open terminal and navigate to the location where you cloned this repo.
2) Run npm setup run
3) Run npx ionic platform add prod:ios
4) Run npx cordova plugin rm phonegap-plugin-push
5) Set the folder permissions for the place where you stored the Git repository to allow all users to read and write recursively.
6) Open Xcode, set the signing settings to sign using the certificate for the team "Michael Hines"
7) Set the corresponding version and increment the build number, even if the last build failed.
8) Open terminal, navigate to the repo, and run sudo npx cordova run prod:ios
9) After the build has completed, open XCode, and go to Product>Archive
10) Submit the update package to Apple via Transporter.
11) Write the corresponding patchnotes for the platform, do not note specific bugs fixed, unless the bug is noticed by a User. Security fixes should be pushed IMMEDIATELY. Non security, quality of life fixes should be released to the App Store on Thursdays at 1AM PST.
12) Note the push in Jira. If apple submits a rejection along with feedback, note the feedback provided by Apple as Jira issues, squash the bug, and resubmit. Increment the version number for every package to be released to the app store with major functionality changes.

------------
**Current iOS Version: 3.9.5**

**Current iOS Build Version: 3.9.5.1**
------------

**Next iOS Version: 3.9.51**

**Next iOS Build Version: 3.9.51.0**
