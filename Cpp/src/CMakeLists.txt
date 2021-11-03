# SRC

set(EXECUTABLE_NAME main.out)
add_executable(${EXECUTABLE_NAME} main.cpp)
target_link_libraries(${EXECUTABLE_NAME} ${CONAN_LIBS})