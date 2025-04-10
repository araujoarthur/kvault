---
id: 10 - The Replace Command
aliases: []
tags: []
---

# The Replace Command


## Single Character (`rx`)

The replace command, executed by typing `rx` where `x` is actually any character, replaces the character currently under the cursor by the specified `x`.

## Multiple Characters (`Rxxx....`)

The replace command can also be the uppercase *R*. In this version, it can be followed by multiple characters to replace the same amount of characters in the original text. For example:

-> The lazy brown fox does not run.
^^^^^^^^^^^^^^^^^^^ (cursor is on |f|ox)

using the command `Rdog does actually sleep.` results in:

-> The lazy brown dog does actually sleep.

>[!note]
> Replace is just like insertion mode, with the only difference being that each typed character deletes an existing character **in the line**, and just appends when there are no more characters to delete.
