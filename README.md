# ocular-brainfuck

###A visually helpful brainfuck interpreter written in JavaScript

It displays the tape, which cell the pointer is currently pointing to, and which instruction is currently executed.

You can run, pause and continue the script, or you can execute it step by step.

You can set the delay between two commands from 500ms to 0ms, where a value of 0 is of course just an indication for "as fast as your browser can go"

Porgrams can be run in single steps or in a sped up mode which executes blocks of equal commands like `+++++++` or `<<<<<<` at once. In  this mode the command blocks `[-]`. `[+]`. `[<]` and `[>]` are also sped up.

You can set the cells to be arbirarily large (as a JavaScript number) or let them wrap at 255 (like a byte)

To do:

 - It's incompatible with the most used interpreters in that the tape can go left from the first cell. I might add an option for that.
 
 - Maybe I'll parse for blocks that move cells from one place to another, because that would speed it up even more.


Use as you wish. There might of course be some bugs.



