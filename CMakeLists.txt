cmake_minimum_required(VERSION "3.19.7")
project("Sort")
include_directories(inc)
file(GLOB SOURCE "src/*.cpp" "inc/*.hh")
add_executable(${PROJECT_NAME} ${SOURCE})
# cmake_minimum_required(VERSION "3.19.7")

# project("Srimejk")
# add_executable("${PROJECT_NAME}" "Main.cpp")
# install(TARGETS "${PROJECT_NAME}" DESTINATION bin) 
# install(FILES "Main.cpp" DESTINATION src)
