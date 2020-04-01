---
title: Terminal
layout: repos
permalink: /terminal/
repository_weight: 1
---

# Windows_Microsoft_Terminal

---

Second to the [VSCODE](https://code.visualstudio.com/) text editor. The next developer tool is a good command line interface and although VScode has a built-in terminal I prefer to use [Windows Microsoft Terminal](https://github.com/microsoft/terminal) for its customizable user interface, multiple tabs and its intergration with Windows Subsystem for Linux. This will ultimately allow us to leave one tab open running a service like the PHP development server, Gulp or Jekyll and seeing complilation errors for Sass or Jekyll as we save our code while also running other arguments like git, npm, composer, etc in another tab. The following is a quick how-to on getting up and running with Windows Microsoft Terminal by downloading its GitHub release, installing and launching it all from Powershell.

---

### 1. Open Windows Powershell from powerusers menu.

Press <kbd>WIN</kbd>+<kbd>X</kbd> then <kbd>A</kbd> to open Windows Powershell (Admin) from powerusers menu.

Press <kbd>ALT</kbd>+<kbd>Y</kbd> to select <kbd>Yes</kbd> at the UAC prompt.

---

### 2. Download Microsoft Terminal package from GitHub.

Copy the following with <kbd>CTRL</kbd>+<kbd>C</kbd>

```
Invoke-WebRequest -Uri https://github.com/microsoft/terminal/releases/download/v0.9.433.0/Microsoft.WindowsTerminal_0.9.433.0_8wekyb3d8bbwe.msixbundle -OutFile terminal.msixbundle -UseBasicParsing
```

and paste into Powershell with <kbd>Right Mouse Click</kbd> and press <kbd>Enter</kbd>

---

### 3. Add Microsoft Terminal package.

Copy the following with <kbd>CTRL</kbd>+<kbd>C</kbd>

```
Add-AppxPackage .\terminal.msixbundle
```

and paste into Powershell with <kbd>Right Mouse Click</kbd> and press <kbd>Enter</kbd>

---

### 4. Open Microsoft Terminal with

#### Windows Powershell command.

Type:

`wt` 

and press <kbd>Enter</kbd>

---

#### Or the Windows Run Command.

Press <kbd>Win</kbd>+<kbd>R</kbd>

Type:

`wt` 

and press <kbd>Enter</kbd>
