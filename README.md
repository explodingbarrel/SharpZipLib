SharpZipLib
===========

\#ziplib is a Zip, GZip, Tar and BZip2 library written entirely in C# for the .NET platform.

Please see the [\#ziplib homepage](http://icsharpcode.github.io/SharpZipLib/) for precompiled downloads,
license information, link to the forum (support), release history, samples and more.

**** Kabam Note

- might need to use mono-develop4 to compile; mono-develop5 seems to insert .net40
target version meta data into the DLL (even project is set to be .net20 compatible),
which unity does not like

- open ICSharpCode.SharpZLib2005.sln and build for "Release" config
- then copy the output dll "./bin/ICSharpCode.SharpZipLib.dll" to unity's "Assets/Plugins/ICSharpCode.SharpZipLib.dll"