# Vim  

Specifically for my vim keybinds in vscode (most are default).  

- [Clipboard](#clipboard)
- [Editing](#editing)
- [Marks](#marks)
- [Navigating](#navigating)
    * [General Navigating](#general-navigating)
    * [Word Navigating](#word-navigating)
    * [Line/Cursor Navigating](#linecursor-navigating)
    * [Character Navigating](#character-navigating)
    * [Document Navigating](#document-navigating)
    * [Window](#window) 
- [Search](#search)
- [Miscellaneous](#miscellaneous-personal)

## Clipboard
| Command | Result                                      |
|---------|---------------------------------------------|
| `y`     | Copy                                        |
| `yy`    | Yank (copy) line                            |
| `p`     | Paste below cursor                          |
| `]p`    | Past below cursor and match indentation     |
| `P`     | Past above cursor                           |
| `]P`    | Past above cursor and match indentation     |  
| `dd`    | Delete (cut) line                           |
| `x`     | Delete (cut) character                      |    
| `D`     | Delete (cut) to the end of line             |

## Editing
| Command   | Result                                                            |
|-----------|-------------------------------------------------------------------|
| `u`       | Undo                                                              |
| `<C-r>`   | Redo                                                              |
| `.`       | Repeat last command                                               |
| `<C-h>`   | Delete the character before the cursor in **insert mode**         |
| `<C-w>`   | Delete the word before the cursor during **insert mode**          | 
| `<Esc>`   | Exit insert mode                                                  |       
| `>>`      | Indent (move right) line one tab                                  |
| `<<`      | De-indent (move left) line on tab                                 | 
| `ciw`     | Change inner word                                                 |
| `ci{`     | Change inside brackets                                            |
| `ca{`     | Delete brackets and contents                                      | 

## Marks 
| Command               | Result                                |    
|-----------------------|---------------------------------------|
| `:marks`              | List of marks                         |
| `ma`                  | Set current position for mark A       |
| `` `a``               | Jump to position of mark A            |
| ``y`a``               | Yank text from position of mark A     |  
| `:delmarks!`          | Delete all marks                      |
| `:delmarks <mark>`    | Delete specific mark                  |

## Navigation  
### General Navigating 
| Command | Result                           |
|---------|----------------------------------|
| `<C-u>` | Half page up                     |
| `<C-d>` | Half page down                   |
| `<C-b>` | Page up                          |
| `<C-f>` | Page down                        |

### Word Navigating 
| Command | Result                      |
|---------|-----------------------------|
| `b`     | Previous word               |
| `w`     | Next word                   |
| `ge`    | Previous end of word        |
| `e`     | Next end of word            |
| `ea`    | Insert at the end of word   |

### Line/Cursor Navigating  
| Command | Result                                              |
|---------|-----------------------------------------------------|
| `h`     | Move cursor left                                    |
| `j`     | Move cursor down                                    |
| `k`     | Move cursor up                                      |
| `l`     | Move cursor right                                   |
| `0`     | Start of Line                                       |
| `$`     | End of line                                         |
| `^`     | Jump to first non-blank character of the line       |
| `g_`    | Jump to last non-blank character of the line        |
| `i`     | Enter insert mode before cursor                     |
| `a`     | Enter insert mode after cursor                      |
| `I`     | Go to the start of the line and enter insert mode   |
| `A`     | Go to the end of the line and enter insert mode     |
| `o`     | Insert line below cursor and enter insert mode      |
| `O`     | Insert line above cursor and enter insert mode      |
| `{`     | Move up code block                                  |
| `}`     | Move down code block                                |   
| `<C-o>` | Go back to previous line                            |
 
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

## Search 
| Command           | Result                                |
|-------------------|---------------------------------------|
| `/`               | Search forward for pattern            |                    
| `?`               | Search backward for pattern           |                                       
| `n`               | Repeat search in same direction       |
| `N`               | Repeat search in opposite direction   | 

## Miscellaneous (Personal)
| Command       | Result        |
|---------------|---------------|
| `<C-Alt-V>`   | Toggle vim    |