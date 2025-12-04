# zshrc additions for this setup

Add the following to `~/.zshrc` to enable the shell tooling installed via `Brewfile`. Nothing here is Ghostty-specific; it just wires up the helpers.

```zsh
# fzf completion and keybindings
[ -f /opt/homebrew/opt/fzf/shell/completion.zsh ] && source /opt/homebrew/opt/fzf/shell/completion.zsh
[ -f /opt/homebrew/opt/fzf/shell/key-bindings.zsh ] && source /opt/homebrew/opt/fzf/shell/key-bindings.zsh

# zsh plugins
source /opt/homebrew/share/zsh-autosuggestions/zsh-autosuggestions.zsh
source /opt/homebrew/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh

# navigation/history helpers
eval "$(zoxide init zsh)"
eval "$(atuin init zsh)"

# prompt
eval "$(starship init zsh)"
```

You can remove any lines you don’t want; this is the minimal wiring for the packages in the Brewfile.
