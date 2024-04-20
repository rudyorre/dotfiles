<h1 align="center"><code>~/dotfiles</code></h1>

## About
Current not much going on here and very much a start. In `/vscode` is my `settings.json` which my local VSCode instance uses as a symlink target.

```bash
ln -s ~/dotfiles/vscode/settings.json ~/Library/Application\ Support/Code/User/settings.json
```

Planning to add some sort of symlink management system like RCM as outlined in [this article](https://anhari.dev/blog/saving-vscode-settings-in-your-dotfiles), just haven't gotten to it quite yet.

Also, will be adding my Neovim setup here as I get more into that, but for now I'll continue to primarily be a VSCode soydev using the [Vim Motions extension](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim) 🤷‍♂.
