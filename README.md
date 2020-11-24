# `rid` for .NET
Joke command for the Windows command line. Prints out sarcastic messages whenever you incorrectly type `dir`. Think of it as an homage to [`sl`](https://github.com/mtoyoda/sl) but for Windows.

The project is targetted for .NET Framework, not .NET Core, so it'll only compile on Windows, unless you were to take the existing code and retarget it for .NET Core. (you may have to remove a few lines of code to get it to compile for macOS or Linux)

This is the original `rid` for Windows only, a [cross-platform version](https://www.github.com/SpeedStriker243/rid-cpp) exists, done in C++, which contains instructions for building on Windows, macOS and Linux. Changes in program behaviour (i.e., new messages, changed messages, different method of providing messages) will be synced with the cross-platform version.
