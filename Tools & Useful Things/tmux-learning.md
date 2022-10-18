# TMUX learning
Tmux is a multiplexer. That allows you to craft a single terminal however you need it.

## Essential Tmux Commands
To launch tmux simply run the command below
```bash
tmux
```
when tmux launches the session is automatically called "0" if you want to change the session name to something more meaningful you can use the following keyboard command `Ctrl+b Shift+$` every tmux command will start with the same prefix of `Ctrl+b` 
![[Pasted image 20221018213202.png]]
To create a new tmux session without attaching to it you can run the following command
```bash
tmux new -s tmux_learning -d
```
the -s flag specifies the session name and the -d flag means to start the new session as detached.

to list all tmux sessions you can run the command: `tmux ls`
to exit a tmux session without closing it you can press the following keys `Ctrl+b d`
to reattach to a session run the command `tmux attach -t SESSION_NAME`

