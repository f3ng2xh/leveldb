ADD_EXECUTABLE(my_app main.cc $<TARGET_OBJECTS:leveldb>)
target_include_directories(my_app PRIVATE ${PROJECT_SOURCE_DIR}/include)
