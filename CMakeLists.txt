cmake_minimum_required(VERSION 2.8.11)

find_package(iDynTree REQUIRED)

add_executable(iDynTreeJacobianTest iDynTreeJacobianTest.cpp)

message("iDynTree_INCLUDE_DIRS : " ${iDynTree_INCLUDE_DIRS})
include_directories(${iDynTree_INCLUDE_DIRS})

message("iDynTree_LIBRARIES : " ${iDynTree_LIBRARIES})
target_link_libraries(iDynTreeJacobianTest ${iDynTree_LIBRARIES} )
