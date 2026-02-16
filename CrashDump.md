# CrashDump
## Task 1
Open the dmp file using WinDbg and then press ctrl+f to search for "version". The version will be found in path validation summary section.

![alt text](Images/image.png)

## Task 2
Run `!peb` on the command line at the bottom of command tab on WinDbg. PEB stores:
- Full image path
- Command line arguments
- Current directory
- Loaded DLL information
This is often used for malware analysis

![alt text](peb.png)