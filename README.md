# pilz_templates
Templates and example applications for the PRBT manipulator.

## `prbt_default_application` package

Copy the launch file into your application package. If you want to use
all configuration options, download this repository and use the files
as template.

Please see the [tutorials](https://wiki.ros.org/pilz_robots/Tutorials/) 
for explanation of the directory structure. Links inside the
launch file point to more information about individual options.

For information about the python setup please see [this thread on answer.ros.org](https://answers.ros.org/question/256611/catkin-rospy-package-structure/) or the [python style guide](http://wiki.ros.org/PyStyleGuide)

It should not be necessary, to change the original launch files
`robot.launch` or `move_group.launch` and thus fork pilz_robots.
If there are any options missing, please file an Issue.

### Versions
`pilz_templates` work both with *ROS melodic* and *ROS kinetic*.
There is a single `master` branch for both releases.

### Changelog
Changes are listed in [Changelog](prbt_default_application/CHANGELOG.rst).
If options changed in a recent version, please update your working copies
accordingly.
