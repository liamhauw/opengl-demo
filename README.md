# Introducation

The implementation of pbr based on OpenGL

# Feature

- image-based lighting
- gui based on imgui

# Dependence
> Only MacOS

- OpenGL
- glfw
- glew
- glm
- stb_image
- imgui

# Build

```zsh
git clone https://github.com/liamhauw/opengl-demo.git
brew install glfw glew glm
cmake -S . -B build
cmake --build build
```

# Run
```zsh
cd ./bin
./graphics
```
The *option* key can be used to hide or show the mouse, *WASD* can move the camera position when the mouse is hidden, the mouse controls the camera orientation, and UI Settings can be made when the mouse is displayed.

# Result
![](./img/res.png)
![](./img/res1.png)
