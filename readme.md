## **The Counter Game**

**Number of players:** 2 players

**Procedure:** The 7 segment displays increasing number at variable rate. Any player can choose to _collect_ the number displayed on the 7 segment. Upon collection, it **resets** the number back to zero. The player who collected the number obtains a score equivalent to the current number when the player choose to _collect_ it. Each player however, can only choose to collect the number **three times at maximum.** The game runs for 30 seconds, and ends once the timer runs out, or that both players have used up their 3 collection chances.

**Winning Condition:** The player with the _most score_ at the end of 30 seconds wins the game. If both players end up with the same score, then the game ends in a _draw_.

### Controls

- Player 1: `io_button[4]` to collect the currently displayed number
- Player 2: `io_button[3]` to collect the currently displayed number

### Display

- Player 1 Score: `io_led[0]`
- Player 2 Score: `io_led[1]`
- If Player 1 wins, all leds in `io_led[0]` will be illuminated. Similarly with Player 2.

## Important Notice

This repository is meant to serve as a sample repository for 50.002 1D project. Its ALU is implemented using Lucid/Verilog math and comparison operators. The game is FSM-based and is sufficient to gain perfect score given that the hardware connections are done properly and the enclosure of the prototype is acceptable.

For 50.002 1D project, you are **not** allowed to do this, and should implement your ALU following Lab 3 closely using combinational logic units.
