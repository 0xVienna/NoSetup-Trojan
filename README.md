# !!! README !!!
BY RUNNING THIS EXECUTABLE/VIRUS, I WILL NOT BE RESPONSIBLE FOR ANY DAMAGES.
Have fun!

# NoSetup-Trojan
A C# trojan that overwrites and restricts the system using dedicated code and disguises itself as an installer.

# How it works
- It checks for running processes, such as Explorer.EXE and terminates them.
- The trojan preparer installs the overwriter for the Master Boot Record, then the trojan setup puts restrictions on registry.

# Changelogs
- V1.2.2
Fix bugs and working to destroy machine.

Known issues:
- Broken registry hooking on some code
- Setup causes huge lag to system (good)
