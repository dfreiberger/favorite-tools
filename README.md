# Favorite Troubleshooting Tools as a Control Systems Engineer

This repository lists tools I have found extremely helpful for troubleshooting software and digging into the details of applications which may not have good documentation or APIs.

## Windows Specific tools

### Process Explorer

[Process Explorer](https://docs.microsoft.com/en-us/sysinternals/downloads/process-explorer) is a great tool for digging into the details of running processes. It can be used to view the command line arguments used to start a process, the environment variables, and the DLLs loaded by the process. It can also be used to view the handles and threads used by a process. I use this mainly to figure out what DLLs are being used by an application so that I can better understand the application structure.

### Process Monitor

[Process Monitor](https://docs.microsoft.com/en-us/sysinternals/downloads/procmon) is a tool for monitoring the file system, registry, and process activity on a Windows system. It can be used to see what files and registry keys are being accessed by a process, and what processes are accessing a file or registry key. This is useful when troubleshooting applications or if you want to automate something that is normally done through the GUI and not exposed or documented by the software vendor. 

### WinDbg Preview

[WinDbg Preview](https://www.microsoft.com/en-us/p/windbg-preview/9pgjgd53tn86) is a modernized version of windbg. It can be used to attach to a running process and view the call stack, set breakpoints, and view the values of variables. 

### Fiddler

[Fiddler](https://www.telerik.com/fiddler) is a free web debugging proxy. It can be used to capture and analyze HTTP and HTTPS traffic.

## .NET

### JetBrains dotPeek

[JetBrains dotPeek](https://www.jetbrains.com/decompiler/) is a free .NET decompiler. It can be used to view the source code of .NET assemblies and is very useful when troubleshooting .NET applications.

### dnSpy

[dnSpyEx](https://github.com/dnSpyEx/dnSpy) is a free .NET debugger and assembly editor. It can be used to view the source code of .NET assemblies as well as debug and edit them.

## Cross-Platform Tools

### Wireshark

[Wireshark](https://www.wireshark.org/) is a free network protocol analyzer. It can be used to capture and analyze network traffic. It is an essential tool for any control system engineer and you can use it to troubleshoot network issues, reverse engineer protocols, and debug applications.

### Meld

[Meld](https://meldmerge.org/) is a free visual diff and merge tool. It can be used to compare files and directories. This is particularly useful when trying to troubleshoot issues occuring on one system but not on another, since it gives a very easy way to compare entire directory structures or individual files. Of course this can be useful to learn what has changed between two versions of an application as well.

### ghidra

[ghidra](https://ghidra-sre.org/) is a free reverse engineering tool. It can be used to analyze binaries and decompile them into C code as well as edit the assembly code.

### Postman

[Postman](https://www.postman.com/) is a free API development environment. It can be used to send HTTP requests and view the responses. It is very useful for troubleshooting REST APIs or building interfaces to applications that don't offer a documented API.

### Chrome Developer Tools

[Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools) is a set of web developer tools built into the Chrome browser. It can be used to debug JavaScript, analyze network traffic, and view the DOM. It is very useful for troubleshooting web applications.

