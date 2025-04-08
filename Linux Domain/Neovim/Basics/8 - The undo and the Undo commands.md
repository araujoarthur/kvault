---
id: 8 - The undo and the Undo commands
aliases: []
tags: []
---

# The (u)ndo and the (U)ndo commands

There are two undo commands in VIM: The (u)ndo is executed by, in normal mode, just typing the lowercase `u` and just undo the latest command. 

The command (U)ndo is executed by, in normal mode, typing the uppercase `U`, and it undo all modifications made in that specific line. 

As they are different commands, it's worth of note that `u` can undo the Undo of `U` and vice versa.

Lastly, there's also the **REDO** command, executed by pressing `CTRL + R`, and it undo the undos.
