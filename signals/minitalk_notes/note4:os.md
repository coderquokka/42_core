### ps aux | grep a.out

## ps
-proc status : disp info about active processes

-a: proc for all users
-u: user who owns each proc along with details CPU, mem usage
-x: proc which are not attached to a terminal, 
     all proc, regardless of how they were started

## ps aux
USER       PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
jiepark   79581  0.0  0.0   2776  1344 pts/1    S+   13:07   0:00 ./a.out

-user: who owns the proc
-%CPU: percentage of CPU usage
-%MEM: percentage of MEM usage
-VSZ: virtual mem size used by the proc
-RSS: resident set size (amount of physical mem used)
-TTY: terminal associated with the proc, if any
-stat: proc states (running, sleeping, ...)
-start: when the proc started
-time: cumulative CPU time the proc has used
-command: coammnd that started the proc

# 
