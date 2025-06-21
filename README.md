# Prerequisites

### Install a Nerd font & use it in the terminal

[Nerd Fonts website](https://www.nerdfonts.com/)


# Install vim 

### 1.Insall vim 
```bash
sudo app update 
sudo apt install vim 
``` 
### 2.VIM config file
```bash
vim ~/.vimrc
```
**paste the content to the file**

### 3.Install tmux 
```bash
sudo apt install tmux
```
### 4.TMUX config file 
```bash
nano ~/.tmux.conf
```
**paste the content to the file**

### 5.Install the Catppuccin theme for tmux 

```bash
mkdir -p ~/.config/tmux/plugins/catppuccin

git clone -b v2.1.0 https://github.com/catppuccin/tmux.git ~/.config/tmux/plugins/catppuccin/tmux

$ git clone https://github.com/tmux-plugins/tmux-cpu ~/.config/tmux/plugins/
```
### 6.run this command to apply changes
```bash
tmux source-file ~/.tmux.conf
```
---


