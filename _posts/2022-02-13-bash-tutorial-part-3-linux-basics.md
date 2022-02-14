---
layout: post
title: bash tutorial - part 3 (linux)
author: "@dm1n"
tags:
- linux
- bash
- tutorials
---

so today we're going with some basic linux commands you can use with bash (mostly to [compare things](https://hacknorris-aka-penguin.github.io/2022-01-22-bash-tutorial-part-2-conditions/) or boost your productivity)

first easy command: `sudo` - logins as other user (mostly root)\
    most important arguments:\
        - `-e` edits file (no need to pass other commands to other files)\
        - `-h` allows logging in to a remote PC\
        - `-s` run in custom shell (other than bash)\
        - `-u` run as other user (instead of default root)\
        - `-A` doesn't ask for password if desktop have askpass app\

second important command: `echo` - just outputs text (probably already was in first part of tutorial)\

third important command: `ping` - checks connection to remote host (like website)\
    most important arguments:\
        - `-c` limit pings to a number (otherwise you'll need to stop it by youself ending script)\
        - `-i` make delay in seconds before sending each ping\
        - `-q` doesnt display output (returns to a variable)\
        - `-s` change default size of a packet (mb)\

fourth important command: `mkdir` - creates folders\

fifth important command: `rm` - removes folders or files\
    most important arguments:\
        - `-f` forces deletion not looking at file size and doesnt ask for deleting OS files\
        - `-i` ask for every file/folder deletion\
        - `-r` remove also subfolders and files in subfolders\
        - `-d` remove empty folders\
        - `-I` ask if deleting more than 3 files/folders\
        
sixth important command: `cat` - show contents of file\
    most important arguments:\
        - `-n` number lines of output\
        - `-v` show key combinations\
        - `-T` display tab keys as key combinations (^I)\
        - `-E` show $ after every end of line\
        - `-A` show visually all characters (whitespace, key combinations and new lines)\
        - `-s` remove empty lines\
        - `-b` show all *filled* lines (overrides `-n`)\

seventh important command : `pwd` - shows current directory\

i know it was short and yes, it didn't had ALL commands but I thihnk it's enough for this moment. after some other tutorials will be more commands ;)\
