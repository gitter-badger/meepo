# Meepo #

[![Join the chat at https://gitter.im/arawde/meepo](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/arawde/meepo?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
Meepo is a fork of [deskbot](https://github.com/6c37/deskbot). You can think of it as a neovim to deskbot's vim: A heavy overhaul of much of its core functionality.

It is a work in progress until otherwise noted. 

### Features ###
- config.json: centralized runtime options
- Desktop & github key-value storage
- last.fm api querying
- vim-style find replace

### Options ###
``` .dt, .desktop ```
|Short|Long     |Argumens|
|-----|---------|--------|
|-p   |--push   |[url] *Add a new desktop to the end of the list*
|-s   |--shift  |[url] Add a new desktop the the beginning of the list*
|-d   |--delete |[id] *Remove the last or specified **id** from the list*
|-r   |--replace|[id:url] *Replace the specified **id** with the given url*

### Contributing ###
Pull requests are your friends.  
You can find us at #.files on irc.rizon.net.
