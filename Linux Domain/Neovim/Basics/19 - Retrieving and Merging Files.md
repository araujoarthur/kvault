---
id: 19 - Retrieving and Merging Files
aliases: []
tags: []
---

# Retrieving and Merging Files

To retrieve the content of a different file than the one you're currently working into **and** place it in the current cursor position you can use the command `:r [STREAM_NAME]`.

The *STREAM_NAME* can be actually any stream, it can be a **file name**, but also the output of an external command to *stdout*, for example `:r !ls` runs the `ls` external command writes its result to the current cursor position.
