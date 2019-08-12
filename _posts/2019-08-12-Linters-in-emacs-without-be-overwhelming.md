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

```python
print("Hello world")
```
```ruby
    def sum_eq_n?(arr, n)
      return true if arr.empty? && n == 0
      arr.product(arr).reject { |a,b| a == b }.any? { |a,b| a + b == n }
    end
```
