# Git Rebase keybindings

Adds shortcuts to the Git Rebase Message language editor to make quick changes to the instructions on each line.

Each line of an interactive Git rebase starts with the command to perform on that commit. Type the character for the command to replace the command on the line or insert a new command.

Select multiple lines (e.g. using vim visual line mode) then tap a key to apply that command to all selected lines.

### vim

This extension was designed primarily to be used when a vim extension is also installed. If a vim extension is active, these keybinds are only active in Normal mode, otherwise the character is handled as usual (e.g. typed in insert mode). This is necessary to be able to type on an exec line for example.

If a vim extension is not installed, some keybindings may not be available and some functionality may be lost in the editor (for example, being unable to normally type in an exec line).

## Keybindings

These keys set the current line to this command:

| key          | command |
| ------------ | ------- |
| <kbd>p</kbd> | pick    |
| <kbd>r</kbd> | reword  |
| <kbd>e</kbd> | edit    |
| <kbd>s</kbd> | squash  |
| <kbd>f</kbd> | fixup   |

These keys insert a new line below set to the command:

| key          | command |
| ------------ | ------- |
| <kbd>b</kbd> | break   |
| <kbd>x</kbd> | exec    |

*<kbd>x</kbd> (exec) is only available in vim and switches to insert mode.*
