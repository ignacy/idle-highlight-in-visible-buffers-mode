# Idle-highlight-in-visible-buffers-mode

A minor mode for Emacs that does what `idle-highlight-mode` but for all visible buffers.

# Setup

```elisp
  (require 'idle-highlight-in-visible-buffers-mode)
  ;; Optional
  (set-face-attribute 'idle-highlight-in-visible-buffers nil :foreground "SpringGreen3" :weight 'bold)
  (add-hook 'prog-mode-hook 'idle-highlight-in-visible-buffers-mode)
```

# Screenshots

With idle-highlight-mode

![before](/images/before.png?raw=true "idle-highlight-mode")

With idle-highlight-in-visible-buffers-mode

![after](/images/after.png?raw=true "idle-highlight-in-visible-buffers-mode")
