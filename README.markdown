# Pelican Export for Habari

This plugin exports Habari posts as static files for Pelican, and is a slightly modified version of the [Jekyll export plugin](http://github.com/ahutchings/habari-jekyll-export) by Andrew Hutchings.

## Requirements

* Habari = 0.6 (*based on version 0.4 of the Jekyll export plugin, so should work in 0.9.x series. *)


## Installation

Step 1: Download this plugin.

To get it from git execute the following command in the `user/plugins` directory:

	$ git clone git://github.com/bryceac/habari-pelican-export.git jekyll-export

Of course you can always download the code from the [GitHub project](http://github.com/bryceac/habari-pelican-export) as an archive.

Step 1: Make the `_posts` directory writable by your web server.

Step 2: Copy `template.example.php` to `template.php` and customize to taste.

Step 3: Enable this plugin in Habari's admin panel.

Step 4: Export your posts by selecting "Export Posts" from the Jekyll Export actions dropdown.
