i18n
====

i18n WordPress tools

Goal
--------

- Improve makepot.php so that are no error reports.
- Allow add-textdomain.php to add text domain to multiple files
- To create a WordPress plugin out of this.

Features
--------

- create POT with strings and translator texts
- add text domain to strings

Documentation
-------------

Installation
------------

To get it running you need to download the files, clone or fork the repo.

To create a pot file for themes
Change the directory in command line to where the POT file should be created.
Paste this code in the command line.
`php C:\path\to\i18n\makepot.php wp-theme C:\path\to\theme-folder\`
To create a pot file for plugins
Change the directory in command line to where the POT file should be created
Paste this code in the command line.
`php C:\path\to\i18n\makepot.php wp-plugin C:\path\to\plugin-folder\`

To add a text domain
Change the directory in command line to where the text domain should be added to the strings in the file.
Paste this code in the command line.
`php C:\path\to\i18n\add-textdomain.php -i text-domain file.php`
or
`php C:\path\to\i18n\add-textdomain.php -i text-domain file.php > new-file.php`

Files
-----

The `[pomo](https://github.com/WordPress/WordPress/tree/master/wp-includes/pomo)` folder is part of WordPress core. As it is a important part of this project I have inlcuded it here so that it can be edited as needed.

Contribute
----------

- Issue Tracker: github.com/grappler/i18n/issues
- Source Code: github.com/grappler/i18n
- [WordPress Coding Standards] (http://make.wordpress.org/core/handbook/coding-standards/php/)
- [WordPress Documentaion Standards] (http://make.wordpress.org/core/handbook/inline-documentation-standards/php-documentation-standards/)

Support
-------

If you are having issues, please let us know.
You can report them in the issues tracker.

License
-------

The project is licensed under the GPL-2.0+ license.