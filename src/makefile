#demo multiple target project
#lcd
CC := gcc -g
RM := rm -rf ../Debug/*
LIBS :=

all : HelloAgent HelloWorld

clean :
	$(RM) HelloAgent HelloWorld

HelloAgent : HelloAgent.c
	$(CC) HelloAgent.c -o ../Debug/HelloAgent $(LIBS)

HelloWorld : HelloWorld.c
	$(CC) HelloWorld.c -o ../Debug/HelloWorld $(LIBS)