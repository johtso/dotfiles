# My dotfiles

## Installation

Clone this repository to `~/.dotfiles`, install the `dotfiles` tool, and sync the dotfiles into your $HOME.

```
git clone --recursive git://github.com/johtso/dotfiles.git ~/.dotfiles
pip install dotfiles
dotfiles --repo=~/.dotfiles --sync
```

Then just set zsh to be your shell:

`chsh -s /bin/zsh`