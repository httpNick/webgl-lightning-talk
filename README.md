# WebGL lightning talk

- native 2D/3D graphics library Javascript API for the browser
- renders on HTML5 `<canvas>` elements.
- code written for WebGL runs on the GPU.
- API is shader based and conforms closely to the OpenGL ES 2.0 spec

## OpenGL ES

- cross-platform 2D/3D graphics API.
- creates an interface for control over low-level graphics hardware operations.
- maintenance of API has been handed over to the Khronos Group
- Graphics vendors, such as Nvidia and Intel, create extensions on top of the API to make it fit their needs and add functionality

## Shaders

Code provided to run on the GPU is written in the form of shaders. Shaders are a composition of 4 different data types which are
 Attributes, Buffers, Uniforms, Textures and Varyings. Code for shaders is written in a strictly typed language called GL
 Shader Language. Data/properties that comprise the shaders, however, can be provided from Javascript and passed to the Shaders.
 
### Vertex

![webglcoordsystem](https://github.com/httpNick/repository/webgl_coordinate_system.png)
 - Coordinates of your program
 
### Fragment 

 - Coloring of your program
 
## References and Resources

- https://www.khronos.org/opengl/
- https://www.khronos.org/webgl/
- http://webglfundamentals.org/webgl/lessons/webgl-fundamentals.html
- https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API
- https://egghead.io/courses/create-3d-graphics-in-javascript-using-webgl
- http://www.html5rocks.com/en/tutorials/webgl/webgl_fundamentals/