# VCRedistMSI
An MSI package that installs the Visual C++ CRT redistributable.

This is a Visual Studio 2015 solution with a Wix Toolset setup project that builds an MSI package that references the Visual C++ CRT merge modules. The MSI built installs the CRT variant matching the solution configuration, i.e., a Debug x64 MSI installs the x64 Debug CRT, etc. 
