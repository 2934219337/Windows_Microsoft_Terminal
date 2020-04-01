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

Copy and paste the following:

```
Invoke-WebRequest -Uri https://github.com/microsoft/terminal/releases/download/v0.9.433.0/Microsoft.WindowsTerminal_0.9.433.0_8wekyb3d8bbwe.msixbundle -OutFile terminal.msixbundle -UseBasicParsing
```

Press `Enter`

### Add Terminal package.

Copy and paste the following:

```
Add-AppxPackage .\terminal.msixbundle
```

Press `Enter`

### Open Terminal with command.

Copy and paste the following:

```
wt
```

Press `Enter`
