# Git Rebase Shortcuts

Adds shortcuts to the Git Rebase Message language editor to make quick changes to the instructions on each line.

Each line of an interactive Git rebase starts with the command to perform on that commit. Type the character for the command to replace the command on the line or insert a new command.

Only applies the command when **a vim extension is active and in Normal mode**, otherwise the character is handled normally (e.g. typed in insert mode). This is necessary to be able to type on an exec line for example.

| key | command                                                    |
| --- | ---------------------------------------------------------- |
| p   | pick                                                       |
| r   | reword                                                     |
| e   | edit                                                       |
| s   | squash                                                     |
| f   | fixup                                                      |
| b   | break (inserted on new line below)                         |
| x   | exec (inserted on new line below, and insert mode entered) |
