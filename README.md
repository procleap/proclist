# Proclist

Small ASM program to list processes and their PIDs. Windows only. Licence MIT.

You can compile it using [fasm](https://flatassembler.net). 

## Example Output

```
C:>.\proclist.exe
==================================
PID      EXE FILE
==================================
0        [System Process]
4        System
56       Secure System
428      smss.exe
676      csrss.exe
776      wininit.exe
784      csrss.exe
848      services.exe
856      LsaIso.exe
876      lsass.exe
960      winlogon.exe

[...] Remaining lines deleted for shortness.
```