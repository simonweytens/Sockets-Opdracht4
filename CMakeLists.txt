cmake_minimum_required(VERSION 2.8 FATAL_ERROR)
project(Opdracht4)

link_libraries(PJ_RPI)
link_libraries(libtlpi.a)

add_executable(Client Client.c)
add_executable(Server Server.c)
add_executable(Http http_server.c)

