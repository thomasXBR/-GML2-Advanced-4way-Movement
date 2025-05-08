# Advanced 4 way movement in GML2 code for 2D games
For this GML2 project I named the player sprites and object as "spr_player" and "obj_player";
<br>
<br>
The sprite and object for the walls are "spr_wall" and "obj_wall";
<br>
<br>
You may name these however you please.
<br>
<br>
I used the arrow keys only as an example of input for movement, but if you wish to use other keys like W, A, S and D you can write the binds like this:
```
var _right = keyboard_check(ord("A"));
var _left = keyboard_check(ord("D"));
var _up = keyboard_check(ord("W"));
var _down = keyboard_check(ord("S"));
```
