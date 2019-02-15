# My awesome Linux conf
### How to install:
```bash
sudo pacman -Syu
sudo pacman -S i3-gaps zsh compton scrot docker-compose docker i3lock i3status i3blocks yaourt dunst --noconfirm
yaourt -S polybar code feh rofi google-chrome jetbrains-toolbox termite ttf-font-awesome ttf-font-awesome-4 terminus-font slack-desktop --noconfirm
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
sudo chsh -s /bin/zsh root 
sudo chsh -s /bin/zsh $(user)
sudo chmod -x ~/.config/polybar/scripts/check-all-updates.sh
sudo chmod -x ~/.config/polybar/scripts/pavolume.sh
```
