# Vim  

Specifically for my vim keybinds in vscode (most are default).  

- [Clipboard](#clipboard)
- [Editing](#editing)
- [Navigating](#navigating)
    * [General Navigating](#general-navigating)
    * [Word Navigating](#word-navigating)
    * [Line Navigating](#line-navigating)
    * [Character Navigating](#character-navigating)
    * [Document Navigating](#document-navigating)
    * [Window](#window)
- [Miscellaneous](#miscellaneous)

## Clipboard
| Command | Result               |
|---------|----------------------|
| `y`     | Copy                 |
| `p`     | Paste                |

## Editing
| Command | Result               |
|---------|----------------------|
| `x`     | Delete character     |
| `dd`    | Delete line          |
| `u`     | Undo                 |
| `<C-R>` | Redo                 |
| `.`     | Repeat last command  |

## Navigation  
### General Navigating 
| Command | Result                           |
|---------|----------------------------------|
| `h`     | Move cursor left                 |
| `j`     | Move cursor down                 |
| `k`     | Move cursor up                   |
| `l`     | Move cursor right                |
| `<C-U>` | Half page up                     |
| `<C-D>` | Half page down                   |
| `<C-B>` | Page up                          |
| `<c-f>` | Page down                        |
| `{`     | Move up code block               |
| `}`     | Move down code block             |   
| `<C-O>` | Go back to previous line         |
| `H`     | Move to top of screen            |
| `M`     | Move to middle of screen         |
| `L`     | Move to bottom of screen         |

### Word Navigating 
| Command | Result               |
|---------|----------------------|
| `b`     | Previous word        |
| `w`     | Next word            |
| `ge`    | Previous end of word |
| `e`     | Next end of word     |

### Line Navigating  
| Command | Result                                          |
|---------|-------------------------------------------------|
| `0`     | Start of Line                                   |
| `$`     | End of line                                     |
| `^`     | Jump to first non-blank character of the line   |
| `g_`    | Jump to last non-blank character of the line    |

### Character Navigating  
| Command | Result                      |
|---------|-----------------------------|
| `fc`    | Go forward to character c   |
| `Fc`    | Go backward to character c  |
| `%`     | Move to matching character  |

### Document Navigating  
| Command | Result               |
|---------|----------------------|
| `gg`    | Jump to first line   |
| `G`     | Jump to last line    |
| `:n`    | Go to line n         |
| `nG`    | Go to line n         |

### Window
| Command | Result                  |
|---------|-------------------------|
| `zz`    | Center this line        |
| `zt`    | Top this line           |
| `zb`    | Bottom this line        |
| `H`     | Move to top of screen   |
| `M`     | Move to middle of screen|
| `L`     | Move to bottom of screen|

## Miscellaneous  
| Command       | Result        |
|---------------|---------------|
| `<C-Alt-V>`   | Toggle vim    |