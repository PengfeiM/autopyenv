# Auto python venv activate and deactivate

## How it works?
when you cd into a directory, it will check if you have path `./venv`.
if does, it will do `source ./venv/bin/activate`,
if not, it will do `deactivate`

## Install
1. just download the repo in any way you can.
2. put file `autopyenv.zsh` in path `~/.oh-my-zsh/custome` or copy the content in `autopyenv.zsh` into your .zshrc file

## Compatibility
it works fine with venv created by pycharm, or you can say it works with a python project path that contains subdir `./venv`.
If you want to use a diffrent python venv dir name, just modify the variable `MYVENV` in `autopyenv.zsh`. 
If you have other request, feel free to fork and make your own script, please keep it open source.
After all, internet is about share.

## Acknowledgement
this script is not my work, I just upload it to github to share.
Original source: https://dev.to/moniquelive/auto-activate-and-deactivate-python-venv-using-zsh-4dlm, https://monique.dev/posts/pyenv/   
Thanks to [moniquelive](https://github.com/moniquelive?tab=repositories&q=&type=source&language=&sort=)! 
