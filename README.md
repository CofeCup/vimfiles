# Dependencies
This Gvim configuration rely on the following tools to give full play to all functions:

- [git](https://git-scm.com/): The [Pro Git](https://git-scm.com/book/zh/v2) book on the website is very good!
- python3: [Anaconda](https://docs.anaconda.com/anaconda/install/windows/) is recommended, but other version works well too
- modelsim: [10.5](https://pan.baidu.com/s/1DH2bGxgQMriJYxdRYSIHFw) is recommended(Passward: Cofe)
- TeX Live 2020: In China, it is recommended to download from [CTAN of tsinghua](https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/mac/mactex/MacTeX.pkg)
- SumatraPDF v3.2: In fact, [pre-release build](https://www.sumatrapdfreader.org/prerelease.html) is recommended because it supports annotation.
- latexmk(update to 4.70a): Using Tex Live Manager embedded in texlive to update

# Content
This git project contend:

- _vimrc for windows
- Vundle plugin
- a nerd font named "Droid Sans Mono Nerd Font"
- snippets for fast latex writing

# How to use
To use this vim configuration, some steps are needed:

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

		let &pythonthreedll=[PATH to python38.dll(**32-bit**)]

	(7) Restart the Gvim.

If you want to use the snippet config, just cope the folder UltiSnips and paste it into ./bundle/ultisnips. After that, restart GVim. 

Enjoy your Vim time!!!

Some function is hided in the vimrc and you should dig by yourself! It is with sufficient comments and easy to read.

# Reference
If you want to learn more vim knowledge in Chinese, I suggest two wedsites and a book:

- [vim教程网](https://vimjc.com)
- [github vim 中文社区](https://github.com/vim-china)
- [《Vim实用技巧》](https://pan.baidu.com/s/1snz-fOPIkw6DUleIKs7Vrw)(Passward: Cofe)

If you want to learn more about latex in Chinese, I suggest two tutorials and a book:

- [How to download TeX Live](https://liam.page/texlive/)
- [The first tutorial for every one!](https://liam.page/2014/09/08/latex-introduction/)
- [《LATEX 入门》](https://pan.baidu.com/s/1ye7qb1Ab8G2BZlByqtSuWA)(Passward: Cofe)

**If you click the buttom releases only and you will keep pace with the update!**

*****************************************************
***Remember: There is no such thing as a free lunch.***
*****************************************************

