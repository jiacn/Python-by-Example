# Python by Example
## Parallel Programming
+ Process and Thread
- The typical difference is that threads (of the same process) run in a shared memory space, while processes run in separate memory spaces.
- Threads within the same process share memory, so data transfer between threads is just a case of referencing the shared objects.
- Processes do not share memory, so other interfaces, such as files, sockets, or specially allocated areas of shared memory, must be used for transferring data between processes.


