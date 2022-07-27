# Bot RPG Ultime
![Python version](https://img.shields.io/badge/python-v3.9.9-blue?style=for-the-badge&logo=appveyor) ![Coverage](https://img.shields.io/badge/coverage-0%25-red?style=for-the-badge&logo=appveyor)
A Discord rpg bot in production.

## Requirements

We are using python virtual environments ([venv]) to simply the development of the project. So theoretically you only need Python.

- [Python] - 3.9.9 if possible ([here](https://www.python.org/ftp/python/3.9.9/))

## How to use Venv
#### Linux
```bash
source .venv/bin/activate
```
#### Windows
If there are UnauthorizedAccess issue, please do the next command
```bash
Set-ExecutionPolicy Unrestricted -Scope Process
```
##### _Cmd.exe_
```bash
.\.venv\bin\Activate.bat
```
##### _Powershell_
```bash
.\.venv\bin\Activate.ps1
```

[Python]: <https://www.python.org/>
[venv]: <https://docs.python.org/3/library/venv.html>
