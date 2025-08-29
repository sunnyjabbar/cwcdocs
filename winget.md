Windows Package Manager
- [Winget]((https://learn.microsoft.com/en-us/windows/package-manager/winget/))
To search for a tool, type 
```powershell
winget search <appname>
```

After you have confirmed that the tool you want is available, you can [install](https://learn.microsoft.com/en-us/windows/package-manager/winget/install) the tool by typing 

```powershell
winget install <appname>
```

 The **WinGet** tool will launch the installer and install the application on your PC.

For example to install python do the following
```powershell
winget search python
winget install Python.Python.3.12
```
To install all applications from a script do the following
```powershell
winget install Python.Python.3.12
winget install Notepad++.Notepad++
winget install Anaconda.Anaconda3
winget install Microsoft.VisualStudioCode
winget install Git.Git
winget install Obsidian.Obsidian
```
