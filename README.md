# CoreDllMap
DllMap implementation for .NET Core 3.0+. The goal of this library is to provide .NET Core projects with [the DllMap feature of the Mono runtime](https://www.mono-project.com/docs/advanced/pinvoke/dllmap/), matching Mono's behavior as closely as possible.

## Build Instructions
1. Install .NET Core 3.0 or later.
2. Run `dotnet build` in the project directory.
3. Grab the output CoreDllMap.dll, and ship it!

## Usage Instructions
Call `CoreDllMap.Register()`, passing in the assembly you want to register with dllmap. That's it!
