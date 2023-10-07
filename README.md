# M1 MACBOOK DEVELOPER SETUP

### Enable syntax highlighting in Vim
```vim
$cp -r /usr/share/vim/vimrc ~/.vimrc

#add this line at the bottom

filetype plugin indent on
syntax on
```
```vim
#To use on other file types

$vi filename.py

#type 
:syntax on
```
### Homebrew Installation
https://brew.sh/
```vim
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
```vim
$brew install neovim
```

