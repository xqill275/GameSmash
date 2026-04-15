add_library(gs STATIC
    entry.cpp
)

add_library(gs::gs ALIAS gs)

target_compile_features(gs PUBLIC cxx_std_23)

target_link_libraries(gs
    PUBLIC
        OgreMain
        OgreBites
)

target_include_directories(gs
    PUBLIC
        ${PROJECT_SOURCE_DIR}/include
)