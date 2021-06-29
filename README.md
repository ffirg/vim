# vim
vi/vim editor goodies


```bash
cat ~/.vimrc

" cracking guide at https://dougblack.io/words/a-good-vimrc.html
set tabstop=2                               " a tab = 2 spaces
set softtabstop=2                           " no. spaces on backspace
set expandtab                               " turn tabs into spaces
set autoindent                              " autoindent!
set wildmenu                                " autocomplete for filenames
set showmatch                               " parenthesis matching
syntax on                                   " syntax!
colorscheme default                         " add a little colour to our live
set incsearch                               " search as chars entered
set hlsearch                                " highlight matches
let mapleader=","                           " leader is a comma
nnoremap <leader><space> :nohlsearch<CR>    " leader,space disables search highlighting
```
