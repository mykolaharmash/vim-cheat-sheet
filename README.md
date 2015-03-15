## VIM cheat sheet

### :Commands

### Visual mode
* :"+y - yank to "+" register to put block in system clipboard

#### Buffers
* :bufdo e! - re-read all buffers from disk (e.g. after "git pull")
* :"_d - delete line to "black hole" buffer to note pollute registers

#### Tabs
* :tabm i - move tab to i-position (count from 0)

#### Plugins
* :CtrlPClearAllCaches - clear cache of CtrlP plugin, if we have new files to search

* * *

### Shortcuts

* Ctrl + l - refresh screen
* 0D - delete all text in line
* ^D - delete all text in line starting from first non-blank character
* gg=G - reindent file

* * *

### Custom Key Maps

* nmap ,d :b#<bar>bd#<CR> - switch to previous buffer && close current

* * *

### Usefull configs

* autocmd BufLeave,FocusLost * silent! wall - autosave buffer on focus lost
