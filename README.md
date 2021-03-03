# Soccer Game Simulation

This soccer game simulation program was the second project of the *Operating Systems* class whose main goal is the understanding of semaphores in synchronizing different processes. We used the C language for this project.

## Introduction

Imagine a group of friends who want to get together to play a game of football. There are three possible entities:
- The player
- The goalie
- The referee

The team constitution is made as soon as possible with the group members that already arrived. Each team has 4 players and 1 goalie. If there are more than the maximum number of players or goalies, they are warned they arrived too late and don't join any team. The referee is the game regulator as he is the only one who can start and end the game.

Each one of the group members is an independent process and its syncronization with other processes is made through synchronization and shared memory.

## How to compile and run

To compile the program, you need to be inside the *semaphore_soccergame/src* folder and type the following line to compile the program:

```
make all
```

Once the program is compiled, we can now run the program by typing the following line in the *semaphore_soccergame/run* folder:

```
./probSemSharedMemSoccerGame
```

This will simulate the soccer game with all the different entities, displaying its internal values (states).

The *run.sh* script executes the program the number of times we want, showing all the different simulations and stopping if there is a deadlock:

```
./run.sh (number of times we want to run the ./probSemSharedMemSoccerGame)
```

## Authors

- [Ricardo Rodriguez](https://github.com/ricardombrodriguez)
- [João Reis](https://github.com/joaoreis16)
