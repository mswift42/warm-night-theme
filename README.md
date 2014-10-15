warm-night-theme
================

emacs24 theme with a dark background and warm colors.

Created with [Emacs Theme Creator](http://emacs-theme-creator.appspot.com).

Screenshots:
------------

Code samples of go and Org-mode:

![Screenshot](https://github.com/mswift42/warm-night-theme/raw/master/screen-go-org.png)

Javascript and Common Lisp:

![Screenshot](https://github.com/mswift42/warm-night-theme/raw/master/screen-js-cl.png)


Installation Instructions
-------------------------

add the following lines to your init.el (only if you have not done so already):

    (setq package-archives '(("gnu" . "http://elpa.gnu.org/packages/")
                             ("melpa" . "http://melpa.milkbox.net/packages/")))
    (package-initialize)



This will add the gnu and melpa repos to your emacs setup.

To install the theme:

**M-x package-install** warm-night-theme


To use the warm-night theme when starting emacs, add this to your init.el:

    (load-theme 'warm-night)
