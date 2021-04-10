# config
My personal, portable configuration for different applications.

# Themes
## oh-my-posh

1. Download the theme from the oh-my-posh folder
2. Move it to your oh-my-posh themes folder (you can also eval any file path after the `--config` parameter, which is useful if you'd like to sync the theme between machines)
3. Run the following command:
```
eval "$(oh-my-posh --init --shell zsh --config $(brew --prefix oh-my-posh)/themes/powerlevel10k_lean_custom.omp.json)"
```