# dotfiles
nord (ft. blahaj)

## preview

[<img width="2940" height="1912" alt="image" src="https://github.com/user-attachments/assets/26e1b9d9-7725-4ee9-8633-b482a8a58d51" />](https://github.com/midnightszz/NordMacOS/blob/main/preview.png)

## pre-requisites 

install the following:

simple-bar (https://www.jeantinland.com/toolbox/simple-bar/documentation/installation/)

aerospace (https://github.com/nikitabobko/AeroSpace)

kitty (https://sw.kovidgoyal.net/kitty/binary/)

fastfetch (https://github.com/fastfetch-cli/fastfetch)

spicetify (https://spicetify.app/docs/getting-started)

equicord (https://equicord.org/)

boringnotch (https://theboring.name/)

## installation

convert the config folder, aerospace.toml, and simplebarrc to dotfiles via vscodium, or whatever editor you like to use. after doing so, make sure you keep .aerospace.toml and .simplebarrc in your home directory (aka the ~ directory). 

reload aerospace and übersicht via the menu bar. 

the aerospace keybinds can be found and customized in the toml file.

before this step, ensure that spicetify is installed. if it isn't, go look at the pre-requisites for the link. 

afterwards, run the following:

`cd spicetify-themes`

`spicetify config current_theme text`

`spicetify config color_scheme Nord`

this might close spotify. if it does, reopen it, and spotify should be successfully skinned.

then theres discord. after installing equicord and patching your discord client, open your settings. 

scroll or look around until you find the equicord settings. go to the themes tab, and open the themes folder. drag the system24-nord.theme.css file into there, and then hit load missing themes. 

enable it and now you've got nord discord!

vscodium is the last one, which is pretty simple. after installing vscodium, install these two extensions

Nord by ArcticIceStudio (https://open-vsx.org/vscode/item?itemName=arcticicestudio.nord-visual-studio-code)

VSCord by LeonardSSH (https://open-vsx.org/vscode/item?itemName=LeonardSSH.vscord)

and thats all.

## contact

if you have any issues, message me on reddit and i can try to help you to the best of my ability. i'm not exactly the best with this stuff, but i can try. thanks for using my dots <3
