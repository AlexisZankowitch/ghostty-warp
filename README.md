# Ghostty Minimal Config (Catppuccin Mocha + Fira Code)

What’s included:
- `config` – active Ghostty config (Catppuccin Mocha + Fira Code, keybindings).
- `themes/catppuccin-mocha.conf` – theme reference.
- `fonts/fira-code.conf` – font settings reference.
- `Brewfile` – shell tooling (fzf/fd, zsh plugins, zoxide, atuin, starship, a few CLI niceties).

## Setup
1) install ghostty [macos installation](https://ghostty.org/docs/install/binary#macos)
2) clone the repo into your congif `git clone git@github.com:AlexisZankowitch/ghostty-warp.git ~/.config/ghostty`
3) Install shell tools (optional but expected):  
   `brew bundle --file=Brewfile`
4) Start Ghostty from your application

## zsh configuration
See `zshrc-notes.md` for the small block to add to your `~/.zshrc` if you want the shell tooling enabled.

## Restore config
If `config` is ever lost, copy it back into `~/.config/ghostty` and restart Ghostty.
