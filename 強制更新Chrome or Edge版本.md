## 將 MSI 儲存到桌面<br>
## 使用 以系統管理員身分執行 開啟 Windows 命令提示字元<br>
---
### 輸入下列命令，其中： C：\Users\username\Desktop 是 MSI 路徑，而 ``` FileName<b> ``` 是 ``` .msi ``` 檔的名稱：<br>
#### 進入該msi檔路徑 ： ``` cd C:\Users\username\Desktop ```
#### 再執行 ``` Cmsiexec /I FileName.msi /qn ALLOWDOWNGRADE=1 ```
### 關閉並重新開啟Chrome or Edge，並確認是否正常運作及版本
