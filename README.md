# mql5-mode

Emacs major mode for editing MQL5.

## Features
- Auto-completion using `company`
- Syntax Highlight for all MQL5 keywords

## Usage (for Spacemacs)
You need to add `c-c++` Layer in advance.

Place `mql5-mode.el` in the following path:

```
~/.emacs.d/private/local/mql5-mode.el
```

Add the following code inside `dotspacemacs/user-config()`

```
(load-file "~/.emacs.d/private/local/mql5-mode.el")
```
