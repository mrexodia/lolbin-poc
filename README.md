# lolbin-poc

Small PoC of using a Microsoft signed executable as a lolbin.

![image](https://user-images.githubusercontent.com/2458265/221688556-d3199385-fc37-4d98-b5e2-52181e2665da.png)

## Building (32-bit)

```
cmake -B build32 -A Win32
cmake --build build32 --config Release
```

## Building (64-bit)

```
cmake -B build64 -A x64
cmake --build build64 --config Release
```

## Usage

Download WinDbg from [here](https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger/debugger-download-tools), put the compiled `dbgeng.dll` next to `windbg.exe`.

## Bonus

There's also a bunch of other DLLs you can use:

![image](https://user-images.githubusercontent.com/2458265/221688609-5dd62990-b594-44ab-bc66-a748965f483c.png)
