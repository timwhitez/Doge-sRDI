![Doge-sRDI](https://socialify.git.ci/timwhitez/Doge-sRDI/image?description=1&font=Raleway&forks=1&issues=1&language=1&logo=https%3A%2F%2Favatars1.githubusercontent.com%2Fu%2F36320909&owner=1&pattern=Circuit%20Board&stargazers=1&theme=Light)

- 🐸Frog For Automatic Scan

- 🐶Doge For Defense Evasion&Offensive Security

# Doge-sRDI
Shellcode implementation of Reflective DLL Injection by Golang. Convert DLLs to position independent shellcode

## Big thanks to Sliver project and leoloobeek
[Sliver](https://github.com/BishopFox/sliver)

[ShellcodeRDI.go](https://gist.github.com/leoloobeek/c726719d25d7e7953d4121bd93dd2ed3)

[sRDI raw project](https://github.com/monoxgas/sRDI)

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

## 🚀Star Trend
[![Stargazers over time](https://starchart.cc/timwhitez/Doge-sRDI.svg)](https://starchart.cc/timwhitez/Doge-sRDI)


## etc
1. 开源的样本大部分可能已经无法免杀,需要自行修改

2. 我认为基础核心代码的开源与整理能够帮助想学习的人
 
3. 本人从github大佬项目中学到了很多，感谢
 
4. 若用本人项目去进行：HW演练/红蓝对抗/APT/黑产/恶意行为/违法行为/割韭菜，等行为，本人概不负责，也与本人无关

5. 本人已不参与大小HW活动的攻击方了，若溯源到timwhite id与本人无关
