##Dotfile Notes


**Dotfile root folder => ~/Dots**
- First sub-directory under ~/Dots will be capitalized and organizes folders by application/etc
- The files under each of these main sub-directories are the files and folders to be linked into
  their perspective places 
- For Example: ~/Dots/Vim is the folder where all vim configs go ~/Dots/Vim/vim will be linked to
  ~/.vim & ~/Dots/Vim/vimrc will be linked to ~/.vimrc


```
/* EXAMPLE DIRECTORY STRUCTURE */
--Dots
    |_Emacs
        |_emacs.d/
    |_Vim
        |_vim/ => ~/.vim
            |_autoload/
            |_bundle/
            |_colors/
        |_vimrc => ~/.vimrc
    |_Zsh/
        |_fpath/
        |_zshrc
        |_zshenv
        |_zprofile
```


