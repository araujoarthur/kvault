---
id: 5 - Change Command Format
aliases: []
tags: []
---
# The Change Commands Format, Motions and Counts

The general format for a change command (it is, the ones that change something in the buffer) is:

```
operator [number] [motion]
```

A list of possible motions is displayed at [[6 - List of Motions]].

## Using a motion alone

You can use a motion to go to specific places in a text in normal mode by typing either `w`, `e` or `$`.

## Using a motion with a count.

You can also set the amount of the same motion to be executed by appending a number **before** the motion, for example:

```
2w
```

Goes to the start of the next second word. 

Similarly, this will work when using motions in the context of an operator, for example:

```
d2w
```

Will delete text until the start of the next second word.
