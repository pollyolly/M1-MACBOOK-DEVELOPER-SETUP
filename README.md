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
### Google Chrome
Allow Google Chrome to Access Local Network
```
Privacy & Security -> Local Network -> Allow Google Chrome
```
### UTM Virtual Machine
qemu-x86_64-softmmu: combined size of system firmware exceeds 8388608 bytes
```
Edit -> QEMU -> UEFI Boot: Uncheck (Disable)
```
