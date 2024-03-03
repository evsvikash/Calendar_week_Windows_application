# Calendar_week_Windows_application
Calendar_week_Windows_application for taskbar


Created by Vikash Sharma

https://github.com/evsvikash

Run application directly by double click and it will show on the taskbar!

To add the application to run on startup in Windows, you can add an entry to the Windows Registry. Here's how you can do it:

First, you need to create a registry entry for your application. You can do this by adding a new registry key to the "Run" subkey in the registry.

Open the Registry Editor by pressing Win + R, typing regedit, and pressing Enter.

Navigate to the following key:

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run
Right-click on the right pane, select "New" -> "String Value".
Name the new string value whatever you like (e.g., "WeekWidget").
Double-click on the new string value and set its value data to the path of your executable file (including the file extension). For example:
C:\path\to\your\executable.exe
Save changes and exit!!!

Enjoy
