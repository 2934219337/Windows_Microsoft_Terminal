---
title: Terminal
layout: page
permalink: /terminal/
repository_weight: 1
---

# Windows_Microsoft_Terminal

### Open Windows Powershell from powerusers menu.

Press <kbd>WIN</kbd>+<kbd>X</kbd> then <kbd>A</kbd> to open Windows Powershell (Admin) from powerusers menu.

Press <kbd>ALT</kbd>+<kbd>Y</kbd> to select <kbd><samp>Yes</samp></kbd> at the UAC prompt.

### Download Microsoft Terminal package from GitHub.

Copy the following with <kbd>CTRL</kbd>+<kbd>C</kbd>

```
Invoke-WebRequest -Uri https://github.com/microsoft/terminal/releases/download/v0.9.433.0/Microsoft.WindowsTerminal_0.9.433.0_8wekyb3d8bbwe.msixbundle -OutFile terminal.msixbundle -UseBasicParsing
```

and paste into Powershell with <kbd>CTRL</kbd>+<kbd>V</kbd> and press <kbd><samp>Enter</samp></kbd>

### Add Microsoft Terminal package.

Copy the following with <kbd>CTRL</kbd>+<kbd>C</kbd>

```
Add-AppxPackage .\terminal.msixbundle
```

and paste into Powershell with <kbd>CTRL</kbd>+<kbd>V</kbd> and press <kbd><samp>Enter</samp></kbd>

### Open Microsoft Terminal with Windows Powershell command.

Type:

`wt` 

and press <kbd><samp>Enter</samp></kbd>

### Open Microsoft Terminal with Run command.

Press <kbd>Win</kbd>+<kbd>R</kbd>

Type:

`wt` 

and press <kbd><samp>Enter</samp></kbd>
