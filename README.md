To use this tool you will need to change Line 5 to desired IP and Line 6 to desired port 

To set up the listener use command nc -lvnp 9001(port number can be changed to specific choice ) 

In case where its failed to daemonise  encoding should be used : URL encoding -double URL encoding - Base64 

The shell can be used for the following : 
sh, /bin/bash, /bin/sh, cmd, bash, powershell, pwsh, ash, bsh, csh, ksh, zsh, pdksh, tcsh, mksh, dash

Program limitations: 
proc_open and stream_set_blocking require PHP version 4.3+, or 5+
Use of stream_select() on file descriptors returned by proc_open() will fail and return FALSE under Windows.
Some compile-time options are needed for daemonisation (like pcntl, posix).  These are rarely available.


This tool may be used for legal purposes only.  Users take full responsibility
for any actions performed using this tool.  The author accepts no liability for
damage caused by this tool.  If these terms are not acceptable to you, then do 
not use this tool.


