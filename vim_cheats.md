# Vim Cheats

### Global
| Command       | Description                      |
| -------------- | -------------------------------- |
| `K`            | Open `man` page under the cursor |
| `:ter[minal]`| Open a terminal window         |

### Cursor Movement
| Command       | Description                      |
| -------------- | -------------------------------- |
| `H       ` | Move to top of screen            |
| `M`          | Move to middle of screen         |
| `L`        | Move to bottom of screen         |
| `%`      | Move cursor to matching character |
| `^`    | Jump to first non-blank character in the line |
| `fx` | Jump to next occurrence of character x |
| `tx` | Jump to previous occurrence of character x |
| `}` | Jump to next paragraph/function/block |
| `{` |  Jump to previous paragraph/function/block |
| `zz` | Center cursor on screen |
| `zt` | Position cursor on top of the screen |
| `zb` | Position cursor on bottom of the screen |

### Insert Mode
| Command       | Description                      |
| -------------- | -------------------------------- |
| `ea` | Append at the end of the word |
| `Ctrl` + `c` | Exit insert mode |

### Editing
| Command       | Description                      |
| -------------- | -------------------------------- |
| `gwip` | Reflow paragraph |
| `g~` | Switch case up to motion |
| `cc` or `S` | Change (replace) entire line |
| `c$` or `C` | Change (replace) to the end of the line |
| `s` | Delete character and substitute text |
| `u` | Undo |
| `U` | Restore undo |

### Visual Commands
| Command       | Description                      |
| -------------- | -------------------------------- |
| `~` | Switch case |
| `>` | Shift text right |
| `<` | Shift text left |

### Visual Mode (Cut & Paste)
| Command       | Description                      |
| -------------- | -------------------------------- |
| `yy` | Yank a line |
| `Y` | Yank to the end of line |
| `D` | Delete to the end of the line |
| `x` | Delete character |
| `:3,5d` | Delete lines starting from 3 to 5 |

### Indent Text
| Command       | Description                      |
| -------------- | -------------------------------- |
| `>>` | Indent (move right) line one shiftwidth |
| `<<` | Indent (move left) line one shiftwidth |
| `]p` | Paste and adjust indent to current line |
| `3==` | Re-indent 3 lines |
| `gg=G` | Re-indent entire buffer |

### Search and Replace
| Command       | Description                      |
| -------------- | -------------------------------- |
| `/pattern` | Search for pattern |
| `?pattern` | Search backward for pattern |
| `n` | Repeat search in same direction |
| `N` | Repeat search in opposite direction |
| `:%s/old/new/g` | Replace all old with new throughout file |
| `:%s/old/new/gc` | Replace all old with new throughout file with confirmation |

### Tabs
| Command       | Description                      |
| -------------- | -------------------------------- |
| `:tabnew` | Open new or specified file in a new tab |
| `gt` or `:tabn[ext]` | Go to next tab |
| `gT` or `tabp[rev]` | Go to previous tab |
| `:tabc[lose]` | Close the current tab and all its windows |
| `:tabo[nly]` | Close all tabs except for the current one |

### Exiting
| Command       | Description                      |
| -------------- | -------------------------------- |
| `ZZ` or `:x` | Save and close file              |
| `ZQ` or `:q!` | Quit and throw away unsaved changes |
