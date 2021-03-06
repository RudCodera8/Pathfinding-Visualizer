# PathFinding visualizer using Dijkstra Algorithm 

Dijkstra Pathfinding visualizer is a simple React app for providing a visual analysis of Dijkstra algorithm finding the shortest path. 
Check out the working model [here](https://hsp3j.csb.app/)


## Table of contents 
* [More about the project](#More-about-the-project)
* [Installation and Running the program](#Installation)
* [Technologies used](#Technologies-used)
* [Future plans for the project](#Future-plans-for-the-project)


### More about the project

This projects aims to provide visualisation to one of the chadest algorithm in the world of programming. Using this one can easily understand how Dijkstra works and finds the shortest path. 


### Installation
#### Step 1 : Just clone or download the repository into your machine. 
#### Step 2 : Install npm. You will find this helpful - [link](https://nodejs.org/en/download/package-manager/) 
#### Step 3 : change the working directory to the cloned folder 
```
$ cd folder-name 
```
#### Step 4 : Type the following command in the terminal  - this will start the program in your browser localhost:3000 
```
$ npm start
```

#### Step 5 : You can now use the app and visualize the algorithm. 


### Some tips on how to read the code. 

##### src folder contains all the logic of the program 

Node.js and Node.css deals with the grid components, right from assigning numbers and classNames to mounting it on DOM. 
Pathfinding.js- is the main component which renders out the whole program into App.js
dijkstra.js governs the logic for the algorithm. 



#### Technologies used

##### 1) React JS 
##### 2) DS used : Mainly array and minheap essence. Algorithm used : Dijkstra Algorithm. 
#### Future plans for the project

I am planning to add more features such as user settting the starting and finish node, adding more algorithms and specifications such as weighted algorithms, A* search algorithms etc. Also planning to host it on firebase/ heroku along with github workflows. 
