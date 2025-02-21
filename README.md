### tui enable
Enable TUI mode.

### Ctrl + l
Refresh the source code layout in GDB TUI mode.

### (Ctrl + x) + o
Switch TUI windows(source code / GDB command view).

### finish
Return from the function.

## multi-threaded debugging
### set scheduler-locking on/off
- When debugging multithreaded programs, set scheduler-locking on ensures that only the "current thread" executes instructions when using step or next, preventing other threads from running multiple lines of code simultaneously. The default mode is scheduler-locking off.
- It must be executed after r(running the program).

### show scheduler-locking
Show the scheduler locking mode.

### info threads
See all thread's info.

### thread tid(thread id)
Switch to the specified thread. 
