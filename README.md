# Simple-PE-Injection_Text-Section
Classic C++ Code PE Injection - Storing payload into Text section

Adversaries may inject portable executables (PE) in order to  get remote access to the target system. Classic PE injection is a method of executing arbitrary code in remote target system.

This can be performed with native Windows API calls such as **VirtualAlloc**, **VirtualProtect**, **CreateThread**.
