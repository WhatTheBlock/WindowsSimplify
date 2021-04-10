# 穩定精簡版

#### 沒有過度精簡的版本，適合一般用戶使用
#### 歡迎至issues或小屋文章回報問題：)

----

### 使用預覽：

- Windows 10 Pro v20H2 (x64)
![Win10_20H2_(19042.867)_20210410.png](/preview/Win10_20H2_(19042.867)_20210410.png)

----

#### 版本：Windows 10 Pro v20H2 (x64)
#### 發布時間：2021/04/10
#### 組建：19042.867
#### 大小：2.14GB
#### SHA-256：FBDD57E84A82FDDA3BB61DFEA09A8412C6D060EA13196B9E7E6997ACFCF78360
#### 下載：[Google雲端](http://tiny.cc/w10_20H2_20210410)、[OneDrive](http://tiny.cc/w10_20H2_20210410_o)

#### 注意事項：
- 更新後會自動裝回部分組件與Edge Chromium
- 更新後會出現Windows安全性，但並無掃毒功能，Defender仍是移除的狀態
- Windows Update服務預設為停用狀態，使用前請先手動啟用
- Windows功能啟用.NET 3.5前請先啟用Windows Update服務

#### 已知問題：
- Windows Update功能異常，無法搜尋到最新的更新，但能透過DISM使用CAB、MSU等檔案更新

----

### Changelog：
#### 2021/04/10 (v20H2)
- 系統更新至19042.867
- 移除.NET Framework 3.5
- 移除Windows Defender
- 移除VC++ Runtime
- 移除DirectX 9.0c
- 移除Windows Store
- Windows Update改為不檢查更新
- 使用精簡美化版boot.wim
- 回復"終極效能"電源選項
- 使用傳統小算盤

#### 2021/02/23 (v20H2)
- 系統更新至19042.844
- 集成.NET Framework 3.5
- 移除Edge Chromium
- Windows Update改為檢查更新但不下載
- 修改系統介面為深色
- 還原預設桌布
- 還原相片檢視器介面
- 開啟GPU調度功能
- 還原音樂與影片的圖片預覽功能
- 還原Windows Defender組件 (已禁用)
- 還原SMB共享功能
- 還原遠端協助功能
- 移除"終極效能"電源選項
- 還原Windows Store
- 關閉虛擬記憶體
- 禁用睡眠功能
- 修復先前版本所有已知問題

#### 2020/08/04 (v2004)
- 版本改為專業版
- 系統更新至19041.423
- 更新Edge Chromium (v84.0.522.52)
- 修復缺少STI.DLL的問題
- 集成VC++ Runtime (2005~2019)
- 集成DirectX 9.0c
- 修改預設桌布
- 修改系統介面為淺色
- 禁用Windows Update
- 右鍵選單加入"在此目錄開啟CMD"選項 (系統管理員)
- 精簡右鍵選單"新增"內的選項
- 允許PowerShell執行本地腳本檔(*.ps1)
- 修改相片檢視器介面
- 新增"終極效能"電源選項
- 關閉GPU調度功能

#### 2020/08/03 (v20H2)
- 系統更新至19042.421
- 移除.NET Framework 3.5 (需要的人請自行安裝)
- 更新Edge Chromium (v84.0.522.50)
- 修復explorer.exe異常重啟
- 修復安裝時無法自動跳過版本選擇畫面
- 修復缺少STI.DLL的問題
- 集成VC++ Runtime (2005~2019)
- 集成DirectX 9.0c
- 修改預設桌布
- 修改系統介面為淺色
- 禁用Windows Update
- 右鍵選單加入"在此目錄開啟CMD"選項 (系統管理員)
- 精簡右鍵選單"新增"內的選項
- 允許PowerShell執行本地腳本檔(*.ps1)
- 修改相片檢視器介面

#### 2020/07/01
- 大幅簡化檔案總管介面
- 移除捷徑的箭頭圖標
- 移除新建捷徑自動加入的字串
- 關閉音樂與影片的圖片預覽
- 精簡右鍵選單的項目
- 記事本預設開啟狀態列
- 提升開始選單開啟速度
- 關閉系統生成日誌檔
- 更新Edge Chromium (v83.0.478.56)
- 回復VP9解碼、小畫家、Media Player
- 移除ISO手動安裝功能 (setup.exe)
- 工作列更加透明
- 多項細節調整

#### 2020/06/14
- 移除OneDrive
- 更新Edge為Edge Chromium (v83.0.478.45)
- 回復UWP版小算盤
- 移除WSL (Windows Subsystem for Linux)
- 多項細節調整
