add_executable(torquecmd main_torquecmd.cpp)
target_link_libraries(torquecmd ${LIBRARY_NAME})

add_executable(positioncmd main_positioncmd.cpp)
target_link_libraries(positioncmd ${LIBRARY_NAME})

add_executable(velocitycmd main_velocitycmd.cpp)
target_link_libraries(velocitycmd ${LIBRARY_NAME})

add_executable(withincmd main_withincmd.cpp)
target_link_libraries(withincmd ${LIBRARY_NAME})

add_executable(stopcmd main_stopcmd.cpp)
target_link_libraries(stopcmd ${LIBRARY_NAME})

add_executable(readstate main_readstate.cpp)
target_link_libraries(readstate ${LIBRARY_NAME})

add_executable(testmotor main_testmotortorque.cpp)
target_link_libraries(testmotor ${LIBRARY_NAME})