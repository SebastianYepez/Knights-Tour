# Knights-Tour

## Description
KnightsTour is a Java program that simulates the famous knight's tour problem on a chessboard. The [knight's tour](https://en.wikipedia.org/wiki/Knight%27s_tour) is a mathematical problem where a knight piece moves around the board in such a way that it visits every square exactly once. This program demonstrates one possible solution to the knight's tour problem utilizing a greedy algorithm.

## Functionality
My implementation of the knight's tour works by maintaining multiple 2D matrices. One of these matrices is updated based on the move number the knight is on (1-64). The other matrix keeps track of how many moves a square currently has available. The premise of the greedy algorithm is to move to the square that has the least number of available moves from the current position of the knight.

## Usage
I developed this project in high school as a passion project, thus one could fine tune the code or use it as inspiration for their own implementation! Simply, one may just download, compile, and run this program on their own machine.

As a user, the program will run as long as desired, taking in a coordinate input (e.g. e4) and printing the resultant board until the user types in "done."

If you would like to try to solve the Knight's Tour on your own, [here[(https://www.maths-resources.com/knights/) is a fun game online!
