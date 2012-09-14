# oh-my-zsh theme
-----------------
This is my modified theme from [themes/mgutz.zsh-theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/mgutz.zsh-theme) for [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) (zshell) with minimal effort.
Looks great when using with Solarized color scheme.

<<<<<<< HEAD
## Screenshots
=======
### New Update: 09/14/2012
* Added another style with dollar sign
* Concatinated into one line to save spaces.
* [View the alternative code](https://github.com/vinhnx/vinhnx.zsh-theme/blob/alt-layout/vinhnx.zsh-theme)

## Screenshot
>>>>>>> 94557b3... edit README

![git diff](http://i.imgur.com/lXcjv.png)

![git commit](http://i.imgur.com/H5z5M.png)

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
