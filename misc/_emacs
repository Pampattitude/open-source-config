;; MELPA
(require 'package) ;; You might already have this line
(add-to-list 'package-archives '("melpa" . "https://melpa.org/packages/"))
(add-to-list 'package-archives '("melpa-stable" . "https://stable.melpa.org/packages/"))

(package-initialize) ;; You might already have this line

;; Tabs
(setq-default indent-tabs-mode nil)
(setq c-basic-indent 2)
(setq js-indent-level 2)
(setq tab-width 2)
(setq indent-tabs-mode nil)

(add-hook 'before-save-hook 'delete-trailing-whitespace) ;; Trailing whitespaces

;; Comment line via C-c C-c
(global-set-key "\C-c\C-c" 'comment-region)
