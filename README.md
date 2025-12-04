# Ghostty Minimal Config (Catppuccin Mocha + Fira Code)

What’s included:
- `config` – active Ghostty config (Catppuccin Mocha + Fira Code, keybindings).
- `themes/catppuccin-mocha.conf` – theme reference.
- `fonts/fira-code.conf` – font settings reference.
- `Brewfile` – shell tooling (fzf/fd, zsh plugins, zoxide, atuin, starship, a few CLI niceties).

No helper scripts or aliases are included; everything is manual.

## Setup
1) Copy/clone this repo to `~/.config/ghostty`.
2) Install shell tools (optional but expected):  
   `brew bundle --file=Brewfile`
3) Restart Ghostty.

## zsh configuration
See `zshrc-notes.md` for the small block to add to your `~/.zshrc` if you want the shell tooling enabled.

## Restore config
If `config` is ever lost, copy it back into `~/.config/ghostty` and restart Ghostty.
