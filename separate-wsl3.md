# How to create separate copy of WSL distro


wsl --export Ubuntu-20.04 ubuntu.tar
wsl --import Ubuntu2 .\Ubuntu2 ubuntu.tar
wsl -d UbuntuRuby -u user

## Errors

no any sign of in drop-down menu of terminal
