# oh-my-zsh theme
-----------------
This is my modified theme from [themes/mgutz.zsh-theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/mgutz.zsh-theme) for [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) (zshell) with minimal effort.
Looks great when using with Solarized color scheme.

## Screenshots

![screenshot](http://i.imgur.com/ERLvH.png)

## Usage
```
git clone https://github.com/vinhnx/vinhnx.zsh-theme.git
cd vinhnx.zsh-theme
cp vinhnx.zsh-theme ~/.oh-my-zsh/themes
```

Then open you `.zshrc` file and change the theme name to `vinhnx`

Or edit with vim:
```
cd ~/
vim .zshrc
```

Change the line starting with `export ZSH_THEME="..."` and replace `...` with `vinhnx`

It should look like this in your `.zshrc` file after editing:

`export ZSH_THEME="vinhnx"`

hit write & save `:wq`, then restart zsh and enjoy!

### Tips*

Solarized color sheme can be found here, choose one that suits you, then install it.
- [Solarized](http://ethanschoonover.com/solarized)

I personally use Console2  with Cygwin and Zsh, so I choose the scheme for my console2 which can be found here:
- [The Solarized theme ported to Console2](https://github.com/stevenharman/console2-solarized)

~ Happy hacking! ;)

## License ##

Copyright (c) 2013 Vinh Nguyen

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
