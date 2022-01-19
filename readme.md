# VIM commands Helps

### Press Tab to access edit mode
* **[shift?]i** enable insert mode, shift start on the begin of line
* **[shift?]o** break line after current line, shift break before
* **[size?]yy** copy the current line, size define the amount of lines to be copied
* **p** past the copies line
* **[size?]dd** cut the current line, size define the amount of lines to be copied
* **u** undo
* **ctrl+r** redo
* **v** access visual mode
	* **y** copy the selected text
	* **d** cut the select text
	* **[shift?]x** delete from left to right, shift to delete start from right
	
* **Esc command**
	* **[:wq|:x|shift+zz]** write and quit
	* **:w [filename]** rename the file
	* **:r [filename]** append the content of filename
	* **:split [filename]** split screen, open another file(ctrl+ww change between screen)
	* **[/|?]/word** search for the word in the current file (/=from top to bottom, ? = from bottom to top) using 'n' you continue to the next word found
	* **:%s/find/replace/g** find and replace the word defined in 'find'
		* **%** to search in all lines, you can use a specific line (1), or an interval of lines (1,10)
		* **g** in the final replace all occurrences in the line
	* **:sintax [on|off]** enable disable sintax in the current file (must be an extension)
	* **:ab [alias] [text]** create an abbreviation to use in vim, use the abbreviation and space to replace in the editing
		* **alias** define the alias of the abbreviation
		* **text** define the content of the abbreviation
	* **:[range]sort[!]** sort lines Alphabetically
		* **range(optional)** define the range of the ordenation, use ',' to specify the range of the lines
		* **!(optional)** define the reverse sort
	* **:set [command]**
		* **number** enable line number in the file
		* **nonu** disable line number in the file
		* **ai** enable auto indent
		* **noai** disable auto indent
		* **visulabell** blink the screen without song warn
		* **ic** enable ignore case
		* **noic** enable ignore case
		* **bg=[dark|light]** change background of editor
		* **tabstop=[size]** define the amount of space in TAB
		* **showmatch** display the context of block with ({}, [], ())
