<p align="center">
  <img width="860" alt="Night Owl Vim colorscheme screenshot" src="https://user-images.githubusercontent.com/1166872/58341756-8f34e480-7e81-11e9-90d1-19775d6020bd.png">
</p>

My personal fork of [haishanh/night-owl.vim]. 


A true color Vim colorscheme based on [sdras/night-owl-vscode-theme](https://github.com/sdras/night-owl-vscode-theme)

## Usage

```vim
""""" install

" install with vim-plug
Plug 'haishanh/night-owl.vim'
" or with NeoBundle
" NeoBundle 'haishanh/night-owl.vim'
" or with Vundle
" Plugin 'haishanh/night-owl.vim'

""""" enable 24bit true color

" If you have vim >=8.0 or Neovim >= 0.1.5
if (has("termguicolors"))
 set termguicolors
endif

" For Neovim 0.1.3 and 0.1.4
let $NVIM_TUI_ENABLE_TRUE_COLOR=1

""""" enable the theme

syntax enable
colorscheme night-owl
```

This theme is build with [jacoborus/estilo](https://github.com/jacoborus/estilo). If you want to customize this theme, you will need [Node.js](https://nodejs.org).

```
# clone the repo and cd to the dir
# install deps
# you can use npm too
yarn

# checkout file estilo/palettes/night-owl.vim.yml and estilo/syntax/base.yml
# read https://github.com/jacoborus/estilo/blob/master/docs/color-palettes.md
# and https://github.com/jacoborus/estilo/blob/master/docs/colorschemes.md
# to understand how to use them

# make changes and run
yarn render
```

## Links

- [24bit(true color) in terminal](https://gist.github.com/XVilka/8346728)
