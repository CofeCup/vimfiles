This Gvim configuration rely on the following tools to give full play to all functions:

    git 
    python3
    modelsim(10.5 is better)
	texlive(2020)
	SumatraPDF(v3.2)
	latexmk(update to 4.70a)

This git project contend:

    _vimrc for windows
	Vundle plugin
    a nerd font named "Droid Sans Mono Nerd Font"
	snippets for fast latex writing

To use this vim configuration, five steps are needed:

    (1) Make sure that you have all the tools mentioned above on your PC(if your work has nothing to do with latex and verilog, you just need to install git and python3). 

    (2) In cmd, excuting the following command:

        $ cd /d [path to the install folder of Gvim(normally we call it $VIMRUNTIME)]
		(eg. cd /d D:\Vim\vim82, and you can use ":echo $VIMRUNTIME" in Gvim to check your Gvim folder path. If your path contains blank space, you should put Double quotation marks("") outside yout path)

        $ git clone https://github.com/CofeCup/vimfiles --recurse-submodules

    (3) Enter the folder under the $HOME path(normally "C:\Users\[Username]") and find a file named "_vimrc". (If it is not existed, pls create one.) Add the following command to _vimrc:

        source [$VIMRUNTIME\vimfiles\_vimrc]

        For example:
        
        source D:\Vim\vim82\vimfiles\_vimrc

    (4) Install the font using "Droid Sans Mono Nerd Font Complete Mono Windows Compatible.otf". Just double click it and you will know : )

	(5) Run ":BundleInstall" in Vim shell line and wait utill the installation finished.

	(6) If needed, change the python3 path using:

		let &pythonthreedll='PATH to python38.dll'

	(7) Restart the Gvim.

Enjoy your Vim time!!!

Some function is hided in the _vimrc and you should dig by yourself! It is with sufficient comments and easy to read.
If you want to learn more vim knowledge in Chinese, I suggest two wedsites: 

    https://vimjc.com 
    https://github.com/vim-china

*****************************************************
Remember: There is no such thing as a free lunch. 
*****************************************************

