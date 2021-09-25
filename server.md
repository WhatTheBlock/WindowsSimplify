# Windows Server

![1.png](/preview/s2022_20348.230_210925.png)

#### 發布時間：2021/09/25

簡介：移除WinSxS，不可更新，為目前最省資源的版本

版本：Windows Server 2022 Datacenter

組建：20348.230

大小：2.04GB

下載：[Google雲端](https://drive.google.com/uc?export=download&id=1IUZmVer-Th7BtH8O6bc6TCkVkucv46pG)

SHA-256：2FF068955BCA9732198FDDEADD72D2EF8661E183BD06EDEB33D32FAA4522FBA4

----

![1.png](/preview/s2022_20348.112_210727.png)

#### 發布時間：2021/07/27

簡介：定位如同穩定版，但沒做過多的測試，不保證能正常更新

版本：Windows Server 2022 Datacenter

組建：20348.112

大小：2.28GB

下載：[Google雲端](https://drive.google.com/uc?export=download&id=1K2rz4cXOFE2dPvwIeaeXCuHZByN3nMQQ)

SHA-256：2B1E8DA5AB8372081C770B7832133E04D1AC0E154965712F77C1C5697F70DE3D

----

#### 發布時間：2021/04/30

簡介：修復Ser2022_DC_(20344.1)_20210430-2的已知問題

版本：Windows Server 2022 Datacenter

組建：20344.1

大小：1.54GB

下載：[Google雲端](http://tiny.cc/s2022dc_20210430_3)、[OneDrive](http://tiny.cc/s2022dc_20210430_3_o)

SHA-256：D9D73F953321B742AE70B3BCD5178CE11AFE610FBB6AF9DA35BF69578209B272

----

![preview.png](/preview/Ser2022_DC_(20344.1)_20210430-2.png)

#### 發布時間：2021/04/30

簡介：在Ser2022_DC_(20344.1)_20210430的基礎下再精簡，不保證其穩定性

版本：Windows Server 2022 Datacenter

組建：20344.1

大小：1.55GB

下載：[Google雲端](http://tiny.cc/s2022dc_20210430_2)、[OneDrive](http://tiny.cc/s2022dc_20210430_2_o)

SHA-256：58DB7D0AFA51413722A5ABB6ED9E50385D2CDD049449C481638359D99806AB81

修改項目：
- 包含 Ser2022_DC_(20344.1)_20210430 的修改項目
- 整合.NET 3.5
- 移除 WinSxS
- 移除 WinRE
- 移除中文以外的輸入法
- 移除磁碟配額
- 移除 Windows Update
- 移除 Windows輕鬆存取的相關組件
- 移除平板電腦模式
- 移除 PlayReady
- 移除撥接數據機驅動
- 移除蜂窩移動網路支援
- 移除文字辨識工具 (OCR)
- 移除語音辨識
- 移除螢幕小鍵盤 (On-Screen Keyboard)
- 移除步驟收錄程式
- 移除 Time Travel Debugging
- 移除 Wordpad
- 移除臉部辨識、指紋、PIN、照片解鎖
- 移除鎖定畫面預設圖片
- 破壞Defender的啟動程式與病毒庫 (避免完全移除導致安裝出錯)
- 修改工具列透明度
- 加入多項效能優化設定

已知問題：
- Defender移除不完全

----

![preview.png](/preview/Ser2022_DC_(20344.1)_20210430.png)

#### 發布時間：2021/04/30

簡介：這當然不是拿來商用，但為了證明其穩定性，會列出所有移除的組件，理論上這個系統將會是此專案最穩定的系統之一，推薦給喜歡LTSB / LTSC的使用者們

版本：Windows Server 2022 Datacenter

組建：20344.1

大小：2.74GB

下載：[Google雲端](http://tiny.cc/s2022dc_20210430)、[OneDrive](http://tiny.cc/s2022dc_20210430_o)

SHA-256：C544C2A2938109560AF3F089681BC579B3B9290FFCB1740507A243566EDA2FC2

修改項目：
- 移除 Edge Chromium
- 移除 MediaPlayer
- 移除 Miracast
- 移除 WinSAT
- 移除 .NET Cache
- 移除 WinSxS Backup
- 加入非破壞性預設定以符合個人用戶使用
