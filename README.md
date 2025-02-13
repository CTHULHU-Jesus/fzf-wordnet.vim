# fzf-wordnet
[![CI](https://github.com/CTHULHU-Jesus/fzf-wordnet.vim/actions/workflows/main.yml/badge.svg)](https://github.com/Avi-D-coder/fzf-wordnet.vim/actions/workflows/main.yml)

Dictionary completion powered by FZF and Wordnet for vim and your terminal.

## Vim/NeoVim
With vim-plug:

```vim
Plug 'junegunn/fzf.vim'
Plug 'Avi-D-coder/fzf-wordnet.vim'

imap <C-S> <Plug>(fzf-complete-wordnet)
nmap <C-d> :DefineWord <C-R>=expand('<cword>')<CR><CR>
```
![ezgif-4-32dc75db6d68](https://user-images.githubusercontent.com/29133776/60706168-de395500-9ed6-11e9-996c-58d2996c59ba.gif)

## Shell

```bash
export PATH="$XDG_CONFIG_HOME/nvim/plugged/fzf-wordnet.vim/bin:$PATH"
```
$ `spell`

## Credit
Shell scripts derived with permision from @ddrscott's blog post and @balta2ar's comment.
