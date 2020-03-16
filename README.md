# Windows_Microsoft_Terminal

Download Library

```
Invoke-WebRequest -Uri http://tlu.dl.delivery.mp.microsoft.com/filestreamingservice/files/628f920b-6ee5-4f64-9988-8e840bc0aa5d?P1=1584319211"&"P2=402"&"P3=2"&"P4=H3%2bzDugPG56JqsIkzZROmb5iOyPrprYibtI%2fKhBz%2f9pesday3GQJ2qOfebCdK5%2fao%2bEIngMxlVdPhb4t2DcJyw%3d%3d -OutFile vclib.appx -UseBasicParsing
```

Add Library

`Add-AppxPackage .\vclib.appx`

Download Terminal

```
Invoke-WebRequest -Uri http://tlu.dl.delivery.mp.microsoft.com/filestreamingservice/files/db008790-6c87-4453-bc1c-2129c4090e00?P1=1584319176"&"P2=402"&"P3=2"&"P4=l0oGwXhu%2biB77%2bj3ie3Zfy%2fMJmuagacqRl%2b0Ic7BA6ewM3s8ugWcoaIOH%2fKHn%2brN6nvvGxtU0s9OaUyEe7q58g%3d%3d -OutFile terminal.appx -UseBasicParsing
```

Add Terminal

`Add-AppxPackage .\terminal.appx`
