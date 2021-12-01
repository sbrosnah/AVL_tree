TARGETS = avl
CC = g++
CCFLAGS = -std=c++11 -g
bst: main.cpp BSTInterface.h NodeInterface.h AVLInterface.h AVL.h AVL.cpp BST.h BST.cpp Node.h Node.cpp
	$(CC) $(CCFLAGS) -o avl main.cpp BST.cpp Node.cpp AVL.cpp

clean:
	-rm avl