# urxvt-softclear

Simple extension that replace the clear shortcut (C-l) to avoid erasing
lines on screen.

## Installation

Copy the soft-clear to the urxvt extension folder :
```
wget https://raw.githubusercontent.com/burton-aad/urxvt-softclear/master/soft-clear -O ~/.urxvt/ext/soft-clear
```

After installing, enable the extension by adding the following line in your
`~/.Xresources`:

```
URxvt.perl-ext-common: ...,soft-clear
```
