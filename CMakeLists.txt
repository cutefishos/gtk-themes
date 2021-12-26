cmake_minimum_required(VERSION 3.5)
project(gtk-theme)
install(DIRECTORY Cutefish DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY Cutefish-light DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY Cutefish-dark DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
    
