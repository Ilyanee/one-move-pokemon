# one-move-pokemon
Pokemon Battle AI to find the best move in a given 1v1 battle state

# Aim of this project
This project aims to put in practice theoretical knowledge about deep learning and data.

## Model
The model aims to decide from a player's perspective on what are the best offensive and defensive moves available in a given context.
This is only an estimation.

## Decision making
The decision relies on the following assumptions:

- The player knows everything about his/her Pokemon at all times

- The player knows only what has been seen from the opponent's Pokemon, the unknwon features are either max values (stats) or most popular ones (moves, item...)

- The environment is known at all times
