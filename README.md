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

# Aliases
## [GitAlias](https://github.com/GitAlias/gitalias)
> Note: Currently the configuration below is intended for UNIX/Linux systems! I have set up my work computer with WSL, so I'll be using that, but the only difference you'd need to make is the path and utility you use to download said config file.

This is a cheat sheet/configuration of useful git aliases using the native aliasing functionality of git. I have not added any of my own yet but will do so after I learn these ones!
```
curl https://raw.githubusercontent.com/GitAlias/gitalias/master/gitalias.txt -o ~/.gitalias
git config --global include.path ~/.gitalias
```