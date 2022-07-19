# .bashrc
Add these commands to `.bashrc` file.
```
if command -v tmux &> /dev/null && [ -n "$PS1" ] && [[ ! "$TERM" =~ screen ]] && [[ ! "$TERM" =~ tmux ]] && [ -z "$TMUX" ]; then
  exec tmux
fi
```

Installing `xclip` so you can copy the output from the tmux session to the system clipboard using vim key bindings.
```
$ sudo apt-get install xclip
```
