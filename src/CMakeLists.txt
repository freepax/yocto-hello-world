# Name of the target
set(TARGET hello)

add_executable(hello hello.c)
target_link_libraries(hello m)


set(EXECUTABLES
  hello
)

install(TARGETS ${EXECUTABLES} DESTINATION /usr/bin)
