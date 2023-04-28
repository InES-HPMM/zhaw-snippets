# ZHAW Snippets

This repo contains a collection of ZHAW related snippets.

## Features

| Snippet | Purpose              | Available in                                                     |
| ------- | -------------------- | ---------------------------------------------------------------- |
| `inesh` | The InES file header | c, cpp, latex, python, shellscript, systemverilog, verilog, vhdl |

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
use "InES-HPMM/zhaw-snippets"
```

```vim
-- Plug
Plug 'InES-HPMM/zhaw-snippets'
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

## Resources

- [VSCode Snippets Documentation](https://code.visualstudio.com/docs/editor/userdefinedsnippets)
- Example project:
  - [vue-vscode-snippets](https://github.com/sdras/vue-vscode-snippets)

## Release Notes

See [CHANGELOG](CHANGELOG.md) for details.
