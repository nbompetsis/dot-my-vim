# Vim Configuration

I recently decided to change my system's Vim text editor and use a refactor of its, Neovim. 

I started using Neovim and its package manager ([Neobundle](https://github.com/Shougo/neobundle.vim)) and I loved them both. So I decided to create dot-my-vim repository as a first base information for anyone who wants to use Neovim text editor.

Neovim shares the same configuration syntax with Vim and the same config file can be used with both editors.

# Installation

## Neovim

1. Install Neovim on your system

More information about Neovim installation can be found [here](https://github.com/neovim/neovim)

## Neobundle - Neovim package manager

1. Download Neobundle source code
```
$ mkdir ~/.vim/bundle
$ git clone https://github.com/Shougo/neobundle.vim ~/.vim/bundle/neobundle.vim
```

2. Configuration .vimrc file

```
Configure plugins :
.vimrc
```

More information about Neobundle can be found [here](https://github.com/Shougo/neobundle.vim)


##  Install vim plugins

When you want to setup a new vim plugin, make the following steps.

For example, you decide to install [vim-fugitive](https://github.com/tpope/vim-fugitive)

Write the following line to your .vimrc file
```
NeoBundle 'tpope/vim-fugitive'
```
After that 

```
Launch vim
run :NeoBundleInstall
```

# Screenshots

![screen shot 2017-4-8](https://cloud.githubusercontent.com/assets/11991105/25785849/8ce3ba26-3392-11e7-9eaf-0931e5e38d95.png)

