
# Dotfiles

My dotfiles are managed by a custom system. The system as well as the dotfiles
themselves are located in [alexcoder04/dotfiles](https://github.com/alexcoder04/dotfiles).

This repository is installed into a folder defined in the `$DOTFILES_REPO`
environmental variable. So, the location can be configured (it's `$HOME/Dotfiles`
in my case) and other programs can do certain automation tasks (e. g. a script
that is bound to a keybinding that changes my i3 theme).

Configuration templates for every program are located inside a dedicated
directory which is named after that program alongside with an `install` script
which generates and copies the config to it's location. This is useful to have
different settings on different machines; those settings are defined inside the
`<hostname>.prefs2` files. More info about the system can be found in the
dotfiles repo itself.

## Key programs in my dotfiles

 - zsh
 - lf
 - i3/sway
 - nvim

