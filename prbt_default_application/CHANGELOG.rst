^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package prbt_default_application
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This file lists the changes that you have to trace, once you created an own application based on this templates
and update its dependencies. Date and upstream versions are given for reference, you can check for your local
version using ``dpkg -l | grep "prbt-\|pilz-"``.

Forthcoming
-----------
* revision of launchfile
* rename of sto to run_permitted

2020-02-17
----------
* compatible with pilz_robots version melodic-0.5.12
* include ``fake_safety_interface.launch`` in case of ``sim:=True``

2019-06-03
----------
* compatible with pilz_robots melodic version 0.5.4 / kinetic version 0.4.9
* instantiate gripper macro (see https://github.com/PilzDE/pilz_robots/pull/130)
* example how to use PG70 gripper with brackets

2019-04-10
----------
* Add template package with default launch file and configuration examples
* Contributors: Pilz GmbH and Co. KG
