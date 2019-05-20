# automatedinstall

## Windows
1. [Install choco](https://chocolatey.org/install#installing-chocolatey) from cmd as administrator
```
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```

2. Restart cmd and install packages :-)

```
choco install -y slack visualstudiocode pandoc mkdocs miktex vlc googlechrome dropbox git openvpn python qbittorrent virtualbox make openvpn paint.net teamviewer wget winrar dotnetcore-sdk
```

3. Restart cmd and run
```
pip install mkdocs-material resharper-platform
```
