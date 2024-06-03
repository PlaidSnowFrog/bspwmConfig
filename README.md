<p>Install dependencies</p>
```sudo apt update && sudo apt install bspwm sxhkd polybar picom rofi dunst feh alacritty thunar```
<p>Make the folders for configs</p>
```cd $HOME/.config/ && mkdir bspwm/ && mkdir dunst/ && mkdir picom/ && sxhkd```
<p>Then clone the repo and cd into it</p>
```git clone https://github.com/PlaidSnowFrog/bspwmConfig/ && cd bspwmConfig```
<p>And put everything in the config folder</p>
```cp montblanc.jpg $HOME/Pictures/backgrounds/ && cp bspwm/bspwmrc $HOME/.config/bspwm/ && cp dunst/dunstrc $HOME/.config/dunst/ && cp picom/picom.conf $HOME/.config/picom/ && cp sxhkd/sxhkdrc $HOME/.config/sxhkd```
