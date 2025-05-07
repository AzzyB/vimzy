# Vimzy

## Azzy's neovim config for the terminal programmer.

![image](https://github.com/AzzyB/vimzy/blob/main/screenshots/greeter_dashboard.png)

## Description

Default configs for neovim using the Lazy nvim package manager that streamline tasks for programming and documentation.

#### Features
* [Treesitter](https://github.com/nvim-treesitter/nvim-treesitter) - file exploration structure with easy manipulation (add, delete, rename, etc.)
* LSP Configuration using Mason
* Customizable greeter dashboard using [alpha](https://github.com/goolord/alpha-nvim)
* Updatable/modifiable plugins via lazy plugin manager

### Dependencies
_This installation is for my Arch system but it's dependencies should be system agnostic therefore just use whatever package manager is relevant to your respective system._

* Well [neovim](https://neovim.io/) of course
* [tmux](https://github.com/tmux/tmux)
* npm

### "Installation"

* Clone or download this repo and copy paste the nvim folder into your ~/.config folder. Running nvim for the first time will auto run all the plugins and download what is needed.  
* NOTE: make sure you don't have any pre-existing configs you may want to keep if you choose to just copy/paste/overwrite should there be an existing nvim config folder.  

### Help
* I'm assuming if you're here you know how to navigate around neovim but if not here's the [cheatsheet](https://neovim.io/doc/user/quickref.html)

---default keybindings to be listed---

### To-Do's
* Document default keybinds and how to edit them
* Explain plugin usage in detail
* Implement theme plugin
* Implement markdown live preview
* Update feature list (its not done yet)

## Acknowledgments
* [Typecraft](https://youtu.be/zHTeCSVAFNY?si=CLY7Iw2ydervuDeM) for an amazing course for 0 to IDE for neovim
* ML4W's hyprland starter [git](https://github.com/mylinuxforwork/hyprland-starter) where I poked around in some files
