CONFIG*
#What is this? 

This is my configuration of nvim, is copied from Chris at machine, don't take ispiration from me.

* To make it work, install vim plug, then in command mode, execute >>:PlugInstall


#Git integration on neovim

https://www.chrisatmachine.com/Neovim/12-git-integration/


##Coc

:CocInstall coc-json coc-css coc-clangd coc-html coc-python coc-cmake coc-explorer

##Add icons
Download the font from the repo below or other font, 
and put into ~/.local/share/fonts

this is the repo where i get the font, is Hack nerd font
https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/Hack/Regular/complete/Hack%20Regular%20Nerd%20Font%20Complete.ttf

##Signify
Ho installato il plug in signify che mi consente di mostrare le icone 
di linee aggiunte, modificate o rimosse. 

    `+`     This line was added.

    `!`     This line was modified.

    `_1`    The number of deleted lines below this sign. If the number is larger
    `99`    than 9, the `_` will be omitted. For numbers larger than 99, `_>`
    `_>`    will be shown instead.

    `!1`    This line was modified and the lines below were deleted.
    `!>`    It is a combination of `!` and `_`. If the number is larger than 9,
          `!>` will be shown instead.

    `‾`     The first line was removed. It's a special case of the `_` sign.
    
I Wrote also a configuration for this plug-in.

##Fugitive 

This plug-in is used for interactin with git
Note: Make sure you are using git through ssh not http

:Git add

:Git commit

:Git push

:Git pull

:Git diff

:Git log

:Git blame

Gdiffsplit

GRemove

GBrowse

##GV 
this open the commit browser 

:GV!         # will only list commits that affected the current file
:GV?         # fills the location list with the revisions of 
                the current file
:GV          # or :GV? can be used in visual mode to track the 
              changes in the selected lines
              

              
              
              

