# EdgeDB Vim Syntax

This is a package with syntax highlighter for EdgeDB languages: EdgeQL and
ESDL (EdgeDB Schema Definition Language).  The plugin is designed to work with
vim and neovim.

# Usage

## Manual Clone
Copy this repo in your vim pack directory. More info in [Vim docs](https://github.com/vim/vim/blob/247bf0de465411e4ebb1c0fe1a9e07f4a7f77e91/runtime/doc/repeat.txt#L515)

`git clone https://github.com/edgedb/edgedb-vim ~/.vim/pack/edgedb/start/edgedb`

### For Neovim using [Packer](https://github.com/wbthomason/packer.nvim)

```
    require('packer').startup(function(use)   
        use 'edgedb/edgedb-vim'
    end)
```

## Using a plugin manager
Use https://github.com/VundleVim/Vundle.vim or https://github.com/junegunn/vim-plug.

Files with extensions `esdl` and `edgeql` will be properly syntax highlighted.

