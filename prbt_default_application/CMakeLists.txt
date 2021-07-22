cmake_minimum_required(VERSION 3.0.2)
project(prbt_default_application)

find_package(catkin REQUIRED COMPONENTS
  # nothing
)

catkin_python_setup()

catkin_package(

)

# install executable python script
catkin_install_python(PROGRAMS scripts/myApplication.py
	DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})

install(DIRECTORY launch DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY config DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY urdf DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
