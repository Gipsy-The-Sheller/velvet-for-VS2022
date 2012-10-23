README.TXT

Windows Portable Velvet_Oases Source 

SUMMARY
A REQUIREMENTS
B COMPILING INSTRUCTIONS
C RUN 

A REQUIREMENTS

Velvet should function on any standard 64bit Linux environment with
Visual Studio 2012. A good amount of physical memory (12GB to start with, more is no luxury)
is recommended. 
	
B COMPILING INSTRUCTIONS

Open velvet.sln with Visual Studio 2012. velvet solution contains four projects named oases, velvetg, velveth, velvet_lib.
oases uses velvet_lib as a static linking library. velvetg and velveth is two executable programs of velvet. Make sure the four
projects are configured with x64 platform before building the solution.

C RUN 

After build the solution, there will be a directory named "bin" in the root directory. Please copy /velvet/velvetg/src/windows_port/lib/zlibwapi.dll
to directory "bin".
