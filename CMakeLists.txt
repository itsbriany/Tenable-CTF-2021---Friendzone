project(friendzone)
set(CMAKE_BUILD_TYPE Debug)
file(GLOB hax_SRC "*.h" "*.cpp")
add_executable(friendzone ${hax_SRC})
