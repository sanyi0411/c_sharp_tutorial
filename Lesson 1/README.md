# Basics

## What is C#?
- C# is a programming language, created by Microsoft.
- It is based on C/C++ and Java.

## What is Just-in-time compilation?
- C/C++ code is compiled to the native code of the machine on which it is compiled. This means that this compiled code won't run on another system with a different architecture or different operating system.
- Java code is compiled to someting called `ByteCode`, the instruction set of Java Virtual Machine (JVM), and it is independent of the machine on which it is running. This means that any computer, that has JVM, can run any `ByteCode`.
- Just-in-time (JIT) compilation means that only those parts of the code are compiled that are needed at the moment. Basically the code is compiled and executed at the same time.
- JVM uses just-in-time compilation to compile `ByteCode` to the native code of the machine.
- C# is similar: it is compiled to `Intermediate Language (IL)` code, the equivalent of `ByteCode`, and than that is turned into native code.

## What is the Common Language Runtime?
- Common Language Runtime (CLR), also called .NET Runtime, turns the `Intermediate Language (IL)` code to the native code of the machine on which it is running.
- It is the equivalent of JVM for Java.

## What is .NET?
- [.NET](https://dotnet.microsoft.com/en-us/learn/dotnet/what-is-dotnet) is a developer platform, a framework for building applications.
- A developer platform is the language you write the code in and the libraries you use the create a program.
- .NET is not limited to C#. You can use other languages to target .NET, like F# and Visual Basic.
- C# cannot run without .NET as C# is only compiled to `IL` code and .NET can compile that to native code. Janky workarounds exist but without .NET and it's libraries a simple command line input/output would be hard to execute.
- .NET can be used to create applications for desktop, web, mobile, IoT, games etc.

### .NET implementations

- `.NET Framework` is the original .NET implementation. It was released by Microsoft in the 1990s and it supports running websites, desktop apps, services and more (only) on Windows.
- `.NET Core` is an open-source software that enables cross-platform support for developers. It was launched in 2014 and it supports all major operating systems.
- `.NET Standard` is a formal specification of different APIs. The implementations use .NET standard APIs and unique APIs specific to the operating system.

### .NET architecture
- 3 main components:
    - .NET languages
    - Application model frameworks
    - .NET runtime
- .NET languages are C#, F# and Visual Basic
- .NET runtime is the `Common Language Runtime (CLR)` that does the just-in-time compilatio and the execution of the program.
- The application model frameworks are a collection of developer tools and libraries. Different frameworks exist for different types of applications:
    - `ASP.NET` extends .NET specifically for building web-based applications.
    - `Xamarin` can be used to create mobile applications with consistent user experience across all mobile platforms.
    - `Universal Windows Platform` extends .NET for Windows 10 application development.
    - `ML.NET` can be used to integrate machine learning into .NET applications.

## Installation

- Download and install the latest [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/).
- Choose the `.NET desktop development` package during installation.