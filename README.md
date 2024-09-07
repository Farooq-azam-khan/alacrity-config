# alacrity-config

0. install alacrity
1. install `meslolg` nerd font
```bash
# pick a font: [https://www.nerdfonts.com/font-downloads](https://www.nerdfonts.com/font-downloads)
 mkdir ~/.local/share/fonts
wget -O ~/.local/share/fonts/Agave.zip ~/. https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/Agave.zip
# unzip in fonts dir 
cd ~/.local/share/fonts
unzip Agave.zip

# update cache 
fc-cache -f -v

# cleanup
rm Agave.zip
```
2. `mkdir -p ~/.config/alacritty/`
3. install themes here https://github.com/alacritty/alacritty-theme
4. donwload `alacritty.toml` into `~/.config/alacritty`
