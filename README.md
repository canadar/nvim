**Storage for my Neovim config**

# Setup

## Install [Neovim](https://github.com/neovim/neovim/wiki/Installing-Neovim)

[I use Packer](https://github.com/wbthomason/packer.nvim) as my plugin manager, so you'll need at least Neovim v0.5.0+

How I install Neovim for WSL Ubuntu 20.04

```shell
sudo add-apt-repository ppa:neovim-ppa/unstable -y
sudo apt update
sudo apt install neovim
```
## Install Packer

### For Linux
```shell
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

### For Windows
```shell
git clone https://github.com/wbthomason/packer.nvim "$env:LOCALAPPDATA\nvim-data\site\pack\packer\start\packer.nvim"
```
