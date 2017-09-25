First Name - Nishant 
Last Name - Rathi
Email Id - nishantrathi@csu.fullerton.edu

Description -
1) Gouraud Shader computes lighting values per vertex and interpolates them over the teapot means covering each fragment over the teapot.
2) Vertex shader calculates the color value of the vertices
3) Pass that color value to Fragment shader by using varying variable
4) Fragment shader fills the calculated color for each fragment over the teapot
5) gl_vertex and gl_normal are used directly i.e. without assigning them to any variable, as we did in Phong shader
6) gl_positon should be in vertex shader
7) What I understood from this task, phong shader is better than gouraud shader