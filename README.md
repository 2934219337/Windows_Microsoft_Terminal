---
title: Terminal
layout: page
permalink: /terminal/
repository_weight: 1
---

# Windows_Microsoft_Terminal

## Open powershell from powerusers menu.

Press `WIN+X` to open powerusers menu.

Press `A` or click `Windows Powershell (Admin)`.

Select `YES` at prompt.

## Download Terminal from GitHub.

```
Invoke-WebRequest -Uri https://github.com/microsoft/terminal/releases/download/v0.9.433.0/Microsoft.WindowsTerminal_0.9.433.0_8wekyb3d8bbwe.msixbundle -OutFile terminal.msixbundle -UseBasicParsing
```

### Add Terminal

```
Add-AppxPackage .\terminal.msixbundle
```

### Open Terminal

```
wt
```
