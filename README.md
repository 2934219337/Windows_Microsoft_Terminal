---
title: Terminal
layout: page
permalink: /terminal/
repository_weight: 1
---

# Windows_Microsoft_Terminal

### Open powershell from powerusers menu.

Press `WIN+X` then `A` to open Windows Powershell (Admin) from powerusers menu.

Press `ALT+Y` to select Yes at the UAC prompt.

### Download Terminal from GitHub.

Copy with `CTRL-C` and paste with `CTRL-V` the following:

```
Invoke-WebRequest -Uri https://github.com/microsoft/terminal/releases/download/v0.9.433.0/Microsoft.WindowsTerminal_0.9.433.0_8wekyb3d8bbwe.msixbundle -OutFile terminal.msixbundle -UseBasicParsing
```

and press `Enter`

### Add Terminal package.

Copy with `CTRL-C` and paste with `CTRL-V` the following:

```
Add-AppxPackage .\terminal.msixbundle
```

and press `Enter`

### Open Terminal with command.

Copy with `CTRL-C` and paste with `CTRL-V` the following:

```
wt
```

and press `Enter`
