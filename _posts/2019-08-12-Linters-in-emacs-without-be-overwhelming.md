---
layout: post
title: "Linters in Emacs"
categories: [binary]
date: 2019-08-12
---

```elisp
(add-hook 'python-mode-hook
		  (lambda ()
			(setq flycheck-pylintrc "~/.emacs.d/.pylintrc")
			(setq indent-line-function #'my-python-indent-line)))
```
