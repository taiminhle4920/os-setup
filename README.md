# os-setup

## mac-setup ##

### Install homebrew ###
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

### Change mod of the shell ###
chmod +x app.sh

### Run the script ###
./app.sh

#### Extra command ####
- Adding python3 to shell


echo "alias python=/usr/bin/python3" >> ~/.zshrc

echo 'export PATH="$(brew --prefix)/opt/python@3/libexec/bin:$PATH"' >> ~/.zshrc

- Change screenshot to jpg

defaults write com.apple.screencapture type jpg

- Make dock appear instance

defaults write com.apple.dock autohide-delay -float 0; defaults write com.apple.dock autohide-time-modifier -int 0 ;killall Dock


- Hide all icon on desktop

defaults write com.apple.finder CreateDesktop false; killall Finder


## win-setup ##

### Install driver ###
Main driver and nvidia driver

### Install app ###
.\app-installer.bat

Install EVkeys



## Ubuntu ##

Run command.sh -> ./commands.sh

### Mutter rounded ###
https://github.com/yilozt/mutter-rounded

gjs dist/mutter_settings.js



## nighttab-setup ##
Copy setting from nighttab.json -> modify the background image

## discord-setup ##
Download BetterDiscord -> Change the theme


