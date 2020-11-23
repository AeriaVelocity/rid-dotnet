# `rid`
Joke command for the Windows command line. Prints out sarcastic messages whenever you incorrectly type `dir`. Think of it as an homage to [`sl`](https://github.com/mtoyoda/sl) but for Windows.

It's done in .NET C#, but I might rewrite the program in C++. Probably not, though.

By the way, it's .NET Framework, not .NET Core, so it'll only compile on Windows, unless you took the existing code and retargeted it for .NET Core. (shouldn't be too hard, the program doesn't use any Windows-specific features)
