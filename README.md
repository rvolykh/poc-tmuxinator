# poc-tmuxinator

Example of preconfigured tmux session by using [tmuxinator](https://github.com/tmuxinator/tmuxinator).

## Installation

```shell
brew install tmux tmuxinator
```

## Cheatsheet

1. Start
```shell
tmuxinator local
```

2. Select window
```shell
CTRL+B <window-number, e.g. 1) # by index, e.g. 0, 1, 2, 3
CTRL+B n # next
CTRL+B p # previous
```

3. Select pane
```shell
CTRL+B <arrow-key> # by direction, e.g. left, up, right, down
CTRL+B o # next
```

4. Disable or enable pane synchronization
```shell
CTRL+B :
setw synchronize-panes off/on
```

5. Zoom in/out pane:
```shell
CTRL+B z
```

6. Exit tmux
```shell
CTRL+B :
kill-session
```
