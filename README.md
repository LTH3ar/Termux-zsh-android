# Termux-zsh-android
Custom config files for oh-my-zsh termux, the default theme is powerlevel10k in .oh-my-zsh/custom/themes. <br />
I recommend using powerlevel10k but you can change it to other themes, everythings should work just fine since it's only change some path to work on termux

## Installation
1. Install git, openssh, curl, wget, termux-auth
<br /><br />
2. Just copy your entire .oh-my-zsh on your PC to your android devices.
I recommend ssh because you don't have to deal with permission and ownership of file when copy (non-root users can use this method but I don't know why you want to install termux on non-root devices)
<br />
Make sure to check permissions & ownership of the files.
<br /><br />
3. Extract fonts.tar.xz which has fonts for oh-my-zsh or just create a ".fonts" directory and download any fonts you want
<br /><br />
4. Install Termux-Styling & restart Termux, change font
<br /><br />
5. Download .zshrc file with plugins.tar.gz (.p10k.zsh if you use powerlevel10k); extract plugins to .oh-my-zsh/custom/
<br /><br />
6. Run zsh to check if there is any problem
<br /><br />
7. "chsh -s zsh" to change default shell to zsh<br />
Use passwd to setup password in case "chsh" command need password
<br /><br />
