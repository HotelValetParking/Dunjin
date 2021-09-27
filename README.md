# Dunjin
Voice activated game master utility using Google's AIY Voice kit on a Raspberry Pi

The following is a reference to the program's objectives (TODO)

| Parse                                                               | Description                                                                                                                                                                                                                                                                                  |
| :------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `roll <y> d<x> < + / - / * / '/' x>`                   | Rolls "y" number of "x"-sided dice (those being 2, 3, 4, 6, 8, 10, 12, 20, 24, 30, 60, and 100) and applies arithmetic to the result.                                                                                                                                                                              |
| `roll/make a[n] <stat> <type> <optional: adv|disadv>`                            | Queries a database for an entity's stats and applies the modifiers to a standard (configurable for multiple kinds of games? TODO)                                                                                                                                                       |
