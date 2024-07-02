# DESCRIPTION
This configuration provides:
- Cool Catppuccin colorscheme (https://github.com/catppuccin/nvim)
- Auto-completions
- LSP (Language Server Protocol) for C/C++, Lua & Javascript (but you can add your own)
- A file explorer (https://github.com/nvim-neo-tree/neo-tree.nvim)
- An amazing fuzzy finder (https://github.com/nvim-telescope/telescope.nvim)

# INSTALLATION
**Make sure you have a nerd font  installed, like *JetBrainsMono Nerd Font***

To install the config, simply:
```bash
rm -rf .local/share/nvim
if [[ -d ~/.config/nvim ]]; then
	mv ~/.config/nvim ~/.config/nvim.back
fi
mkdir -p ~/.config/nvim
git clone https://github.com/RomainPlmg/NeoVim-Config.git ~/.config/nvim && nvim
```

Once in NeoVim, simply run `:MasonInstallAll`. Then restart NeoVim and it is done. Enjoy!

Please understand that this is my personal configuration for my setup. If something doesn't work, feel free to open up an issue or message me, and I will try to help.

**Thank you for your download !**
