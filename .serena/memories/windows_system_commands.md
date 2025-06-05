# Windows-Specific System Commands for SymPy Development

## File and Directory Operations
- `dir` - List directory contents (equivalent to `ls`)
- `type filename` - Display file contents (equivalent to `cat`)
- `copy source dest` - Copy files (equivalent to `cp`)
- `del filename` - Delete files (equivalent to `rm`)
- `rmdir /s dirname` - Remove directory recursively (equivalent to `rm -rf`)
- `mkdir dirname` - Create directory
- `cd dirname` - Change directory
- `cd ..` - Go up one directory
- `cd \` - Go to root directory

## Text Processing
- `findstr pattern filename` - Search for patterns in files (equivalent to `grep`)
- `findstr /s /i pattern *` - Recursive case-insensitive search
- `fc file1 file2` - Compare files (equivalent to `diff`)

## System Information
- `echo %PATH%` - Display PATH environment variable
- `where python` - Find Python executable location (equivalent to `which`)
- `python --version` - Check Python version

## Process Management
- `tasklist` - List running processes (equivalent to `ps`)
- `taskkill /f /pid <pid>` - Kill process by PID

## Network
- `ping hostname` - Test network connectivity
- `ipconfig` - Display network configuration

## Git Commands (same on Windows)
- All git commands work the same way on Windows
- Use Git Bash for Unix-like command experience if preferred

## PowerShell Alternatives
If using PowerShell instead of Command Prompt:
- `Get-ChildItem` or `ls` - List directory contents
- `Get-Content filename` or `cat filename` - Display file contents
- `Copy-Item` or `cp` - Copy files
- `Remove-Item` or `rm` - Delete files
