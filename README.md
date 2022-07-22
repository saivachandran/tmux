tmux steps
-------------

# tmux installation
-------------------

```
sudo apt update -y
sudo apt install tmux -Y
```

# type tmux first terminal
--------------------------
```
tmux
```

# split the window vertical
```
ctrl+b  %
```
# split the window horizontal
```
ctrl+b  "
```

# siwtch between window
-----------------------
```
ctrl+b   <--  

ctrl+b   -->  
```
# rename window
--------------
```
ctrl+b ,
```
type name enter

# swtich between terminal
------------------------

ctrl+b 0

ctrl+b 1

# detach terminal
----------------
```
ctrl+b  d
```

# list detach screen
--------------------
```
tmux ls
```

# attach the detached terminal
------------------------------
```
tmux attach -t docker
```

# rename detached terminal
--------------------------

```
tmux rename-session -t docker docker1
```

# kill the session

```
tmux kill-session -t docker1 
```

# Switching between terminal windows
```
CTRL+b w
```









