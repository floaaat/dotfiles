<h1 align="center">Dotfiles</h1>

## Reqs & Software

<div style="display: flex; gap: 20px;">
<ul>
  <li>listitem1.1</li>
  <li>listitem1.2</li>
</ul>
<ul>
  <li>listitem2.1</li>
  <li>listitem2.2</li>
</ul>
</div>

**hyprland ( *wm* )**\
**waybar ( *bar* )**\
**fuzzel ( *app.menu* )**\
**clipman ( *clipb.* )**\
**grimblast ( *screensh.* )**\
**ly ( *displ.m* )**

**foot ( *term* )**\
**fish ( *shell* )**\
**yazi ( *file.m* )**\
**helix ( *editor* )**\
**bottom ( *sys.mon* )**\
**fastfetch ( *fetch* )**\
**eza ( *cd* )**\
**fzf ( *findin'* )**

**firefox ( *browser* )**

***wm*** -> **hyprland**\
***bar*** -> **waybar**\
***app.menu*** -> **fuzzel**\
***clipb.*** -> **clipman**\
***screensh.*** -> **grimblast**\
***displ.m*** -> **ly**

***term*** -> **foot**\
***shell*** -> **fish**\
***file.m*** -> **yazi**\
***editor*** -> **helix**\
***sys.mon*** -> **bottom**\
***fetch*** -> **fastfetch**\
***cd*** -> **eza**\
***findin'*** -> **fzf**

***browser*** -> **firefox**

## Themes & Fonts
*GTK* -> **Catppuccin Macchiato Gtk Theme**\
*Cursor* -> **Bibata Cursors**\
*Font* -> **FiraCode Nerd Font**

## Installation
Installing software
```
sudo pacman -Suy
sudo pacman -S hyprland waybar fuzzel clipman ly foot fish yazi helix fastfetch eza fzf firefox ttf-firacode-nerd
yay -S grimblast-git bottom-git catppuccin-gtk-theme-macchiato bibata-cursor-theme
```
Copying config files
```
git clone https://github.com/floaaat/dotfiles.git ~/floaaat-dotfiles/
cp ~/floaaat-dotfiles/.config/* ~/.config/
```
Setting up themes
```
gsettings set org.gnome.desktop.interface gtk-theme catppuccin-macchiato-blue-standard+default
gsettings set org.gnome.desktop.interface icon-theme Bibata-Modern-Ice
```
Changing shell to fish
```
sudo chsh -s /usr/bin/fish
```
Enabling ly.service
```
sudo systemctl enable ly.service
```
