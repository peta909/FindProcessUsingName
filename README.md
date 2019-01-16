# FindProcessUsingName

Modified the code from https://docs.microsoft.com/en-us/windows/desktop/ToolHelp/taking-a-snapshot-and-viewing-processes

Replaced the use of TCHAR to const wchar_t* (so it can be compiled w/o errors in vs2017/

commented out some codes from original source for ease of debugging.

Added code to find PID of a process via its string name.

currently hardcoded to "smss.exe"

# FYI
The code was written and compiled using VS2017 Professional. Drop me a qns/comment at peta909@hotmail.com :)
