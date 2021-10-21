# nofrils

This is a fork of nofrils: an extremely minimalist vim colorscheme.

This fork adds _some_ color while still trying to preserve the spirit of the colorscheme and fixes some broken stuff.
It also tries to support Neovim and various plugins to make them look decent and not totally broken.

## Usage

To use:

- `:colo nofrils-dark`
- `:colo nofrils-light`
- `:colo nofrils-sepia`
- `:colo nofrils-acme`

To customize:

- `:let g:nofrils_strbackgrounds=1` to turn highlighted string backgrounds, for languages where strings are a major part of them
- `:let g:nofrils_heavycomments=1` to turn on high contrast comments rather than the default faded style, for projects where the comments are not deceit and lies
- `:let g:nofrils_heavylinenumbers=1` to turn on brighter line numbers, for people who use relative line numbers to hop around

Commands (once theme is loaded):

- `:NofrilsDark` use dark theme
- `:NofrilsLight` use light theme
- `:NofrilsSepia` use sepia theme
- `:NofrilsAcme` use acme theme
- `:NofrilsFocusNormal` reset back to normal settings
- `:NofrilsFocusCode` focus only code, fade everything else
- `:NofrilsFocusComments` focus only comments, fade everything else

The only highlighted elements are spelling, errors, comments, vim features (diff, etc) and _optionally_ string backgrounds

**Click for non-fuzzified versions**

_nofrils-dark_: **`:let g:nofrils_heavylinenumbers=1`**, **`:let g:nofrils_strbackgrounds=1`** and **`:let g:nofrils_heavycomments=1`**
![Dark Version](http://i.imgur.com/1lUx2hY.png)

---

_nofrils-acme_: **`:let g:nofrils_heavylinenumbers=0`**, **`:let g:nofrils_strbackgrounds=0`** and **`:let g:nofrils_heavycomments=0`**
![Acme Version](http://i.imgur.com/yn7OJrY.png)

---

_nofrils-sepia_: **`:let g:nofrils_heavylinenumbers=1`**, **`:let g:nofrils_strbackgrounds=0`** and **`:let g:nofrils_heavycomments=1`**
![Sepia Version](http://i.imgur.com/zwW5kir.png)

---

_nofrils-light_: **`:let g:nofrils_heavylinenumbers=0`**, **`:let g:nofrils_strbackgrounds=0`** and **`:let g:nofrils_heavycomments=1`**
![Light Version](http://i.imgur.com/XXoxztJ.png)

---

_nofrils-acme_: **`:let g:nofrils_heavylinenumbers=0`**, **`:let g:nofrils_strbackgrounds=0`** and **`:let g:nofrils_heavycomments=0`**
![Diffs Arcme Version](http://i.imgur.com/cLcbq7M.png)

---

Why did you even create this thing? https://www.robertmelton.com/2016/03/13/syntax-highlighting-off/

---

Forks

- [Kakoune](http://kakoune.org/): https://github.com/robertmeta/nofrils-kakoune
- [Atom](https://atom.io/): https://atom.io/themes/nothrill-dark-syntax
- [VSCode](https://code.visualstudio.com/): https://github.com/urld/vscode-nofrills
- [Emacs](https://www.gnu.org/software/emacs/): https://gitlab.com/esessoms/nofrils-theme
- [Emacs](https://www.gnu.org/software/emacs/): https://github.com/lthms/nordless-theme.el (not exact a port, but useful for nofrils desires)
- [Micro](https://micro-editor.github.io/): https://git.sr.ht/~cac04/micro-nofrils
