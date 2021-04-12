moodle-block_timetable
========================

Moodle block plugin which displays the events of a configurable time frame in a beautiful way.


Requirements
------------

This plugin requires Moodle 3.9+


Motivation for this plugin
--------------------------

Moodle's unified calendar is a brilliant foundation for everything related to events and provides deep integration for a lot of activities as well. This block therefor provides an additional interface for the existing calendar entries.

It aims to be an additional alternative to block_upcomingevents and block_calendar. The best location to put the block is the dashboard, especially on Moodle 4.0 because of courses being shifted to a separate page. Using this block, the dashboard essentially provides an overview about the student's day, week or month.

Installation
------------

Install the plugin like any other plugin to folder
/availability/condition/sectioncomplete

See http://docs.moodle.org/en/Installing_plugins for details on installing Moodle plugins


Usage & Settings
----------------

After installing the plugin, it is ready to use without the need for any configuration.

Admins can add it to the dashboard. The block has the following configuration options:
1. Default view – Dropdown – Today, This Week, This Month, Next X days
2. Available views – Checkboxes – Today, This Week, This Month, Next X days
3. Display options – Checkboxes – Event Title, Description, Link, Location, Duration, Single/Recurring, Type, Status (past/future)

Teachers (or other users with editing rights) can add it to their courses. It will provide the same configuration options and one additional:
1. Scope – Radio Button – This course only, All


If you want to learn more about using blocks in Moodle, please see https://docs.moodle.org/en/Blocks.


Theme support
-------------

This plugin is developed and tested on Moodle Core's Boost theme.
It should also work with Boost child themes, including Moodle Core's Classic theme. However, we can't support any other theme than Boost.


Plugin repositories
-------------------

This plugin will be published and regularly updated in the Moodle plugins repository:
TBD

The latest development version can be found on Github:
https://github.com/stefanscholz/moodle-block_timetable

Bug and problem reports / Support requests
------------------------------------------

This plugin is carefully developed and thoroughly tested, but bugs and problems can always appear.

Please report bugs and problems on Github:
https://github.com/stefanscholz/moodle-block_timetable/issues

We will do our best to solve your problems, but please note that due to limited resources we can't always provide per-case support.


Feature proposals
-----------------

Please issue feature proposals on Github:
https://github.com/stefanscholz/moodle-block_timetable/issues

Please create pull requests on Github:
https://github.com/stefanscholz/moodle-block_timetable/issues

We are always interested to read about your feature proposals or even get a pull request from you, but please accept that we can handle your issues only as feature _proposals_ and not as feature _requests_.


Moodle release support
----------------------

This plugin is maintained for the two most recent major releases of Moodle as well as the most recent LTS release of Moodle. 

If you are running a legacy version of Moodle, but want or need to run the latest version of this plugin, you can get the latest version of the plugin, remove the line starting with $plugin->requires from version.php and use this latest plugin version then on your legacy Moodle. However, please note that you will run this setup completely at your own risk. We can't support this approach in any way and there is an undeniable risk for erratic behavior.


Translating this plugin
-----------------------

This Moodle plugin is shipped with an english language pack only. All translations into other languages must be managed through AMOS (https://lang.moodle.org) by what they will become part of Moodle's official language pack.


Copyright
---------

bdecent gmbh
bdecent.de
