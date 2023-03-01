# Windows-Batch-Get-last-logged-in-user-on-another-machine
 
REG QUERY \\TARGETMACHINE\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Authentication\LogonUI\ /v LastLoggedOnUser
