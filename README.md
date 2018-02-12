**~/Projects/nano**

#### To Do: 

- Conduct experiments with the **header** statement, to handle using **#!/usr/bin/env bash**, instead of **#!/bin/bash**
- 

###### Saturday, June  6, 2015

- Successfully pushed origin/header branch from ProBook to BTCDEV
- Successfully pulled origin/header branch from BTCDEV to HQ
- Changed include files from /usr/share/nano to ~/Projects/nano in ~/.nanorc
- Added ~/.nanorc file from both my Mac & ProBook
- Successfully pulled changes from Mac/BTCDEV

###### Thursday, June  4, 2015

- Which project is current? ProBook or the Mac?
- I am fairly confident that the ProBook version is the most recent (mostly based on *php.nanorc*).
- Created **header** branch on ProBook
- **Sucess!** Removed the last slash in the shebang, since env takes the language as an argument.
	- **NEW:** header "^#!.\*(ba|k|pdk)?sh[-0-9_]*"
	- **OLD:** header "^#!.\*/(ba|k|pdk)?sh[-0-9_]*"
	- (eg. **#!/usr/bin/php** ===>> **#!/usr/bin/env php**)

