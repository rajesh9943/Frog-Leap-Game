<h1>Frog Leap Game Documentation</h1>

**Problem statement**

Create famous 'Frog leap' puzzle game. Try completing the game before starting to get an idea
about its working. [Enjoy Playing 🎮](http://www.example.com)
 the Frog Leap game!

**Rules**

1\. The left set of frogs can only move right, the right set of frogs
can only move left.

2\. Frogs can move forward one space, or move two spaces by jumping
over another frog from opposite side.

3\. The puzzle is solved when the two sets of frogs have switched
positions.

**Introduction**

Welcome to the documentation for the Frog Leap puzzle game! This game
is a simulation of the classic puzzle in which you must move frogs
between two sets of positions until they switch places. The left set
of frogs can only move right, and the right set can only move left.
Frogs can move one space forward or leap over another frog to move two spaces.
**How to Play**

**Step 1: Display**

The game begins by displaying the initial set of frogs on the left and right sides.

**Step 2: Input**

Enter the position of the frog you want to move. For example, entering position 2 will look like this:
[ 0 , 1 , 2 , 3 , 4 , 5 , 6 ]
['G', 'G', 'G', '-', 'B', 'B', 'B']
[ 0 , 1 , 2 , 3 , 4 , 5 , 6 ]
['🐸', '🐸', '🐸', '🍁', '🐬', '🐬', '🐬']

**Step 3: Rules and Validation**

Ensure that the entered position is between 0 and 6 (inclusive) or 'q' to quit the game.
The entered position cannot be the position of an empty leaf ('🍁').
Check if the selected frog can perform the move based on the game rules.

**Step 4: Make a Move**

Make the appropriate move by updating the game display. The frog can move to an empty space or leap
over another frog.

**Step 5: Winning Condition**

Check if the two sets of frogs have switched positions. If so, the player wins the game.

**MAKE YOUR MOVE**

![Screenshot (135)](https://github.com/rajesh9943/Frog-Leap-Game/assets/98160008/d535afb2-40b5-442d-a05f-11f3f44cbd13)

![Screenshot (134)](https://github.com/rajesh9943/Frog-Leap-Game/assets/98160008/5d40fc76-4601-4982-942d-5a17daaaf09d)

[ 0 , 1 , 2 , 3 , 4 , 5 , 6 ]
['🐬', '🐬', '🐬', '🍁', '🐸', '🐸', '🐸']

**Congratulations.! YOU WIN 🎉**

