# !!! README !!!
BY RUNNING THIS EXECUTABLE/VIRUS, I WILL NOT BE RESPONSIBLE FOR ANY DAMAGES.
Have fun!



# NoSetup-Trojan
A C# trojan that overwrites and restricts the system using dedicated code and disguises itself as an installer. In this case, Windows 8.1 Installer.

# How it works
- It checks for running processes, such as Explorer.EXE, taskmgr.exe, notepad.exe and terminates them.
- The trojan preparer installs the overwriter for the Master Boot Record, then the trojan setup puts restrictions on registry and runs a lot of scripts to further lock down the victim's computer.

# Changelogs
Current Version: v1.1.2

Known issues:
- Broken registry hooking on some code
- Setup causes huge lag to system (good)
