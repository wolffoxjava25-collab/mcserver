# Source code
- https://github.com/lordofwizard/mcserver
## 更動
- 修改 install 內的java 17 至 java 26
## 教學指令參考
- https://www.youtube.com/watch?v=f2nvfJuI5GU&t
## 使用差別
### 系統安裝
原本：<del>Debian GNU/Linux, 11 or 12</del> <br>
現在：Ubuntu, 20.04 LTS
### java安裝指令
原本：<del>5. 輸入apt-get install openjdk-17-jre-headless</del> <br>
現在：5. 輸入apt-get install openjdk-26-jre-headless <br>
原本：<del>10.輸入git clone https://github.com/lordofwizard/mcserver</del> <br>
現在：10. 輸入git clone https://github.com/tony0406/mcserver
### 創立伺服器
原本：<del>選擇 [3]Create Forge Server</del> <br>
現在：選擇 [1]Create Vanilla Server

## 模組伺服器
目前只能使用無模組的Vanilla Server，如需Forge Server，要再修正 ForgeInstall 與 startJavaServer 檔
