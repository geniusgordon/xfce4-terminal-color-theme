# Terminal Color Theme

A cli tool for changing xfce4-terminal color theme

### Usage

#### List available themes
```
$ terminal-color-theme -l
black-on-white
dark-pastels
green-on-black
solarized-dark
solarized-light
tango
white-on-black
xterm
```

#### Apply theme
```
$ terminal-color-theme solarized-dark
```

### Install bash completion

Needs re-login to bash.

#### Archlinux
```
sudo cp ./bash_completion /usr/share/bash-completion/completions/terminal-color-theme
```
#### Ubuntu
```
sudo cp ./bash_completion /etc/bash_completion.d/terminal-color-theme
```
```
