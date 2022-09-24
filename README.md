# ✨ Myles's Neovim dotfiles 🎉

## Preview

![Preview](https://user-images.githubusercontent.com/54089360/192091452-22f0c996-637d-4b36-b99f-2a2b797ddbd2.png)

## TODO

- [ ] install script
- [ ] null-ls/lspconfig config

## ⚙️ Install

### 🪡 Prepare

create directories `swap`, `backup` and `undo` in vim cache directory.

font

```bash
docker run --rm -v /path/to/font:/in -v /path/for/output:/out nerdfonts/patcher --careful --complete --progressbars
```

### 🔗 Dependencies

- [ ] rgrep
- [ ] fd
- [ ] lazygit

## ⌨️  keymaps

### 📁 File Explorer(nvim-tree)

| key         | command                | description                         |
|-------------|------------------------|-------------------------------------|
| \<leader\>e | NvimTreeFindFileToggle | Toggle explorer for current bufname |
| \<leader\>E | NvimTreeToggle         | Toggle explorer                     |

for more keymapping information, see [nvim-tree](https://github.com/kyazdani42/nvim-tree.lua#defaults)

### 🚀 LSP(lspconf)

### Telescope

## 🔑 LICENSE
