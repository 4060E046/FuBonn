## 1.將 .MSI 儲存到桌面<br>
## 2.以系統管理員身分執行CMD<br>
### 3.輸入下列命令，其中： C：\Users\username\Desktop\test 是您下載的 MSI 路徑，而 FileName 是 .msi 檔的名稱：<br>
 C:\Users\username\Desktop> ```msiexec /I FileName.msi /qn ALLOWDOWNGRADE=1```<br>
## 4.關閉並重新開啟Edge或Ｃhrome，以確認復原正常運作
