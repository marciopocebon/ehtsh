# ehtools-shell (ehtsh)

    root@ehtools:/var# ehtsh --theme eterm
    eterm##$:/var: ls
    readme.txt
    eterm##$:/var: cat readme.txt
    cat: readme.txt: permission denied!
    eterm##$:/var: more readme.txt
    --------------------
       LEAVE ME HERE!
    --------------------
    eterm##$:/var: rm readme.txt
    rm: readme.txt: [y/N]
    
# How to install ehtsh

> cd ehtools-shell

> chmod +x install.sh

> ./install.sh

# How to uninstall ehtsh

> cd ehtools-shell

> chmod +x uninstall.sh

> ./uninstall.sh

# Ehtools shell options

| Command | Description |
| --- | --- |
| ehtsh --theme | Select terminal theme |
| ehtsh --theme --list | Show all terminal themes |

# Ehtools shell themes

| Theme | Description |
| --- | --- |
| ehtsh | ehtsh default theme |
| system | "as system" theme for old computers |
| eterm | eterm default theme |
| root | fake root user theme |
| kali | kali linux theme |
| parrot | parrot os theme |
| dos_fat | dos cmd theme |
| c_disk | windows cmd theme |

# How to change theme

> ehtsh --theme --list

    INFO: Select theme, for example "dos_fat"

> ehtsh --theme dos_fat

    DOS_fat: cd /root/examples
    DOS_fat: ls 
    Desktop Videos Media 
    DOS_fat: exit
    [exit 0]
    
 # Thats all!
    
