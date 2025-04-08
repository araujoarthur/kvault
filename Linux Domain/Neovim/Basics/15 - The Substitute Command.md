---
id: 15 - The Substitute Command
aliases: []
tags: []
---

# The Substitute Command

This command has a bit of a different structure: `:s/old/new/g`. 

Because of the `/g`, it changes **all** the occurences in the line. If ommited, it would change only the first occurence.

## Other possible substitutions

- `:#,#s/old/new/g`, where `#,#` are numbers: Changes all the occurences of `old` to `new` on the range specified by `#,#` as the line numbers delimiting the beginning and the ending of the range.
- `:%s/old/new/g`: Changes all the occurences of `old` to `new` in **the whole file**.
- `:%s/old/new/gc`: Finds all the occurences of `old` in the file and *prompts* the user if it's meant to be replaced by `new` or not.
