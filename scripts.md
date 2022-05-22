
# Scripts

The scripts do a lot of tasks on my system and kind of glue everything
togerther. The repository is located in
[alexcoder04/scripts](https://github.com/alexcoder04/scripts) and is installed
into a folder defined in the `$SCRIPTS_DIR` environmental variable. This
location must be added to `$PATH`.

Most of the scripts source `libsh` which defines some useful shell functions
(error/info message in terminal and gui, prompts, ...).

The scripts' shebang is `#!/bin/sh`, so they are written in POSIX sh, not Bash.
This is done for efficiency and portability purposes (the shell I use by default
is Dash).

