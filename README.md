# Chuck's NvChad Setup

## Initial setup

This is a fork of the orignal NvChad starter setup. It can be put in place with the command...

```shell
$ git clone git@github.com:ocheret/nvchad_starter.git ~/.config/nvim

```

## Important setup

- Don't use the MacOS built-in terminal. Use something like wezterm.
- Install at least one *Nerd Font* from [nerdfonts.com](https://nerdfonts.com).
- Install ripgrep - `$ brew install ripgrep`.
- `:MasonInstallAll`
- `:MasonInstall rust-analyzer`
- `:MasonInstall codelldb`

## Some useful shortcuts

Note: The leader character is set to `<space>`.

- `<space>th` to select a theme like Catppuccin
- `ctrl-N` to toggle on and off the file tree explorer
- `<space>ff` for the fuzzy file finder
- `<space>h` terminal emulator
- `:Mason` to bring up the Mason menu

# Original README content below this point.

**This repo is supposed to used as config by NvChad users!**

- The main nvchad repo (NvChad/NvChad) is used as a plugin by this repo.
- So you just import its modules , like `require "nvchad.options" , require "nvchad.mappings"`
- So you can delete the .git from this repo ( when you clone it locally ) or fork it :)

# Credits

1) Lazyvim starter https://github.com/LazyVim/starter as nvchad's starter was inspired by Lazyvim's . It made a lot of things easier!
