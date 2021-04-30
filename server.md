# Server

![preview.png](/preview/Ser2022_DC_(20344.1)_20210430-2.png)

#### 發布時間：2021/04/30

簡介：在Ser2022_DC_(20344.1)_20210430的基礎下再精簡，不保證其穩定性

版本：Windows Server 2022 Datacenter

組建：20344.1 (21H2)

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

----

![preview.png](/preview/Ser2022_DC_(20344.1)_20210430.png)

#### 發布時間：2021/04/30

簡介：這當然不是拿來商用，但為了證明其穩定性，會列出所有移除的組件，理論上這個系統將會是此專案最穩定的系統之一，推薦給喜歡LTSB / LTSC的使用者們

版本：Windows Server 2022 Datacenter

組建：20344.1 (21H2)

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
