# Cheatsheet


2. ### Vim Commands
	1. #### Text Commands
		1. `ciw '' Esc p`  -  Wrap current word with `''`
	2. #### Misc.
		1. `<C-z>`  -  Leaves vim momentarily to get to the shell environment.
		2.  `fg`    -  After using previous command and doing whatever, use this to return to vim.
		3. **Time Travel**
			1. :earlier 35s  -  Goes back 35 seconds to where the buffer was at that point
			2. :later 15s    -  If the previous command overshoots, can go forward to where you want.
		4. **File Encryption**
			1. `:X` 										 -  Will encrypt the file asking for a pass key and phrase.
			2.  `:set key=` 						 -  Will undo file encryption.
			3.  `:setlocal cm=blowfish`  -  Better file encryption.
		5. `:r!<Bash command>` 				 -  Outputs result of bash command into current buffer.
	1. UltiSnips
		1. Anything wrapped in ` ` ` will be interpolated by Ultisnips as a bash command and input
		the result.
		2. `<C-j>`  - Go to next tabstop --  areas denoted with $<Number>
		3. `<C-K>`  -  Go to previous tabstop

	1. Good online Vim Tutorials
		1. https://www.digitalocean.com/community/tutorials/how-to-use-vim-for-advanced-editing-of-plain-text-or-code-on-a-vps--2
		2. http://yannesposito.com/Scratch/en/blog/Learn-Vim-Progressively/
1. ### Bash Commands
	1. Date
		1. `date`             -  Tue Nov 10 10:25:26 CST 2015
		2. `date +%Y`         -  2015
		3. `date +%Y/%m/%d`   -  2015/11/10



