# Day 14 - [Understanding Processes]


## Objective

What was the goal for today?

The goal for today was to understand what processes are in Linux, how they run, and how to monitor and control them.


## What I Learned

A process is a running instance of a program.

Every process has a unique PID (Process ID).

Processes can run in:

Foreground (blocks the terminal)

Background (runs without blocking using &)

A process can have parent and child relationships.

Linux provides commands to monitor and manage processes.

Some processes finish immediately, while others run continuously (e.g., loops).


## What I Built / Practiced

Running a script in the background:

python3 script.py &

Viewing running processes:

ps
ps aux

Searching for a specific process:

ps aux | grep script.py

Stopping a process:

kill <PID>

Force stopping a process:

kill -9 <PID>

Killing a process by name:

pkill -f script.py


## Challenges Faced

Trying to kill a process that had already finished.

Using incorrect syntax like kill <PID> instead of kill PID.

Confusion when ps aux | grep showed the grep command itself.

Managing short-lived vs long-running processes.

Trying to kill a process but didnt stop until i use the right command pkill -9 -f script.py



## Key Takeaways

Not all processes stay alive long enough to manage.

Always confirm a process is running before killing it.

kill requires the correct PID and proper syntax.

pkill is faster when dealing with process names.

Background processes (&) are useful but require proper monitoring.


## Resources

https://www.geeksforgeeks.org/linux-unix/processes-in-linuxunix/

https://github.com/Najeeb-Sulaiman/linux-and-bash-scripting-guide/blob/main/05-linux-processes/01-understanding-processes.md



## Output


 ps
 ps -f
 ps 19
 top
 ps aux
 htop
 ps aux | grep python
 python script.py &
 python3 script.py &
 python script.py &
 ls
 touch scrip.py
 touch script.py
 nano script.py
 python3 script.py &
 fg
 bg
 kill <183101>
 kill 183101
 ps
 ps aux | grep python
 python3 -c "import time; while True: time.sleep(1)"
 nano script.py
 python3 script.py &
 kilkill 183101
 kill -9 183101
 pkill -9 -f script.py
 ps aux | grep script.py


