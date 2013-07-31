inithooks
=========
Based on the inithooks for turnkey linux - https://github.com/turnkeylinux/inithooks

This fork strips back to be a generic inithooks package and splits the turnkey specific scripts into a seperate repository.

The plan is to develop a seperate deb package that will have a set of scripts that can be dynamically loaded into either the firstboot.d or everyboot.d folders.

