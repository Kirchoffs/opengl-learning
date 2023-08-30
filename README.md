# opengl-learning
Reference:
- https://learnopengl.com/
- https://carette.xyz/posts/opengl_and_cpp_on_m1_mac/ 

## Install GLFW on MacOS M1
### CMD
```
>> git clone https://github.com/glfw/glfw.git
>> cd glfw
>> cmake -DCMAKE_OSX_ARCHITECTURES=arm64 .
>> make
>> sudo make install
```

### Test
```
>> cd hello-world
>> g++ test_opengl.cpp -o test_opengl -std=c++17 -framework Cocoa -framework OpenGL -framework IOKit -lglfw3
>> ./test_opengl
```