# lolbin-poc

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