# cerberus
Cerberus is a multipurpose Rubik's cube simulator which provides a visual interface for tracking the state changes brought about by very long move sequences(>1000 moves). Almost all of the cube simulators available online recieve the move sequences with lengths <= 100. Thus, when it comes to working with longer move strings, we have to mechanically go about copying and pasting smaller parts of each string which makes the process an extremely dull affair. And on top of that, it allows errors to sneak in causing us to repeat the whole thing all over again! 

The simulator uses the 3x variant of the <a href="https://cubing.github.io/AnimCubeJS/">AnimCubeJS</a> module to render the cube canvas. This simulator was actually developed to test the <a href="https://github.com/erstan/cerb">cerb</a> Rubik's cube solver, but can be used for any kind of cubing simulations.
# Usage
Go to the <a href="https://erstan.github.io/cerberus/index.html">simulator</a> page and you'll see an unscrambled 3xRubik's cube. Now, use the following one-letter commands to interact with the cube simulator.

`m`:
Press <kbd>m</kbd> to enter the `move execution` mode. It prompts the user to enter a move string using the standard Rubik's cube <a href="https://en.wikipedia.org/wiki/Rubik%27s_Cube#Move_notation" target="_blank">move</a> notation. This will render the new state of the cube after the execution.

`a`:
Press <kbd>a</kbd> to enter the `animation` mode. It is similar to the `m` mode, but it also displays the intermediate stages of the cube while the moves are being executed.

`c`:
<kbd>c</kbd> is used to clear the previous scrambles and return the cube back to its solved state. 
