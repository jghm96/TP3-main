cmake_minimum_required(VERSION 3.17)
project(TP3_main)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(TP3_main
        agua.cpp
        agua.h
        aire.cpp
        aire.h
        bin_search_tree.h
        bin_tree_node.h
        camino.cpp
        camino.h
        casillero.cpp
        casillero.h
        diccionario.cpp
        diccionario.h
        fuego.cpp
        fuego.h
        grafo.cpp
        grafo.h
        interfazUsuario.cpp
        interfazUsuario.h
        juego.cpp
        juego.h
        lago.cpp
        lago.h
        lecturaCsvCasilleros.cpp
        lecturaCsvCasilleros.h
        lista.h
        logFile.cpp
        logFile.h
        main.cpp
        matriz.cpp
        matriz.h
        montania.cpp
        montania.h
        node.h
        node_double.h
        parser.cpp
        parser.h
        personaje.cpp
        personaje.h
        precipicio.cpp
        precipicio.h
        queue.h
        tierra.cpp
        tierra.h
        vacio.cpp
        vacio.h
        volcan.cpp
        volcan.h)
