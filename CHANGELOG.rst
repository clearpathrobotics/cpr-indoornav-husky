^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cpr_indoornav_husky
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.4.1 (2024-03-26)
------------------
* Swap the priorities of /cmd_vel and /manual/cmd_vel to enable teleop assist via the GUI
* Remove Config_extras export for outdoornav
* Contributors: Chris Iverach-Brereton, Michael Hosmar, José Mastrangelo

0.4.0 (2024-01-04)
------------------
* Update to work with Otto's 2.26 release
* Add improved support for Husky Observer
* Contributors: Chris Iverach-Brereton, José Mastrangelo

0.3.5 (2023-03-09)
------------------
* Fix the PI variable; husky_description uses M_PI, not PI
* Contributors: Chris Iverach-Brereton

0.3.4 (2023-01-19)
------------------
* Add the wifi_connected and wifi_connection topics that were missing by default
* Contributors: Chris Iverach-Brereton

0.3.3 (2022-11-24)
------------------
* Add a block for wireless charge docking if necessary
* Add the web GUI input
* Add the option to override the ROS2 bridge topics
* Contributors: Chris Iverach-Brereton

0.3.2 (2022-06-15)
------------------
* Fix the python interpreter to use Python3
* Contributors: Chris I-B

0.3.1 (2022-06-03)
------------------
* Change the ROS1->2 bridge domain to 91.
* Fix a bug with the BRIDGE_SETUP_PATH envar
* Update the Husky graphics
* Contributors: Chris Iverach-Brereton

0.3.0 (2022-05-06)
------------------
* Initial public release
* Contributors: Chris Iverach-Brereton
