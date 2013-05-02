flycheck-color-mode-line.el
===========================

An Emacs minor-mode for [Flycheck][flycheck] which colors the mode line
according to the Flycheck state of the current buffer.


Installation
------------

If you choose not to use one of the convenient packages in [Melpa][melpa]
or [Marmalade][marmalade],
you'll need to add the directory containing `flycheck-color-mode-line.el` to your
`load-path`, and then

    (require 'flymake-elixir)

    (eval-after-load "flycheck"
      '(add-hook 'flycheck-mode-hook 'flycheck-color-mode-line-mode))


Examples
--------

Here are some screenshots with the different [Solarized themes][solarized]
and the [Powerline package][powerline].

**Solarized Light**

![mode line with solarized light warning](https://raw.github.com/syl20bnr/flycheck-color-mode-line/master/doc/flycheck-color-mode-line-light-e.png)
![mode line with solarized light error](https://raw.github.com/syl20bnr/flycheck-color-mode-line/master/doc/flycheck-color-mode-line-light-w.png)

**Solarized Dark**

![mode line with solarized light warning](https://raw.github.com/syl20bnr/flycheck-color-mode-line/master/doc/flycheck-color-mode-line-dark-e.png)
![mode line with solarized light error](https://raw.github.com/syl20bnr/flycheck-color-mode-line/master/doc/flycheck-color-mode-line-dark-w.png)


Thanks
------

- [Thomas Järvstrand][tjarvstrand] for the initial code from the excellent EDTS package
- [Sebastian Wiesner][lunaryorn] for flycheck and his awesome support.


[flycheck]: http://github.com/lunaryorn/flycheck
[melpa]: http://melpa.milkbox.net
[marmalade]: http://marmalade-repo.org
[solarized]: http://github.com/bbatsov/solarized-emacs
[powerline]: http://github.com/milkypostman/powerline
[tjarvstrand]: http://github.com/tjarvstrand
[lunaryorn]: http://github.com/lunaryorn
