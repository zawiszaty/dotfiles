.PHONY: start
start: install

.PHONY: install
install: ## install all stuff
		sudo pacman -S i3-wm --noconfirm
		sudo pacman -S i3lock --noconfirm
		sudo pacman -S i3status --noconfirm
		sudo pacman -S i3blocks --noconfirm
		sudo pacman -S yaourt --noconfirm
		sudo pacman -S dunst --noconfirm
		yaourt -S polybar --noconfirm
		yaourt -S rofi --noconfirm
		yaourt -S termite --noconfirm
		yaourt -S ttf-font-awesome  --noconfirm
		yaourt -S ttf-font-awesome-4  --noconfirm
		yaourt -S terminus-font --noconfirm
		yaourt -S slack-desktop --noconfirm
		yaourt -S google-chrome --noconfirm
		yaourt -S jetbrains-toolbox --noconfirm
		yaourt -S code --noconfirm
		sudo pacman -S zsh --noconfirm
		sudo pacman -S compton --noconfirm
		sudo pacman -S scrot --noconfirm
		sudo pacman -S docker --noconfirm
		sudo pacman -S docker-compose --noconfirm
		sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
		sudo chsh -s /bin/zsh root 
		sudo chsh -s /bin/zsh $USER