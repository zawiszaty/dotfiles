# My awesome Linux conf
![Image of linux](https://github.com/zawiszaty/dotfiles/blob/master/screenshots/2019-02-15-21:14:00-screenshot.png)
![Image of linux](https://github.com/zawiszaty/dotfiles/blob/master/screenshots/2019-02-15-21:14:43-screenshot.png)
### What I use:
* i3-gaps
* polybar
* dunst (notification)
* compton (shadow)
* rofi
* termite
### How to install:
```bash
sudo pacman -Syu
sudo pacman -S i3-gaps zsh compton scrot docker-compose docker i3lock i3status i3blocks yaourt dunst --noconfirm
yaourt -S polybar code feh rofi google-chrome jetbrains-toolbox termite ttf-font-awesome ttf-font-awesome-4 terminus-font slack-desktop trizen --noconfirm
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
sudo chsh -s /bin/zsh root 
sudo chsh -s /bin/zsh $(user)
sudo chmod -x ~/.config/polybar/scripts/check-all-updates.sh
sudo chmod -x ~/.config/polybar/scripts/pavolume.sh
echo 'alias dotfiles="/usr/bin/git --git-dir=$HOME/dotfiles --work-tree=$HOME"' >> $HOME/.zshrc
source ~/.zshrc
echo "dotfiles" >> .gitignore
git clone --bare https://github.com/zawiszaty/dotfilest $HOME/dotfiles
dotfiles checkout
dotfiles config --local status.showUntrackedFiles no
```
### Where did I get my inspiration?
- https://github.com/michal-franc/dotfiles
- https://gitlab.com/dwt1/dotfiles
