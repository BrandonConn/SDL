#OBJS specifies which files to compile as part of the project
OBJS = hello_triangle.cpp

#CC specifies which compiler we're using
CC = g++

#COMPILER_FLAGS specifies the additional compilation options we're using
# -w suppresses all warnings
COMPILER_FLAGS = -w -std=c++14

#LINKER_FLAGS specifies the libraries we're linking against
LINKER_FLAGS = -lSDL2 -lGL -lGLEW

#OBJ_NAME specifies the name of our exectuable
OBJ_NAME = triangle

#This is the target that compiles our executable
all : $(OBJS)
	$(CC) $(OBJS) $(COMPILER_FLAGS) $(LINKER_FLAGS) -o $(OBJ_NAME)

clean : $(OBJ_NAME)
	rm -r $(OBJ_NAME)
