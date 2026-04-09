# dotfiles
nord (ft. blahaj)

## preview


## pre-requisites 

install the following:

simple-bar (https://www.jeantinland.com/toolbox/simple-bar/documentation/installation/)

aerospace (https://github.com/nikitabobko/AeroSpace)

kitty (https://sw.kovidgoyal.net/kitty/binary/)

fastfetch (https://github.com/fastfetch-cli/fastfetch)

spicetify (https://spicetify.app/docs/getting-started)

equicord (https://equicord.org/)

boringnotch(https://theboring.name/)

## installation

convert config, aerospace.toml, and simplebarrc to dotfiles via vscodium, or whatever editor you like to use. after doing so, make sure you keep .aerospace.toml and .simplebarrc in your home directory (aka the ~ directory). 

reload aerospace and übersicht via the menu bar. 

the aerospace keybinds can be found and customized in the toml file.

before this step, ensure that spicetify is installed. if it isn't, go look at the pre-requisites for the link. 

afterwards, run the following:

`cd spicetify-themes`

`spicetify config current_theme text`

`spicetify config color_scheme Nord`

this might close spotify. if it does, reopen it, and spotify should be successfully skinned.

lastly, there's discord. after installing equicord and patching your discord client, open your settings. scroll or look around until you find the equicord settings. go to the themes tab, and open the themes folder. drag the system24-nord.theme.css file into there, and then hit load missing themes. enable it and boom!

## contact

if you have any issues, message me on reddit and i can try to help you to the best of my ability. i'm not exactly the best with this stuff, but i can try. thanks for using my dots :3 
