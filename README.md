# MazeSolver
 Solves a maze given to the program as a list with '#' and ' ', tries to return the shortest path by using BFS algorithm.

### Precautions
The algorithm used in this program is very crude, hence, it takes a really long time to solve bigger mazes. I have tested it with 10x10 mazes and it did work on those, but even then if the mazes were a bit more complex, the program would literally just brute force it's way through it. This was my first venture into pathfinding algorithms, so expect to see more repos on my profile related to pathfinding

### How to use:
The included jupyter notebook can be used to convert any maze with black walls and white spaces and entry and exit on top and bottom or the other way round respectively into a 2d character array with each whitespace represented by ' ' and each wall represented by a '#'.
You can store the list in a bin file and then import it into the automaze.py file to use it there, I mostly didn't bother because of how slow this algorithm is in real world usage. DO NOT use anything over 10x10 or 15x15 depending on how fast your pc is. Then just copy over the list(crude I know) into the main py file and let the program do it's thing.

You are free to change this code any way you like and use it anywhere you like (although I don't really recommend it).

### TODO:
- Maybe implement linked lists to make the code work 8x faster and not brute-force it's way through, and make it more usable
- Add more pathfinding algorithms to this repo as I learn em
- Make this a python package (hehe)