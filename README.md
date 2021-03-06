# tiler.vim
Tiling window manger for Vim

## Features
  1. multiple layouts,
	2. can increase or decrease master window count on the fly,
	3. support for popups e.g. nerdtree, tagbar, quickfix, etc,
	4. each tab has its own settings

See the help file for more information.

![example](https://user-images.githubusercontent.com/1034743/31067325-e97fe69e-a717-11e7-8663-bd67a80c5312.gif)

# Install
Using vim-plug:

```
Plug 'zhamlin/tiler.vim'
```

# Commands

| Command               | List                                                                   |
| ---                   | ---                                                                    |
| `TilerFocus`          | Moves current window to master window                                  |
| `TilerReorder`        | Creates the correct window layout                                      |
| `TilerClose`          | Closes current window                                                  |
| `TilerNew`            | Opens a new window                                                     |
| `TilerOpen [FILE]`    | Opens a file in a new window                                           |
| `TilerResize [SIZE]`  | Resizes master window to [SIZE]                                        |
| `TilerSwitch [LAYOUT]`| Switches the current layout to [LAYOUT]                                |
