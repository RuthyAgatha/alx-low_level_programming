This project is about file descriptor which is a unique identifier (handle) for a file or other input/output resource, such as a pipe or network socket.
File descriptors typically have non-negative integer values, with negative values being reserved to indicate "no value" or error conditions.
File descriptors are a part of the POSIX API. Each Unix process (except perhaps daemons) should have three standard POSIX file descriptors, corresponding to the three standard streams:
