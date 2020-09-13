This Gvim configuration rely on the following tools to give full play to all functions:

    git 
    python
    modelsim
    Windows system

This git project contend:

    _vimrc for windows
    all the plugin & colorsheme vim files mentioned in the _vimrc
    a nerd font named "Droid Sans Mono Nerd Font"

To use this vim configuration, five step is needed:

    (1) Make sure that you have python, modelsim, and git on your PC(if your work has nothing to do with python and verilog, you just need to install git)

    (2) In cmd, excuting the following command:

        $ cd /d [path to your $VIMRUNTIME] (like: cd /d D:\Vim\vim82)
        $ git clone https://github.com/CofeCup/vimfiles

    (3) Enter the folder under the $HOME path(normally "C:\Users\[Username]") and find _vimrc file. Add the following command:
        source [path to your $VIMRUNTIME/vimfiles/_vimrc]

        For example:
        
        source D:\Vim\vim82\vimfiles\_vimrc

    (4) Install the font using "Droid Sans Mono Nerd Font Complete Mono Windows Compatible.otf". Just double click it and you will know : )

	(5) Run ":BundleInstall" in Vim shell line and wait utill the installation finished. Restart the Vim.

    Enjoy your Vim time!!!

    Some function is hided in the _vimrc and you should dig for yourself! It is with sufficient comments and easy to read.
    If you want to learn more vim knowledge in Chinese, I suggest two wedsites: 
        https://vimjc.com 
        https://github.com/vim-china

	*****************************************************
    * Remember: There is no such thing as a free lunch. *
	*****************************************************

    Copyright (c) 2020 CofeCup
    ALL RIGHTS RESERVED
