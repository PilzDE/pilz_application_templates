cmake_minimum_required(VERSION 2.8.3)
project(prbt_default_application)

find_package(catkin REQUIRED COMPONENTS
  # nothing
)

catkin_package(

)

catkin_python_setup()

# install executable python script
catkin_install_python(PROGRAMS scripts/myFirstApplication.py
	DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})
