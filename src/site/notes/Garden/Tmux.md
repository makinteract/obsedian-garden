---
{"dg-publish":true,"permalink":"/garden/tmux/","tags":["cheats"]}
---

### Note

`C-b` is `ctrl+b`

### Panes

- Split horizontal: `C+b %`
- Split vertical `C+b "`
- Navigate pane `C+b <arrow>`
- Full screen: `C-b z`
- Exit: `C+d` or `exit`
    

### Windows

- New window `C-b c`
- Next window: `C-b n`
- Previous window: `C-b p`
- Rename current window `C-b ,`
    

### Session Handling

- List sessions: `tmux ls` or `tmux list-sessions`
- New session: `tmux new -s <name>`
- Attach to session: `tmux attach -t 0`or `tmux attach -t <name>`
- De-attach session: `C-b d`
- Rename session: `tmux rename-session -t 0 <name>`
    

### 

Full reference [link](https://www.hamvocke.com/blog/a-quick-and-easy-guide-to-tmux)
​