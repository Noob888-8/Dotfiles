I use EndeavourOS, btw (Arch basically)


#### Dotfiles

Very easy to understand hyprland configuration for noobs (like me)
Everything is explained


**OS:** take a guess
**VM:** Hyprland
**Wallpaper:** Hyprpaper - https://github.com/dharmx/walls/blob/main/anime/a_log_cabin_in_the_woods.png
**Bar:** Waybar
**Terminal:** kitty
**Application launcher:** rofi

###### TUTORIAL!!!

Download command:
```
cd ~ 
git clone https://github.com/Noob888-8/Dotfiles.git
```

This will import the dotfiles to your home directory.

Search how to move files using commands and move the original files of the configs to a backup directory (make a backup directory in your ~ directory with- mkdir backups -so you can revert to your old configs if something goes wrong.

Your configurations for hyprland, waybar, hyprpaper are all in ~/.config, cd into that directory and then into the directory of where you want to change the config.
There, do this command to import the files.

```
cp ~/Dotfiles/name-of-the-dotfile-config-folder/name-of-the-config-file ~/.config/name-of-the-config-folder

for example (for waybar, it has 2 files) :
cp ~/Dotfiles/waybar/config.jsonc ~/.config/waybar
cp ~/Dotfiles/waybar/style.css ~/.config/waybar
```
Read the hyprland config file (near line 210) first so you can set your preferred keybinds.
You can change the colors and other properties in the files with the help of the comments.

###### Have fun, keep ricing!
