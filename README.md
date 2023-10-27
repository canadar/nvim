**Storage for my Neovim config**

First, you'll need to [Install Lua](https://www.lua.org/download.html)

### Install [Neovim](https://github.com/neovim/neovim/wiki/Installing-Neovim)

[I use Packer](https://github.com/wbthomason/packer.nvim) as my plugin manager, so you'll need at least Neovim v0.5.0+

How I install Neovim for WSL Ubuntu 20.04

```shell
sudo add-apt-repository ppa:neovim-ppa/unstable -y
sudo apt update
sudo apt install neovim
```
### Clone
Clone this repo into the default configuration directory for your system.

* Linx - `~/.config/(clone here)`
* Windows - `%LocalAppData%\(clone here)`

### Install Packer

### For Linux
```shell
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

### For Windows
```shell
git clone https://github.com/wbthomason/packer.nvim "$env:LOCALAPPDATA\nvim-data\site\pack\packer\start\packer.nvim"
```

From here, if you have Neovim open, restart Neovim and navigate to lua/plugin and open `plugins.lua`. Use the `:so` command to source the file, and you should be able to run `:PackerSync` to install all of the plugins. Restart once again and you should be good to go! 👍
