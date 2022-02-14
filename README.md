# nvim-ide


## Try out this config

- Make sure you have [node](https://nodejs.org/en/) installed, I recommend a node manager like [nvm](https://github.com/nvm-sh/nvm).

- Add copy/paste possibility 

-- On mac `pbcopy` should be builtin

-- On Ubuntu

  ```
  sudo apt install xsel
  ```

-- On Arch Linux

  ```
  sudo pacman -S xsel
  ```
- Next we need to install python support (node is optional)

-- Neovim python support

  ```
  pip install pynvim
  ```

-- Neovim node support

  ```
  npm i -g neovim
  ``` 

- Install Linters and Formatters for Python (or your Language). It is used for `Null-LS` plugin.

  ```
  pip3 install flake8
  pip3 install mypy 
  pip3 install back 
  ```

- Make sure to remove or move your current `nvim` directory

**IMPORTANT** Requires [Neovim v0.6.0](https://github.com/neovim/neovim/releases/tag/v0.6.0) or [Nightly](https://github.com/neovim/neovim/releases/tag/nightly). 
```
git clone https://github.com/KitKod/nvim-ide ~/.config/nvim
```

Run `nvim` and wait for the plugins to be installed 

**NOTE** (You will notice treesitter pulling in a bunch of parsers the next time you open Neovim) 

## Get healthy

Open `nvim` and enter the following:

```
:checkhealth
```

---

\- Mykyta Kamak

