add_executable(GS_Sample
    sample.cpp
)

target_link_libraries(GS_Sample
    PRIVATE
        gs::gs
)