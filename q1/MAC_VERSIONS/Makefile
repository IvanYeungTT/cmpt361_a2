GCC_OPTIONS=-Wall -pedantic -I ../include
GL_OPTIONS=-framework OpenGL -framework GLUT 
OPTIONS=$(GCC_OPTIONS) $(GL_OPTIONS)


example1: 
	g++ $@.cpp ../Common/initShader.o $(OPTIONS) -o $@  

