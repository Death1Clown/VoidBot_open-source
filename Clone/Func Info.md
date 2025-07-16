    Clone.bat

git clone https://github.com/Death1Clown/VoidBot_open-source.git
pause




    Version & Installation.bat

@echo off
echo Checking Git version...

git --version >nul 2>&1

IF %ERRORLEVEL% EQU 0 (
    git --version
    echo Git is installed and working correctly.
) ELSE (
    echo Git is not installed or not added to your PATH.
    echo Please install Git from https://git-scm.com/downloads
)

pause
