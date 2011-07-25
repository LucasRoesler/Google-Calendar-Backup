General Information
===================

This is a simple script to backup your Google calendars to your computer.
It will grab all of your calendars and save them in ical format.

Goals
-----
Some future goals are to

* More secure password storage, I want to implement use of the gnome-keyring
but this doesn't play nice with cron.

Current Features
----------------

* Backup all of your Google calendars (public and private) in ical format

Installation
============
 Download the script, you must edit it to include your email and password
 so change the lines

    email = ''
    password = ''
    backup_folder = ''

to

    email = 'your.email@gmail.com'
    password = 'yourpassword'
    backup_folder = 'location you want to save the caledars to'

Contributing
============

Get the code at

    git clone git://github.com/TheAxeR/Google-Calendar-Backup.git
