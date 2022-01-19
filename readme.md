# VIM commands Helps

| ESC Mode  	| Description	|
| -------------: | ------------- |
| **i**      		| (shift opptionally) enable insert mode, shift start on the begin of line |
| **o**      		| (shift opptionally) break line after current line, shift break before  |
| **yy**     		| (shift opptionally) copy the current line, size define the amount of lines to be copied  |
| **dd**     		| (shift opptionally) cut the current line, size define the amount of lines to be copied  |
| **ctrl+r**        	| redo  |
| **u**             	| undo  |
| **p**             	| paste the clipboard  |
| **:wq**		| write and quit |
| **:x** 		| write and quit |
| **shift+zz** 		| write and quit |
| **:w filename** 	| rename the file |
| **:r filename** 	| append the content of filename |
| **:split filename** 	| split screen, open another file(ctrl+ww change between screen) |
| **/text** 		| search for the word in the current file from top to bottom using 'n' you continue to the next word found |
| **?text** 		| search for the word in the current file from bottom to top using 'n' you continue to the next word found |
| **:/find/replace/** 	| find and replace the word defined in 'find' * teste * teste |
| **:sintax on\|off** 	| enable disable sintax in the current file (must be an extension) |
| **:ab alias text** 	| create an abbreviation to use in vim, use the abbreviation and space to replace in the editing |
| **:sort** 		| sort lines Alphabetically |
| **:N,Nsort** 		| define the range of the ordenation, use ',' to specify the range of the lines |
| **sort!** 		| define the reverse sort |
| **v** 	    	| Visual Mode       |

## Visual Mode

| Visual Mode  	| Description	|
| -------------: | ------------- |
| **y**		| copy the selected text 	|
| **d**		| cut the select text  		|
| **x** | (shift opptionally) delete from left to right, shift to delete start from right|

## Find and replace options

| :/find/replace/ Mode | Description	|
| -----------------: | ------------- |
| **%** | to search in all lines, you can use a specific line (1), or an interval of lines (1,10) |
| **g** | in the final replace all occurrences in the line

| :ab Mode | Description	|
| -----------------: | ------------- |
| **alias** | define the alias of the abbreviation |
| **text** | define the content of the abbreviation |

# Set options

| :set Mode 		| Description	|
| --------------------: | ------------- |
| **number** 		| enable line number in the file |
| **nonu** 		| disable line number in the file |
| **ai** 		| enable auto indent |
| **noai** 		| disable auto indent |
| **visulabell** 	| blink the screen without song warn |
| **ic** 		| enable ignore case |
| **noic** 		| enable ignore case |
| **bg=[dark\|light]** 	| change background of editor |
| **tabstop=size** 	| define the amount of space in TAB |
| **showmatch** 	    | display the context of block with ({}, [], ())|
