flycheck-lilypond
================

Make [Flycheck][] syntax-check LilyPond files.

Installation
------------

With [`use-package`][use-package] in your init file:

```el
(use-package flycheck
  :ensure t
  :defer t
  :init (add-hook 'LilyPond-mode-hook 'flycheck-mode)
  :config
  (use-package flycheck-lilypond
    :ensure t))
```

Or manually from [MELPA][] with <kbd>M-x package-refresh-contents</kbd>
and <kbd>M-x package-install RET flycheck-lilypond</kbd>.

Usage
-----

Just use Flycheck as usual in [LilyPond mode][LilyPond-mode].

License
-------

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see http://www.gnu.org/licenses/.

See [`COPYING`][copying] for details.

[Flycheck]: https://github.com/flycheck/flycheck
[use-package]: https://github.com/jwiegley/use-package
[MELPA]: http://melpa.milkbox.net
[COPYING]: https://github.com/hinrik/flycheck-lilypond/blob/master/COPYING
[LilyPond-mode]: http://lilypond.org/doc/latest/Documentation/usage/text-editor-support#emacs-mode
