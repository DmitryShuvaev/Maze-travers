# Maze-travers

#include <QCoreApplication>
#include "maze.h"

int main(int argc, char *argv[])
{
    QCoreApplication a(argc, argv);
Maze m;
    m.printMaze();
m.printPos();
int i=0;
/*
while ( i<63) {
 m.move();i++;
}
*/
m.mazeTravers(m.maze,12);
    return a.exec();
}

