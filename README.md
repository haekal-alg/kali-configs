# .bashrc
Add these commands to `.bashrc` file.
```
if command -v tmux &> /dev/null && [ -n "$PS1" ] && [[ ! "$TERM" =~ screen ]] && [[ ! "$TERM" =~ tmux ]] && [ -z "$TMUX" ]; then
  exec tmux
fi
alias cb=clipboard
```

Installing `clipboard-cli`
```
$ sudo apt-get install npm
$ sudo npm install --global clipboard-cli
```
