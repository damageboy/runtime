set(SOURCES
  test14.cpp
)

add_executable(paltest_vswprintf_test14
  ${SOURCES}
)

add_dependencies(paltest_vswprintf_test14 coreclrpal)

target_link_libraries(paltest_vswprintf_test14
  ${COMMON_TEST_LIBRARIES}
)
