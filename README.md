# MountEFI
A more robust edition of my previous MountEFI script

Added my usual collection of disk functions - plus some experimentation with callback functions.

-

Todo:

In the future, I plan to allow input/output based on another script.

For example:  If another script calls `MountEFI -mount disk0s1` then my script would mount without user interaction, and return a 0 on success, or a 1 on failure.