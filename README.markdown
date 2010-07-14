Bash Drupal Module Creator
==========================

As [Jordan Sissel](http://github.com/jordansissel/) always says, if you do a multi-step process more than once, you're doing it wrong.

This bash script creates the directory and info and module files for a new Drupal 6.x module.

Installation
------------
Put all the included files into a directory together, then add that directory to your $PATH. I'd recommend `/usr/bin/newmod/` or `~/bin/newmod/`.

Usage
-----
`newmod module_name`

Result
------
- Creates `module_name` directory
- Creates `module_name/module_name.info` with basic template
- Creates `module_name/module_name.module` with basic template

That's it. Nothing fancy, just a time saver.

Customization
-------------
Modify the included `template.info` and `template.module` if you want the started files to be different.

Meta
====
* Written by [Brock Boland](http://www.brockboland.com/)
* On GitHub: [http://github.com/brockboland/Bash-Drupal-Module-Creator](http://github.com/brockboland/Bash-Drupal-Module-Creator)
