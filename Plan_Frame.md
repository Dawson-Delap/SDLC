# Plan Frame

## Game Mechanics

How the player will interact with the game

- Keyboard controlls with arrows
- Mouse controlls by clicking

- Test if both work
- See which people prefer

## Logic Testing

How the game will check is someone won

- Have an index system that the game checks

- index spots and see if the piece goes in the right spot

How winning the small boards will work

- Have a seperate index system for the small boards

- see if the index system interferes with the big boards

## Boundary Testing

- if 2 4 in a rows at the same time give the player the space and there is no extra benifit

- check spots clicked to make sure that the spot is valid

## Integration Testing

- The game updates the board after every placement
- when pressing buttons on start and end screen they work and go to right screen

## Bad Input Handling

- check if click is valid
- if game breaks have a restart

## Test Info

| Test Case | Test Data | Expected Outcome |
| --------- | --------- | ---------------- |
| Winning   | 2 wins    | The player should win if they win twice|
| Save to Gallery | Screenshot of board| Saved to Gallery and able to view|
| Invalid place | click on spot taken | the click does nothing|
