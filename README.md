# Table of Contents

- [Table of Contents](#table-of-contents)
- [Vim and Other Pokemons](#vim-and-other-pokemons)
  - [Pokemons](#pokemons)
    - [Pokemon: _i3wm_](#pokemon-_i3wm_)
    - [Pokemon: _fish_](#pokemon-_fish_)
    - [Pokemon: _starship_](#pokemon-_starship_)
    - [Pokemon: _tmux_](#pokemon-_tmux_)
  - [(Neo)Vim](#neovim)
        - [Tried:](#tried)
        - [Will try:](#will-try)
        - [Might be interesting:](#might-be-interesting)

# Vim and Other Pokemons

_Workflow on Linux and my recommendations._

**_The goal is to try and make teammates more productive (even a lil bit).
Please, don't hesitate to correct me and to ask questions._**

## Pokemons

- [i3wm](#i3wm)
- [fish](#fish)
- [starship](#fish)
- [tmux](#tmux)

### Pokemon: _i3wm_

---

- [website](https://i3wm.org/)
- [github](https://github.com/i3/i3)

Replaced GNOME with i3wm.

**Why?**

- Because stylings for i32m looks badass
- Better navigation
- Simple to start, does not need much to learn to be productive

**cons:**

- Might have issues when going deeper in configuration to satisfy your needs

**Useful videos:**

- [Quick start](https://www.youtube.com/watch?v=j1I63wGcvU4)
- [Configuration](https://www.youtube.com/watch?v=8-S0cWnLBKg)
- (Optional) ["ricing"=styling](https://www.youtube.com/watch?v=ARKIwOlazKI)

There is alternative - [regolith](https://regolith-linux.org/) which is
combination of GNOME and i32m and is really cool but for me it's an overkill.

### Pokemon: _fish_

---

- [website](https://fishshell.com/)
- [github](https://github.com/fish-shell/fish-shell)

**Why?**

- Because autocomplete is amazing
- Let's you use vi keybindings

**cons:**

- you need to install [oh my fish](https://github.com/oh-my-fish/oh-my-fish)
  - I've installed `nvm` using `omf`, for example.
- sometimes will fail to run scrips because most of the scripts are written for
  bash or sh
  - possible solution: [bass](https://github.com/edc/bass)

### Pokemon: _starship_

---

- [website](https://starship.rs/)
- [github](https://github.com/starship/starship)

**Why?**

- It is written in Rust
- Utility styling
- Great documentation
- Fish + Starship + Vi(keybindings) combo

Definitely should configure for git.

### Pokemon: _tmux_

---

- [github](https://github.com/tmux/tmux)

**Why?**

- One terminal was not enough
- Having multiple opened terminals takes too much space

## (Neo)Vim

---

**Why?**

- Basically you can have your custom IDE/editor
- But that's not the case: it's actually keybindings and vim modes that matter
  (and many other things)

Vim also has GUI, but I never use it.

**Why (Neovim)?**

- Because NeoVim is community based, which makes it less opinion dependant

**Cons:**

- Sometimes GUI is needed
  - viewing images, for example

**Github copilot is already in vim thanks to tpope - [copilot.vim](https://github.com/github/copilot.vim)**

**Recommended plugins:**

##### Tried:

- [coc](https://github.com/neoclide/coc.nvim)
  - LSP
- [nerdtree](https://github.com/preservim/nerdtree)
  - File architecture
- [ultisnips](https://github.com/SirVer/ultisnips)
  - Code snippets
- [ctrlp](https://github.com/ctrlpvim/ctrlp.vim)
  - Fuzzy finder
- [vim commentary](https://github.com/tpope/vim-commentary)
  - Commenting and commenting out
- [emmet vim](https://github.com/mattn/emmet-vim)
  - Well, emmet...
- [vim maximizer](https://github.com/szw/vim-maximizer)
  - Maximizes 1 pane
- [blamer](https://github.com/APZelos/blamer.nvim)
  - Kinda like git lens
- [lightline](https://github.com/itchyny/lightline.vim)
  - Ricing vim
- [markdown preview](https://github.com/iamcco/markdown-preview.nvim)
  - opens markdown in browser for preview

##### Will try:

- [telescope](https://github.com/nvim-telescope/telescope.nvim)
  - Fuzzy finder (probably will try this one, and not the other one)
- [fzf](https://github.com/junegunn/fzf.vim)
  - Fuzzy finder

##### Might be interesting:

- [vim fugitive](https://github.com/tpope/vim-fugitive)
  - Git wrapper

**If you ever consider to try out vim, you won't regret it. And you will also
have a lot of issues, so don't hesitate to reach out to me.**

**Books (both have same author):**

- [Practical Vim: Edit Text at the Speed of Thought](https://b-ok.asia/book/5103162/425395)
- [Modern Vim: Craft Your Development Environment with Vim 8 and Neovim](https://b-ok.asia/book/3515981/579b1b) (new version of previous book + neovim)
- [Youtuber: Primeagen](https://www.youtube.com/channel/UC8ENHE5xdFSwx71u3fDH5Xw)
