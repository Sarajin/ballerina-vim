# ballerina-vim
Vim syntax plugin for ballerina

## Installing via vim plug

1) Add below line to the plugin config

Plug 'lankavitharana/ballerina-vim'

2) run :PlugInstall

3) restart vim

## Installing via vim 8+

1) Add `packloadall` to your `.vimrc` (if you haven't already):

`.vimrc`:

```vim
packloadall
```

2) Add a folder in `.vim` called `pack`

3) Under `.vim/pack` create a folder named whatever you like. (i.e. `plugins`)

4) In `.vim/pack/[FOLDER]` add a folder called `start`

5) move or clone the repository into `.vim/pack/[FOLDER]/start`
