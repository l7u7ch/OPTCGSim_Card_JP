本リポジトリは、OPTCGSim で使用されている英語のカードデータを日本語のカードデータに置き換えたモノです。

PowerShell in Windows 11

```ps
PS> Get-Location
C:\Users\[USER_NAME]\OPTCGSim\OPTCGSim_Data\StreamingAssets
PS> Remove-Item -Recurse -Force Cards
PS> git clone https://github.com/l7u7ch/OPTCGSim_Card_JP.git Cards

```

Bash in Ubuntu 24.04

```bash
$ pwd
~/OPTCGSim/OPTCGSim_Data/StreamingAssets
$ rm -R Cards
$ git clone https://github.com/l7u7ch/OPTCGSim_Card_JP.git Cards
```
