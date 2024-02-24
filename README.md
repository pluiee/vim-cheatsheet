# Vim Cheatsheet
>Note: All actions are based on the [VSCode Vim Extension](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim).

## Cursor moves
|Move to the...|Key|
|:--|:--|
|left|`h`|
|right|`l`|
|down|`j`|
|up|`k`|
|start of the line|`0`|
|first non-blank character of the line|`^`|
|end of the line|`$`|
|27th line|`27gg` or `27G`|
|move 5 lines down|`5j`|
|start of the next word|`w`|
|start of the current word|`b`|
|end of the current word|`e`|
|start of the file|`gg`|
|end of the file|`G`|
|half page up|`Ctrl` + `u`|
|half page down|`Ctrl` + `d`|

## Entering Insert mode 
|Location after entering|Key|
|:--|:--|
|before the cursor|`i`|
|start of the line|`I`|
|after the cursor|`a`|
|end of the line|`A`|
|new line under the current line|`o`|
|new line above the current line|`O`|

|Insert while...|Key|
|:--|:--|
|deleting the selected block|`c`|
|deleting the current line after the cursor|`C`|
|deleting the current word|`ciw`|
|deleting all contents inside the bracket|`ci{`|

## Entering Visual mode
|Function|Key|
|:--|:--|
|enter visual mode|`v`|
|enter visual line mode|`V`|
|enter visual block mode|`Ctrl`+`v`|
|select the latest block|`gv`|

## Surround
|Function|Key|
|:--|:--|
|surround current word with quotes|`ysiw"`|
|surround current paragraph with brackets|`ysip{`|
|surround current line with parantheses|`yss(`|
|surround visual block with quotes|`S"`|

## Exit to Normal mode
`Esc` or `Ctrl` + `[`
