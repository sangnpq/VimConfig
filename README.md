# VimConfig

1. Check vim version > 7.4
2. sudo apt install build-essential cmake python3-dev
3. gedit ~/.vimrc

'''VimL Script
set nocompatible              " required
filetype off                  " required

" set the runtime path to include Vundle and initialize
set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()

Plugin 'gmarik/Vundle.vim'

Bundle 'Valloric/YouCompleteMe'

call vundle#end()            " required
filetype plugin indent on    " required
'''

4. vim -> :PluginInstall
5. cd ~/.vim/bundle/YouCompleteMe && ./install.py
