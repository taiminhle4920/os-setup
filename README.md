# os-setup

## mac-setup ##

### Install homebrew ###
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

### Change mod of the shell ###
chmod +x app.sh

### Run the script ###
./app.sh

#### add python to .zshrc
echo 'export PATH="$(brew --prefix)/opt/python@3/libexec/bin:$PATH"' >> ~/.zshrc

## win-setup ##

### Install driver ###
Main driver and nvidia driver

### Install app ###
.\app-installer.bat

Install EVkeys


## nighttab-setup ##
Copy setting from nighttab.json -> modify the background image

## discord-setup ##
Download BetterDiscord -> Change the theme


