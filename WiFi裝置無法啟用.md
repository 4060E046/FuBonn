
# WiFi裝置無法啟用
### Intel無線網卡的RSC 功能可能會導致WiFi使用異常，所以可以嘗試禁用<br>
windows powershell（系統管理員），打開後在命令列輸入以下命令：```Get-NetAdapterRsc```<br>
先查看有開啟RSC功能的網卡名字，然後再對應的輸入禁用網路RSC的命令：<br>
`Disable-NetAdapterRsc空格-name空格WLAN`<br>
或者是<br>
`Disable-NetAdapterRsc空格-name空格 Wi-Fi`<br>
