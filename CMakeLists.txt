find_package(iDynTree REQUIRED)

add_executable(iDynTreeJacobianTest iDynTreeJacobianTest.cpp)

target_include_directories(iDynTreeJacobianTest ${iDynTree_INCLUDE_DIRS}

target_link_libraries(iDynTreeJacobianTest ${iDynTree_LIBRARIES} )
