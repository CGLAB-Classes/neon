add_executable(neon-sandbox
  main.cpp
  test.hpp
  test.cpp)

target_link_libraries(neon-sandbox
  neon
  extern::lodepng
  extern::glm
  extern::taskflow)
