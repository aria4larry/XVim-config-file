.xvimrc

.xvimrc ls a config file like .vimrc; used by XVim.
see XVim https://github.com/JugglerShu/XVim/blob/master/README.md

I like to use keyboard for coding, controling computer.
I appreciate XVim' author and contributors. XVim makes my working efficient, and funny.

New Feature

1. I add a new method -menucmd:inWindow, so we can perform click any menu item
with its titlename.  eg.  :menucmd Title:Build 

2. fix some action crash bug. See XVimExCommand.m

keymap like  
    map ,bp  :menucmd Title:Build<CR>

My .xvimrc list most menu action and menu title keymap.
Share with you. Hope it useful for you.
And this is my first contribution to OpenSource World.

License
MITLicense
