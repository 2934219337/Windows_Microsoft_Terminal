# Windows_Microsoft_Terminal

Download Terminal

```
Invoke-WebRequest -Uri https://github.com/microsoft/terminal/releases/download/v0.9.433.0/Microsoft.WindowsTerminal_0.9.433.0_8wekyb3d8bbwe.msixbundle -OutFile terminal.msixbundle -UseBasicParsing
```

Add Terminal

`Add-AppxPackage .\terminal.msixbundle`

Open Terminal

`wt`
