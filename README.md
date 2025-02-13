moodle-theme_boost_campus_child
===============================

[![Build Status](https://travis-ci.org/moodleuulm/moodle-theme_boost_campus_child.svg?branch=master)](https://travis-ci.org/moodleuulm/moodle-theme_boost_campus_child)

Moodle Boost Campus child theme which is intended to get the full Boost Campus features but easy to change in color and adding additional SCSS for example for delivering several identical based themes for different users.


Requirements
------------

This plugin requires Moodle 3.6+


Motivation for this theme
-------------------------

We implemented this Boost Campus child theme for easy delivering several identical based themes for different users.


Installation
------------

Install the plugin like any other theme to folder
/theme/boost_campus_child

See http://docs.moodle.org/en/Installing_plugins for details on installing Moodle plugins


Usage & Settings
----------------

After installing the theme, it does not do anything to Moodle yet.

To configure the theme and its behaviour, please visit:
Site administration -> Appearance -> Themes -> Boost Campus Child.

There, you find multiple settings tabs:

### 1. Tab "General Settings"

In this tab there are the following settings:

#### Theme presets

##### Theme preset

This setting is already available in the Moodle core theme Boost. For more information how to use it, please have a look at the official Moodle documentation: http://docs.moodle.org/en/Boost_theme

##### Additional theme preset files

This setting is already available in the Moodle core theme Boost. For more information how to use it, please have a look at the official Moodle documentation: http://docs.moodle.org/en/Boost_theme

#### Brand colors

##### Brand color

This setting is already available in the Moodle core theme Boost. For more information how to use it, please have a look at the official Moodle documentation: http://docs.moodle.org/en/Boost_theme

##### Brand success color

This color is used for example in regards to form validations.

##### Brand info color

This color is used for example for availability information of course activities or resources.

##### Brand warning color

This color is used for example for warning texts.

##### Brand danger color

This color is used for example in regards to form validations.


### 2. Tab "Advanced Settings"

In this tab there are the following settings:

#### Raw initial SCSS

This setting is already available in the Moodle core theme Boost. For more information how to use it, please have a look at the official Moodle documentation: http://docs.moodle.org/en/Boost_theme

#### Raw SCSS

This setting is already available in the Moodle core theme Boost. For more information how to use it, please have a look at the official Moodle documentation: http://docs.moodle.org/en/Boost_theme


How this theme works
--------------------

This Boost Campus child theme is implemented with minimal code duplication in mind. It inherits / requires as much code as possible from theme_boost and theme_boost_campus.
All settings and the entire design (SCSS - pre and post as well as the Raw SCSS part) is completely inherited from theme_boost_campus. So you get a functional and optical duplicate of your existing Boost Campus theme with the possibility to alter or extend it.


How to clone this theme for just another child theme instance
-------------------------------------------------------------

* Copy the directoy /theme/boost_campus_child to /theme/boost_campus/foo
* Search and replace the string "theme_boost_campus_child" within this directory with "theme_boost_campus_foo"
* Rename the file /theme/boost_campus_child/lang/en/theme_boost_campus_child.php to /theme/boost_campus_foo/lang/en/theme_boost_campus_foo.php
* Modify the strings "pluginname" and "configtitle" in /theme/boost_campus_foo/lang/en/theme_boost_campus_foo.php according to your needs


Plugin repositories
-------------------

This plugin is not published in the Moodle plugins repository.

The latest development version can be found on Github:
https://github.com/moodleuulm/moodle-theme_boost_campus_child


Bug and problem reports / Support requests
------------------------------------------

This plugin is carefully developed and thoroughly tested, but bugs and problems can always appear.

Please report bugs and problems on Github:
https://github.com/moodleuulm/moodle-theme_boost_campus_child/issues

We will do our best to solve your problems, but please note that due to limited resources we can't always provide per-case support.


Feature proposals
-----------------

Due to limited resources, the functionality of this plugin is primarily implemented for our own local needs and published as-is to the community. We are aware that members of the community will have other needs and would love to see them solved by this plugin.

Please issue feature proposals on Github:
https://github.com/moodleuulm/moodle-theme_boost_campus_child/issues

Please create pull requests on Github:
https://github.com/moodleuulm/moodle-theme_boost_campus_child/pulls

We are always interested to read about your feature proposals or even get a pull request from you, but please accept that we can handle your issues only as feature _proposals_ and not as feature _requests_.


Moodle release support
----------------------

Due to limited resources, this plugin is only maintained for the most recent major release of Moodle. However, previous versions of this plugin which work in legacy major releases of Moodle are still available as-is without any further updates in the Moodle Plugins repository.

There may be several weeks after a new major release of Moodle has been published until we can do a compatibility check and fix problems if necessary. If you encounter problems with a new major release of Moodle - or can confirm that this plugin still works with a new major relase - please let us know on Github.

If you are running a legacy version of Moodle, but want or need to run the latest version of this plugin, you can get the latest version of the plugin, remove the line starting with $plugin->requires from version.php and use this latest plugin version then on your legacy Moodle. However, please note that you will run this setup completely at your own risk. We can't support this approach in any way and there is a undeniable risk for erratic behavior.


Translating this plugin
-----------------------

This child theme does not contain any strings which are visible to a Moodle student / teacher and it can't be translated on AMOS as it is not published in the Moodle plugins repository. In our point of view, translating this plugin is not necessary.


Right-to-left support
---------------------

This plugin has not been tested with Moodle's support for right-to-left (RTL) languages.
If you want to use this plugin with a RTL language and it doesn't work as-is, you are free to send us a pull request on Github with modifications.


PHP7 Support
------------

Since Moodle 3.4 core, PHP7 is mandatory. We are developing and testing this plugin for PHP7 only.


Copyright
---------

Ulm University
kiz - Media Department
Team Web & Teaching Support
Kathrin Osswald

