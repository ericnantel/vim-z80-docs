# The unofficial Zilog Z80 Assembly Documentation
*Written by Eric Nantel*

The primary intent of this (Neo)Vim plugin is to be able to efficient browse
for Z80 instructions within (Neo)Vim ecosystem, thus removing the need to launch
an external application.

# Installation

To install in Vim using vim-plug:
```vim
call plug#begin('~/.vim/plugged')
  Plug 'ericnantel/vim-z80-docs'
call plug#end()
```

To install in Neovim using lazy.nvim:
```lua
require("lazy").setup({
  spec = {
    {
      "ericnantel/vim-z80-docs",
    },
  }
})
```

# Search keyword

In order to open the unofficial Zilog Z80 Assembly Documentation within (Neo)Vim,
You can enter the one the following commands:
```vim
:help z80-docs
:help z80-registers
:help z80-instructions
```

To search for a specific instruction you may do a command like:
```vim
:help z80-instruction-add
```
Where you can replace 'add' by the instruction you are looking for.
If it exists, you'll be teleported to the right location in the doc.

# Contribution

I am looking for contributors for extending the unofficial Zilog Z80 Assembly Documentation.
Such as translators, and people that can report typos I may have made or that can add some
tables or graphs to help users visualize the architecture of its components (ex: RAM, ALU).

In addition to that, I am not against having tutorials on writing and/or assembling a program.

# What's next ?

Having a Z80 LSP in (Neo)Vim would be awesome !

But regarding this plugin, I want to make it simple for users to know about cycles an instruction
takes, so adding Z80 support to airline or lualine is something I am considering.

Additionaly, I would like to do other (Neo)Vim unofficial Doc plugins for other retro cpus.

If you read all this, congrats ! You may want to star this repository to help the retro community.
*Eric Nantel*
