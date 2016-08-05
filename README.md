# acme-mode.el

This project is an [Emacs](https://www.gnu.org/software/emacs/) major mode for the
[Acme Assembler](https://web.archive.org/web/20150520143433/https://www.esw-heim.tu-clausthal.de/~marco/smorbrod/acme/).

## Installation

In order to install acme-mode for Emacs, copy acme-mode.el into your local
site-lisp directory and add the following lines to your ~/.emacs:

```lisp
(autoload 'acme-mode "acme-mode"
    "Major mode for editing Acme 6502 sources." t)

(add-to-list 'auto-mode-alist '(".acme$" . acme-mode))
```

## History

Forked from <https://github.com/afwlehmann/acme-mode> August 2016.

Additional changes by Adam Vandenberg (flangy@gmail.com).
