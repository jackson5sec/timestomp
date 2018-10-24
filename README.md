ts
=======
c/c++ timestomp utility (ts.exe)

works with millsecond cloning

Usage
=======
    ts.exe --help
    Clear MACE: ts.exe -m <file>
    Clone MACE: ts.exe -c <source file> <dest file>
    Author: Jackson5

Example
=======
Clear MACE records. Based off msf clearing

    ts.exe -m C:\users\user\sample.exe

Clone MACE records from source to destination.

    ts.exe -c C:\windows\system32\cmd.exe C:\users\user\sample.exe

References:

https://github.com/rapid7/meterpreter/blob/master/source/extensions/priv/server/timestomp.c
