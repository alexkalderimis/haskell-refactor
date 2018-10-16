# Haskell Refactor

A vim plugin that helps you refactor Haskell code.

![Demo](https://github.com/chris-bacon/haskell-refactor/raw/master/demo.gif "Demo")

## Installation

With `Plug` add,

```vim
Plug 'chris-bacon/haskell-refactor'
```

to your vimrc.

Alternatively, you can clone this repo.

## Usage

Select the code you wish to refactor in visual mode. You can then use the following commands:

```vim
:ExtractHaskellFunction <name> <params>
:ExtractHaskellType <name>
```

All options are optional. Every command will default to a prompt if no args are provided, so you do not need to provide any arguments. This also means you can use the motions:

```
<leader>ef - calls ExtractHaskellFunction
<leader>et - calls ExtractHaskellType
```

## Contributing

_Please feel free to raise any issues or PRs._
