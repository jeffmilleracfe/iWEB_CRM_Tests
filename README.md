# iWEB_CRM_Tests
Coded UI Tests for netForum's CRM Module

This is a proof-of-concept for trying to share netForum Coded UI Tests across the netForum Community.  The idea here is that we'll have one repository/VS Coded UI Test Project for each module of netForum.  To ensure maximum compatibility across netForum environments, tests should try and follow the following rules:
  - start your test by already being logged into your netForum environment and clicking on the "Abila" logo in the top left; this will reset your session
  - try and only use baseline fields for the initial recording and assertion(s); you can add additional recordings/tests and assertions for CUSTOM Fields or processes (and these tests/assertions should be clearly labeled that they are "custom")
  - be cognizant of your environment and include comments in your test files for things like:  are your modules sorted alphabetically?  Do you assume certain child forms are already expanded?

NOTE: Tests in this respository are for version 2014 of netForum iWEB

ABOUT ME:  Jeff Miller - I've been using netForum now for about 10 years and sharing test scripts has been something I've wanted to do for a few years now.  Given some of the QA challenges we've been experiencing in netForum-land recently, I figured now is as good a time as ever to give this a shot in the developer community.  If you have questions or want to chat about this whole thing, feel free to reach out at jeff.miller "at" acfe.com.
