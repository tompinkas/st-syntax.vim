# Vim Syntax File for ST (Structured Text for PLC Programming) 
This is very basic syntax file, a starting point for anybody, who wants to edit PLC programs in Vim. Anybody who would like to contribute is welcomed.

## Installation
* Download [stplc.vim](https://github.com/tompinkas/st-syntax.vim/edit/master/stplc.vim)
* Copy it to the folder ~/.vim/syntax

## Running
### Manually
When you open ST file in Vim, use commands

```vim
:set syntax=stplc
:syntax on
```

### Automatically
To highlight syntax automatically, set the file type in ~/.vimrc or /etc/vim/vimrc. For example, when exported from Beckhoff TwinCAT PLC Control IDE, files come with extension .EXP, thus .vimrc:
```vim
au BufNewFile,BufRead *.EXP set filetype=stplc
```
Similarly, B&R Automation Studio IDE save files with extension .st, so add to .vimrc:
```vim
au BufNewFile,BufRead *.st set filetype=stplc
```


