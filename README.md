# Customize-Terminal-Linux
With figlet, lolcat, and cowsay

![Display in the terminal](https://user-images.githubusercontent.com/37952748/72699298-51a46a80-3b7a-11ea-874a-53fc96a3edae.png)

    1. Install figlet
        $ sudo apt-get install figlet
        ===============================================

    2. Install cowsay
        $ sudo apt-get install cowsay
        ===============================================

    3. Install lolcat
        $ sudo apt-get install ruby
        $ ruby -v
        $ sudo gem install lolcat
        ===============================================

    4. Install nano
        $ sudo apt-get install nano
        ===============================================

    5. Configuration .bashrc 
        $ nano .bashrc
        ===============================================

    6. Add this syntax in .bashrc
        cowsay -f eyes Welcome to CodeArt | lolcat
        figlet -f standard "Wahyoe" | lolcat
        date | lolcat
