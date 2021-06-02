# Dotfiles Vim

Ini adalah dotfiles dari .vimrc yang dipakai untuk nvim.

## Cara Mengaktifkannya

Buat `~/.config/nvim/init.vim` yang isinya:

```vim
set runtimepath+=~/.vim,~/.vim/after
set packpath+=~/.vim
source ~/vimrc/.vimrc
```
