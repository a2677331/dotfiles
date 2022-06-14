dotfiles
========

A collection of my personal dotfiles. 

Installation
------------
1. Install [chezmoi](https://www.chezmoi.io/#considering-using-chezmoi)
    ```
    snap install chezmoi --classic
    ```
    
2. Then restore dotfiles on your machine
    ```
    chezmoi init https://github.com/a2677331/my-dotfiles.git # download all config files inside chezmoi
    chezmoi apply                                            # actually place config files under your $USER path
    ```
