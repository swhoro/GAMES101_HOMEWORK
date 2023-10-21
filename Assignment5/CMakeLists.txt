add_executable(hw5 main.cpp Object.hpp Vector.hpp Sphere.hpp global.hpp Triangle.hpp Scene.cpp Scene.hpp Light.hpp Renderer.cpp)
# target_compile_options(RayTracing PUBLIC -Wall -Wextra -pedantic -Wshadow -Wreturn-type -fsanitize=undefined)
# target_link_libraries(RayTracing PUBLIC -fsanitize=undefined)

target_compile_definitions(hw5 PRIVATE -DWIDTH=2560)
target_compile_definitions(hw5 PRIVATE -DHEIGHT=1440)
target_compile_definitions(hw5 PRIVATE -DMSAA2)
