cmake_minimum_required(VERSION 3.15)
project(neurai_seeder)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(neurai_seeder
        neurai.cpp
        neurai.h
        combine.pl
        compat.h
        db.cpp
        db.h
        dns.cpp
        dns.h
        main.cpp
        Makefile
        netbase.cpp
        netbase.h
        protocol.cpp
        protocol.h
        README
        serialize.h
        strlcpy.h
        test.pl
        uint256.h
        util.cpp
        util.h)
