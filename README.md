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

## Brewfile contents
- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions): Fish-like autosuggestions in zsh as you type.
- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting): Colors zsh commands to catch mistakes early.
- [fzf](https://github.com/junegunn/fzf): Fast fuzzy finder for files, history, and more.
- [fd](https://github.com/sharkdp/fd): Faster, simpler `find` used by fzf bindings.
- [zoxide](https://github.com/ajeetdsouza/zoxide): Smart directory jumper powered by frecency.
- [atuin](https://github.com/ellie/atuin): Syncable, searchable shell history.
- [starship](https://github.com/starship/starship): Cross-shell prompt that shows git/status info quickly.
- [ripgrep](https://github.com/BurntSushi/ripgrep): Fast recursive search with sane defaults.
- [bat](https://github.com/sharkdp/bat): `cat` with syntax highlighting and paging.
- [eza](https://github.com/eza-community/eza): Modern `ls` with git/status, icons, and tree views.
- [tldr](https://github.com/tldr-pages/tldr): Concise community-maintained cheatsheets for commands.
- [jq](https://github.com/jqlang/jq): CLI JSON processor for querying and shaping data.
- [font-fira-code-nerd-font](https://github.com/ryanoasis/nerd-fonts): Fira Code with Nerd Font glyphs for prompt/icons.
- Quick usage? Run `tldr <tool>` for a one-page refresher.

## zsh configuration
See `zshrc-notes.md` for the small block to add to your `~/.zshrc` if you want the shell tooling enabled.

## Restore config
If `config` is ever lost, copy it back into `~/.config/ghostty` and restart Ghostty.
