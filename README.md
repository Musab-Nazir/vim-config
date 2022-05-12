# dotfiles

This is a collection of config files I used for a number of different tools and apps

## Nvim
Make sure to install `vim-plug`. There are a few external dependencies needed that can be fetched via `brew`.
### Telescope
* brew install fd
* brew install ripgrep

### Extra Lua config
To configure the LSP, auto complete etc, install the pacakges via `Plug Install` first.
Then uncomment the following line from init.vim
```
 lua require("config")
```
This will load the lua config for a bunch of the plugins and install/configure typescript + clojure language servers
