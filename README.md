# The-Game-Of-Life
## The Game of Life is a simulation game developed by the mathematician Conway John as a research model The life cycle of the living organism. The game is played on a huge matrix whose members are sites Possible survivals: each site can have one of the following two situations:
### A. "There is life" - a full life site - will be marked as a full square
### B. "There is no life" - an empty life site - we will mark it as an empty square
### Birth - in every site where there is "no life" that has exactly 3 living neighbors, there will be a birth in the next generation. otherwise The site remains "lifeless" - empty.
### Death - at any site where there is "life" that has 0 or 1 living neighbors, death will occur in the next generation as a result from loneliness In any site where "there is life" and if there are 4 or more living neighbors, death will occur in the next generation as a result From "Population Explosion".
### Existence - any site where "there is life" and has 2 or 3 living neighbors, will continue to exist in the next generation. The processes of birth, death and existence occur simultaneously in all sites and create a new state of life called A new generation.
## How the game look like?
### First the program will create a matrix with random values ​​representing the initial life states.
### The program will display the life matrix in a window on which the cells must be drawn as empty squares  and full according to the situations of life. The drawing is on a Canvas component located inside a .Application window
### There is a button in the upper left corner of the drawing surface. Each time the button is pressed, the program will calculate the life modes of the next generation and update the display.
## GameOfLife.java:
### The GameOfLife class represents the life matrix. The class includes a constructor that accepts my dimensions The matrix and appropriate operations for updating and retrieving the information.
## DrawGameOfLifeController.java:
###  The drawing is done from the DrawGameOfLifeController class which includes a method that responds to the button press. Filling squares is done using the fillRect method of the GraphicsContext.
