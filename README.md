# Doge-sRDI
Shellcode implementation of Reflective DLL Injection by Golang. Convert DLLs to position independent shellcode

## Big thanks to Sliver project and leoloobeek
[Sliver](https://github.com/BishopFox/sliver)

[ShellcodeRDI.go](https://gist.github.com/leoloobeek/c726719d25d7e7953d4121bd93dd2ed3)

## Usage
srdi.exe [dllName] [Args(not necessary)] [entryPoint(not necessary)]
```
PS D:\> .\srdi.exe .\Outflank-PsC.dll
Outflank-PsC.bin
PS D:\> .\loader.exe .\Outflank-PsC.bin 1
Mess with the banana, die like the... banana?

--------------------------------------------------------------------

[+] ProcessName:   svchost.exe
    ProcessID:     3968
    PPID:          940 (services.exe)
    CreateTime:    17/03/2021 21:01
    Path:          C:\Windows\System32\svchost.exe
    ImageType:     64-bit
    CompanyName:   Microsoft Corporation
    Description:   Windows ?????
    Version:       10.0.19041.867

......
```
