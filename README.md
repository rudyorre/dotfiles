<h1 align="center"><code>~/dotfiles</code></h1>

## About
Current not much going on here and very much a start. in `/vscode` are my `settings.json` and `keybindings.json` files that are symlinks on my local instance to the actual files.

```bash
ln -s ~/Library/Application\ Support/Code/User/settings.json ~/dotfiles/vscode/settings.json
ln -s ~/Library/Application\ Support/Code/User/keybindings.json ~/dotfiles/vscode/keybindings.json
```

Planning to add some sort of symlink management system as outlined in [this article](https://anhari.dev/blog/saving-vscode-settings-in-your-dotfiles), just haven't gotten to it quite yet.

Also, will be adding my Neovim setup here as I get more into that.

