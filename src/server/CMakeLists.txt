add_executable(server_app 
    main.cpp
)

target_link_libraries(server_app
sqlite3
)