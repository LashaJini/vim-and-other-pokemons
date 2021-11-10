# Table of Contents

- [Table of Contents](#table-of-contents)
  - [Vim and Other Pokemons](#vim-and-other-pokemons)
    - [Pokemons](#pokemons)
      - [i3wm](#i3wm)
      - [fish](#fish)
      - [starship](#starship)
      - [tmux](#tmux)
    - [Vim](#vim)
    - [TODO](#todo)

## Vim and Other Pokemons

_Workflow on Linux and my recommendations._

### Pokemons

- [i3wm](#i3wm)
- [fish](#fish)
- [starship](#fish)
- [tmux](#tmux)

#### i3wm

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

#### fish

---

- [website](https://fishshell.com/)
- [github](https://github.com/fish-shell/fish-shell)

**Why?**

- because autocomplete is amazing
- let's you use vi keybindings

**cons:**

- you need to install [oh my fish](https://github.com/oh-my-fish/oh-my-fish)
  - I've installed `nvm` using `omf`, for example.
- sometimes will fail to run scrips because most of the scripts are written for
  bash or sh
  - possible solution: [bass](https://github.com/edc/bass)

#### starship

---

- [website](https://starship.rs/)
- [github](https://github.com/starship/starship)

**Why?**

- It is written in Rust
- Utility styling
- Great documentation
- Fish + Starship + Vi(keybindings) combo

Definitely should configure for git.

#### tmux

---

- [github](https://github.com/tmux/tmux)

### Vim

### TODO

- [ ] clean vim
- [ ] default vimrc
- [ ] vi, vim, neovim
- [ ] vim vs emacs vs vscode
- [ ] learning curve
- [ ] splitting & moving panes
- [ ] there will be issues
- [ ] disabling cache or something
- [ ] recommendations
  - caps swap
  - primegean
- [ ] plugins
  - blamer
  - vim-maximizer
  - vim-commentary
  - ctrlp
  - markdown-preview
  - ultisnips
  - nerdtree
  - emmet-vim
  - lightline
  - simpylfold
  - coc
  - ale?
- [ ] my init.vim
- [ ] github copilot and tpope
- [ ] vim-fugitive
- [ ] vimium
- [ ] cons of using neovim
- [ ] u can also have mouse feature
