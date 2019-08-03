# Dynamic-Disjoint-Sets
Java implementation of the Dynamic Disjoint Sets ADT (Union-Find), and then use it to test whether a maze given as an input image can be solved or not.
In each image (maze), there are two specific pixels colored red – these mark the start and end of the maze (no significance to which is which). After finding them and saving their position, they are colored white, and then run the segmentation, and use it to check whether a path between the two end points exists or not.

## Prerequisite
You need to have java installed on your system. You can get the java from https://www.oracle.com/technetwork/java/javase/downloads/index.html.

## Usage
Download: DisplayImage.java, Maze.java, UnionFind.java and mazeImages folder and put them in the same folder.
Than, run the following commands in the cmd\terminal:
````
javac Maze.java
````
````
java Maze <image-filename>
````
for example:
````
java Maze mazeImages/maze1.PNG
````

This will run the application to check whether a path between the two end points exists or not in the maze1.PNG image.
