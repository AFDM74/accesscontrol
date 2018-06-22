AccessControl
=============

Door Access Control System Software

This take on a Access Control system is focused in opening doors using a Raspberry Pi, a HID Proxy+ RFI card reader and a relay to trigger the door lock mechanism.

As this project was forked from another GitHub user, there are still some files that don't matter for my version of this software, but are still present at this time.

**Currently focused on doing:
- Debian (raspbian) initialization scripts
- Modifications to logging system

**I wish/plan to (TO DO):
- Installation script
- Add a simple web site to manage cards, reload the AccessControl Service, and check system status.
- Add a simple Arduino w/ network support to query a remote database.

This project is forked from the github project from rmiller @ duskglow located at https://github.com/duskglow/accesscontrol. The original software contained herein was designed for controlling access to doors and lockers for the 'Ctrl-h' hackerspace in Portland, OR.

It uses the following submodules:
- Wiegand Protocol Library (https://github.com/monkeyboard/Wiegand-Protocol-Library-for-Arduino)
- rpi/wiringPi Libray (http://wiringpi.com/)

Suggestions, Questions and Feedback are really appreciated: me @ decomartins dot com (Yes, my e-mail account is 'me')...
