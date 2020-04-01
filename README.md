---
title: Terminal
layout: page
permalink: /terminal/
repository_weight: 1
---

# Windows_Microsoft_Terminal

### Open powershell from powerusers menu.

Press <kbd>WIN</kbd>+<kbd>X</kbd> then <kbd>A</kbd> to open Windows Powershell (Admin) from powerusers menu.

Press <kbd>ALT</kbd>+<kbd>Y</kbd> to select <kbd><samp>Yes</samp></kbd> at the UAC prompt.

### Download Terminal from GitHub.

Copy with <kbd>CTRL</kbd>+<kbd>C</kbd> and paste with <kbd>CTRL</kbd>+<kbd>V</kbd> the following:

```
Invoke-WebRequest -Uri https://github.com/microsoft/terminal/releases/download/v0.9.433.0/Microsoft.WindowsTerminal_0.9.433.0_8wekyb3d8bbwe.msixbundle -OutFile terminal.msixbundle -UseBasicParsing
```

and press <kbd><samp>Enter</samp></kbd>

### Add Terminal package.

Copy with <kbd>CTRL</kbd>+<kbd>C</kbd> and paste with <kbd>CTRL</kbd>+<kbd>V</kbd> the following:

```
Add-AppxPackage .\terminal.msixbundle
```

and press <kbd><samp>Enter</samp></kbd>

### Open Terminal with command.

Type `wt` and press <kbd><samp>Enter</samp></kbd>
