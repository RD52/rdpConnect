微軟遠端連線自訂解析度與自動複製密碼到剪貼簿
===

自動連上並複製密碼到剪貼簿
```
irm bit.ly/36tr1aS|iex; rdpConnect '192.168.3.12' '123456'
```

bat
```
pwsh -Command "&{irm bit.ly/36tr1aS|iex; rdpConnect '192.168.3.12' '123456'}"
```

pwsh
```
C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe -command "irm bit.ly/36tr1aS|iex; rdpConnect '192.168.3.12' '123456'"
```



### 安裝到電腦上
```
irm bit.ly/36tr1aS|iex; Install
```

### 離線使用
```ps1
irm bit.ly/36tr1aS|iex; Download '192.168.3.12' ''
```
