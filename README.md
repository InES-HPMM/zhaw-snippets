# ZHAW Snippets

This repo contains a collection of ZHAW related snippets.

## Features

Currently, this collection provides snippets for the InES file headers in C/C++
and VHDL. More snippets will be added when they get requested or I when I
encounter them.

## Installation

### VSCode

Install the extension from the extension market.

### Vim/Neovim

This plugin only provides snippets. Therefore, you need a plugin that provides
snippet features and supports loading VSCode snippets.

For example:

- [vim-vsnip](https://github.com/hrsh7th/vim-vsnip)
- [LuaSnip](https://github.com/L3MON4D3/LuaSnip)
- [coc-snippets](https://github.com/neoclide/coc-snippets)

Use your plugin manager to install the package.

```lua
-- Packer
use "rafamadriz/friendly-snippets"
```

```vim
-- Plug
Plug 'rafamadriz/friendly-snippets'
```

```
-- coc.nvim
CocInstall https://github.com/InES-HPMM/zhaw-snippets@main
```

[vim-vsnip](https://github.com/hrsh7th/vim-vsnip) will automatically detect and
load the snippets. In [LuaSnip](https://github.com/L3MON4D3/LuaSnip) you will
have to call

```lua
require("luasnip.loaders.from_vscode").load()
-- or to lazy load the snippets
require("luasnip.loaders.from_vscode").lazy_load()
```

## Snippets

| Snippet | Purpose              | Available in |
| ------- | -------------------- | ------------ |
| `inesh` | The InES file header | c, cpp, vhdl |

## Resources

- [VSCode Snippets Documentation](https://code.visualstudio.com/docs/editor/userdefinedsnippets)
- Example project:
  - [vue-vscode-snippets](https://github.com/sdras/vue-vscode-snippets)

## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release of zhaw-snippets
