# Patch for vim.

## Documentation content
1. [Installing requiments][1]
2. [Including plugin][2]
3. [Reinstall && Clear VIM][3]

## Install VIM && Vandle
* Install Vim
  # Ubuntu 
  ``` bash
    sudo apt install vim
  ``` 
  # Arch 
  ``` bash 
    sudo pacman -S vim 
  ```
* Install Vundle
  ``` bash 
    cd && git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
  ```
## Install MyConfig
  * Get started
    ``` bash
      cd && git clone https://github.com/KR1470R/MyVimConfig.git && cat MyVimConfig/vimrc >> ~/.vimrc && vim +PluginInstall +qall 
    ```
  * Enjoy!
 
## Reinstall VIM && Clear all shits of VIM
  * 
    # Ubuntu
      ``` bash 
        sudo apt update && sudo apt purge vim && sudo apt install vim && sudo rm ~/.vimrc
      ```
    # Arch 
      ``` bash 
        sudo pacman -Suyy && sudo pacman -Rns vim && sudo pacman -S vim && sudo rm ~/.vimrc
      ```
      
      
[1]:https://github.com/KR1470R/MyVimConfig#Install
[2]:https://github.com/KR1470R/MyVimConfig#Including_plugin
[3]:https://github.com/KR1470R/MyVimConfig#Reinstall_&&_Clear_VIM
