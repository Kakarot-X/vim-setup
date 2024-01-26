# Installation


## Installing Plugins
Firstly copy the `vimrc` file to your home directory to replace your current `.vimrc` file:
```bash
   $ cp  vimrc ~/.vimrc
```
Make sure the [Vundle](https://github.com/VundleVim/Vundle.vim) plug-in manager is installed on your system. If it's not, run the following commands:

    $ cd ~/.vim
    $ mkdir bundle && cd bundle
    $ git clone https://https://github.com/VundleVim/Vundle.vim Vundle.git
    $ cd ~

Lastly, install the plug-ins by running the following on the command-line:

    $ vim +PluginInstall +qall
Plugins will be saved in plugged directory
