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






## win-setup ##

### Install driver ###
Main driver and nvidia driver

### Install app ###
.\app-installer.bat

Install EVkeys







## Fedora ##
- update dnf

sudo nano /etc/dnf/dnf.conf


fastestmirror=True

max_parallel_downloads=10

defaultyes=True

keepcache=True


dnf clean all

sudo dnf update


- RPM fusion

sudo dnf install https://mirrors.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm https://mirrors.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm

sudo dnf groupupdate core

- Install flatpack

 flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo

- Add media codec
  
sudo dnf groupupdate multimedia --setop="install_weak_deps=False" --exclude=PackageKit-gstreamer-plugin

sudo dnf groupupdate sound-and-video

- Check and Install VGA driver

sudo nano /etc/gdm/custom.conf -> uncomment WaylandEnable=false

lspci | grep VGA

sudo dnf install akmod-nvidia

- Install apps:

  udo dnf instpython3-pip steam htop neofetch




## nighttab-setup ##
Copy setting from nighttab.json -> modify the background image

## discord-setup ##
Download BetterDiscord -> Change the theme


