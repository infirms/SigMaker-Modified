# SigMaker-Modified
Modified version of sigmaker for convenient use by gamesense users.

# About
IDA SigMaker Plugin updated for the IDA Pro 7.0 SDK by infirms

PLEASE NOTE: IDA Freeware 7.0 is **NOT** supported. 

Originally made by ajkhoury( https://github.com/ajkhoury/SigMaker-x64 )

# Compiling

Visual Studio will expect the environment variable IDADIR to resolve to your IDA 7.0 installation directory.

Visual Studio will also expect the SDK to be located at %IDADIR%\idasdk. Make sure these folders resolve in Windows properly before attempting to build the project.

# Running the build

Because IDA no longer has a native 32-bit compiled version anymore, the Release/Debug scenarios are the build scripts for the 32-bit version of IDA and Release64/Debug64 are the build scripts for the 64-bit version.

**Do not change the target platform from x64!**

# Installing

After compiling compiler will automaticly copy plugin dll file to the path of environment variable IDADIR in plugins folder.

In case you are using pre-compiled binaries just copy them into plugins folder in your ida installation directory.

# Usage

Plugin gui can be called by simple Ctrl + Alt + S combination or with Edit-> Plugins -> SigMaker.
