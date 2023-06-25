# Template for LearnOpenGL with `vcpkg` & `cmake`

This is a template to set up a project for [LearnOpenGL](https://learnopengl.com/) using [vcpkg](https://vcpkg.io/) and [cmake](https://cmake.org/). After installing `vcpkg` and configuring the environment variable `VCPKG_ROOT`

```
cmake -S . -B build --preset debug
cmake --build build
build/glfw-example
```

should build and run the scaffold.