---
title: Top 11 Most Useful Tmux commands
description: Unleash the power of tmux with these 10 powerful commands
date: 2021-08-01
tags: linux
layout: layouts/post.njk
---

Tmux is a very powerful commandline tool for managing multple terminal windows and sessions.
It is one of the tools you never know you need until you start using. 

### 1. Starting tmux
`tmux`

### 2. Creating named tmux session
 `tmux new -t session-name`

### 3. Detach from a session
`prefix d`

### 4. Attach to a session
`tmux attach -t session-name`

### 5. List all available sessions
`prefix w`

### 6. Kill or Close a pane
`prefix x`
... then accept by entering `y`

### 7. Create a new window
`prefix c`

### 8. Go to next window
`prefix n`

### 9. Go to previous window
`prefix p`

### 10. Toggle last active pane
`prefix ;`

### 11. List key bindings
`prefix? `
