# Gentoo Script
This is a gentoo deployment script created by Mental Outlaw.

## Installation process
- Run `setup_gentoo.sh`.

It will prompt you to provision your disk, or you can auto provision using my recommended format.
The script is going to prompt you to answer several questions to configure your installation. After this the setup will do its thing. The setup takes several minutes.

When this finishes you'll have a working Gentoo installation with my minimal kernel config. 
- Use flags, exit the chroot, remove the live cd and reboot.

From here you could go on and customize Gentoo to your liking, or deploy my included "rice" (GUI configuration and dotfiles) with`sudo deploy_rice.sh` I currently  use dwm, pcmanfm, zsh, bash, and vim.

You can also run `install_software.sh` to install a list of software that I use on Gentoo.

## About
[YouTube channel](https://www.youtube.com/user/MentalOutlawStudios) 
