Sysmon Process Monitoring Lab

Objective

Monitor Windows process creation and termination events using Sysmon.

Tools Used

Sysmon
Event Viewer
Windows PowerShell

Activities Performed

1. Installed and configured Sysmon.
2. Generated process creation events.
3. Generated process termination events.
4. Investigated Event ID 1 and Event ID 5.
5. Analyzed process details including:

    Process Name
    Process ID
    Parent Process
    Command Line
    User Context

 Processes Tested

 notepad.exe
 cmd.exe
 ipconfig.exe

 Findings

Sysmon successfully logged process creation and termination events. The collected logs provide valuable visibility for SOC analysts during threat hunting and incident investigations.

 Author

Mohammed Almalki (uk66u)
