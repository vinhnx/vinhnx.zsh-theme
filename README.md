# oh-my-zsh theme
-----------------
This is my modified theme from [themes/mgutz.zsh-theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/mgutz.zsh-theme) for [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) (zshell) with minimal effort.
Looks great when using with Solarized color scheme.

### New Update: 09/14/2012
* Replaced `»` with dollar sign `$`.
* Combined all into one line to save spaces.

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

<a rel="license" href="http://creativecommons.org/licenses/by-nc/3.0/deed.en_US"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc/3.0/80x15.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">vinhnx.zsh-theme</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://vinhnx.github.com" property="cc:attributionName" rel="cc:attributionURL">Vinh Nguyen</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/3.0/deed.en_US">Creative Commons Attribution-NonCommercial 3.0 Unported License</a>.