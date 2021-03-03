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

To compile the program, you need to be in the /soccer_semaphore_game

