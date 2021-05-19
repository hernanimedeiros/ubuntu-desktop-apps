# ubuntu-desktop-apps
*Install desktop apps for productivity increase in Ubuntu based distros*

In this repo I want to register 3 uses cases for ubuntu desktop apps:
- Desktop app from script
- Desktop app from app that your run from terminal writing a command
- Desktop app from App Image file

Maybe I will do individual repos for each use case but the app stores are getting better everyday and in near future some parts of this repo will be useless! So, before waste you valuable time with desktop apps, check your distro app store and app oficial sites for a .deb installer or something user friendly.

Attention! If this will be your first contact with terminal, maybe this project is not for you (or this a good way to start). Otherwise if you use terminal sometimes go ahead.


## Desktop app from script
*In each folder there are 2 files: the script (app_name) and the shortcut generator (app_name.desktop)*

**devilbox_run_app**
Run your Devilbox Development Environment in one touch. Close it with ctrl+c.

**echo_default**
Enable echo cancellation to your microphone (default)

**echo_webrtc**
Enable echo cancellation to your microphone (webrtc)

### Install instructions

#### Prepare to war

- Clone project

- Copy Icons folder to home/username/

- Dig into the folder:
```
cd path_to_folder
```

#### Install app

- Making a script executable. You can do this easly in command line:

```
sudo install app_name /usr/local/bin
```

#### Install shortcuts

- Copy appname.desktop to ~/.local/share/applications/. You can do this also from the command line:

```
cp app_name.desktop ~/.local/share/applications/
```


## Desktop app from app that your run from terminal writing a command (ex: scrcpy)
*In each folder there is a shortcut generator (app_name.desktop)*

**scrcpy**
Run scrcpy without run command in terminal

### Install instructions

#### Prepare to war

- Clone project

- Copy Icons folder to home/username/

- Dig into a folder:
```
cd cd path_to_folder
```

#### Install shortcuts

- Copy appname.desktop to ~/.local/share/applications/. You can do this also from the command line:

```
cp app_name.desktop ~/.local/share/applications/
```

## Desktop app from App Image file
*In each folder there is a shortcut generator (app_name.desktop). You also need to download the App Image*

Examples
- Inkscape
- Balena Etcher

### Install instructions

#### Prepare to war

- Copy App Image to home/Apps/ and give it a name that script can read (check script)

- Clone project

- Copy Icons folder to home/username/

- Dig into a folder:
```
cd cd path_to_folder
```

#### Install shortcuts

- Copy appname.desktop to ~/.local/share/applications/. You can do this also from the command line:

```
cp app_name.desktop ~/.local/share/applications/
```


## Final notes
Some apps need gnome-terminal to run. If you don't have it on your ubuntu based distro run on terminal:

```
sudo apt update
sudo apt install gnome-terminal
```

## References
[Ask Ubuntu](https://askubuntu.com/questions/46627/how-can-i-make-a-script-that-opens-terminal-windows-and-executes-commands-in-the)

[Linux Uprising](https://www.linuxuprising.com/2020/09/how-to-enable-echo-noise-cancellation.html)
