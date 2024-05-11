# Init

## Plugin manager
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
```tmux
set -g @plugin 'tmux-plugins/tpm'

# Initialize TMUX plugin manager (keep this line at the very bottom of tmux.conf)
run '~/.tmux/plugins/tpm/tpm'
```


# Keys
<C-x> - leader key

`<leader>c` - create new window
`<leader>n` - next window
`<leader>p` - prev window
`<leader>"` - split vertical
`<leader>%` - split horizonal

`<leader>:rename-window {name}`
`<leader>:rename-session {name}`

`<leader>d` - detach window

`tmux ls` - list of sessions

`<leader>s` - sessions view

`<leader>I` - install plugins
