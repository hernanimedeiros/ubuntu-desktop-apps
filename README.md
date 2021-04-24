# ubuntu-desktop-apps
*Some desktop apps for productivity increase in Ubuntu based distros*

## App list
### devilbox_run_app
Run your Devilbox Development Environment in one touch. Close it with ctrl+c

### echo_default
enable noise cancellation to your microphone (default)

### echo_webrtc
enable noise cancellation to your microphone (webrtc)

## Install instructions
Attention! If this will be your first contact with terminal, maybe this project is not for you. Otherwise if you use terminal sometimes go ahead.

In each folder of this project there are 2 files: the script (app_name) and the app generator (app_name.desktop)

After copy the files to your home folder:

-Install the app, making it executable. You can do this easly in command line:

```
sudo install app_name /usr/local/bin
```


-Copy appname.desktop to ~/.local/share/applications/
You can do this also from the command line:

```
cp app_name.desktop ~/.local/share/applications/
```

## Final notes
Some apps need gnome-terminal to run. If you don't have it on your ubuntu based distro run on terminal:

```
sudo apt update
sudo apt install gnome-terminal
```

Some apps have my user name on it. Change it to yours before run the commands.

## References
[Ask Ubuntu](https://askubuntu.com/questions/46627/how-can-i-make-a-script-that-opens-terminal-windows-and-executes-commands-in-the)

[Linux Uprising](https://www.linuxuprising.com/2020/09/how-to-enable-echo-noise-cancellation.html)
