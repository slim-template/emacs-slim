# Synopsis

`slim-mode` provides Emacs support for editing
[Slim](http://slim-lang.com) templates. It's based on `haml-mode`.

![Screenshot](http://i50.tinypic.com/2441b8i.png)

# Installation

All users are encouraged to install `slim-mode` via package.el.

## Manual

Just drop `slim-mode.el` somewhere in your `load-path`. I favour the
folder `~/.emacs.d/vendor`:

```lisp
(add-to-list 'load-path "~/emacs.d/vendor")
(require 'slim-mode)
```

## Marmalade

If you're an Emacs 24 user or you have a recent version of package.el
you can install `slim-mode` from the
[Marmalade](http://marmalade-repo.org/) repository.

## MELPA

If you're an Emacs 24 user or you have a recent version of package.el
you can install `slim-mode` from the
[MELPA](http://melpa.milkbox.net/) repository.

## Emacs Prelude

`slim-mode` is part of the
[Emacs Prelude](https://github.com/bbatsov/prelude). If you're a Prelude
user - `slim-mode` is already properly configured and ready for
action.

# Usage

Just start editing slim files. :-)

# Caveats

The mode is a work in progress and not everything is implemented
yet. Be patient and send bug reports when you notice that something is
wrong/missing/not perfect.

## Known issues

Check out the project's
[issue list](https://github.com/slim-template/emacs-slim/issues?sort=created&direction=desc&state=open)
a list of unresolved issues. By the way - feel free to fix any of them
and sent us a pull request. :-)

## Contributors

Here's a
[list](https://github.com/slim-template/emacs-slim/contributors) of
all the people who have contributed to the development of `slim-mode`.

## Bugs & Improvements

Bug reports and suggestions for improvements are always
welcome. GitHub pull requests are even better! :-)

Cheers,<br>
The `slim-mode` Team
