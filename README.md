# `rid` for .NET
Joke command for the Windows command line. Prints out sarcastic messages whenever you incorrectly type `dir`. Think of it as an homage to [`sl`](https://github.com/mtoyoda/sl) but for Windows.

The project is targetted for .NET Framework, not .NET Core, so it'll only compile on Windows, unless you were to take the existing code and retarget it for .NET Core. 

This is the original `rid` for Windows only, a [cross-platform version](https://www.github.com/SpeedStriker243/rid-cpp) exists, done in C++, which contains instructions for building on Windows, macOS and Linux. Changes in program behaviour (i.e., new messages, changed messages, different method of providing messages) will be synced with the cross-platform version.

## Building instructions
You need to have [Visual Studio](https://visualstudio.microsoft.com/vs/) installed with at least .NET Framework 4.8.
Open `rid.csproj` and run the project. It'll run, and it'll also make an executable. Right click on the project in the Solution Explorer, then click 'Open File in File Explorer'. Then navigate to `\bin\Debug\` to find `rid.exe`.

Either place `rid.exe` in `C:\Windows\System32` or place it wherever and add it to your system's PATH, then you can run `rid` straight from the command prompt.

You can skip adding to PATH, but you then have to specify where `rid.exe` is.
