# UNC Path Converter

A small PowerShell WinForms utility that converts mapped drive paths (e.g. Z:\Folder) into their underlying UNC paths (e.g. \\Server\Share\Folder).

## Features

- Accepts paths pasted from Explorer's Copy as path (quotes handled automatically)
- Converts mapped network drives to UNC using Win32_LogicalDisk
- Copies the result to clipboard automatically
- Open UNC location directly in Explorer

## Run

powershell.exe -ExecutionPolicy Bypass -File .\UNCPathConverter.ps1

## Compile to EXE

Install-Module PS2EXE -Scope CurrentUser
Invoke-PS2EXE -InputFile .\UNCPathConverter.ps1 -OutputFile .\UNCPathConverter.exe -NoConsole

## Author

Jay 
