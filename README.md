# Installation

## ELPA and MELPA

No way.

## Manual installation

1. Clone this repo to `~/.emacs.d/qsharp-mode/`:

    ```
    git clone git://github.com/forked-from-1kasper/emacs-qsharp-mode`
    ```

2. Add the following to your `init.el`:

    ```lisp
    (add-to-list 'load-path "~/.emacs.d/qsharp-mode/")
    (autoload 'qsharp-mode "qsharp-mode" "Major mode for editing Q# code." t)
    (add-to-list 'auto-mode-alist '("\\.qs$" . qsharp-mode))
    ```

3. ???

4. PROFIT!
