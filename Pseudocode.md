# Pseudocode

## Intialize game

big board grid 4x4
small boards grid 4x4

## Start Screen

display start screen
if start button clicked:
    go to game board

## Game Running

While game running:
    display board
    display whose turn it is

## inputs

    if click on spot:
        check if click is valid
        get spot clicked
        place players piece

## win checking

    if 4 of same piece in row on small board:
        give space to winning player
    if 4 of same piece in row n big board:
        give win to player
    switch player

## End Screen

dislay end screen
if restart clicked:
    go back to game function
if exit clicked:
    close program
