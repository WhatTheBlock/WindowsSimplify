# Windows 11

![1.png](/preview/22000.469_220131.png)

#### 發布時間：2022/01/31

**簡介：** 高度精簡版本，適合遊戲、虛擬機等用途

**版本：** Windows 11 Pro

**組建：** 22000.469

**大小：** 1.74GB

**下載：** [Link](https://github.com/WhatTheBlock/WindowsSimplify/releases/download/w11.220131/22000.469_220131.iso)

**SHA-256：** 35107a12d755fe7fc63df515e66ef4e4e36be180993daeeab8096977cf67b4db

**注意事項：**
- 無法安裝CU更新
- ISO內含IE啟動腳本，無需Edge也可啟動

----

#### 發布時間：2022/01/23

**簡介：** 保留了部分行動裝置常用的UWP APP，無測試過，不建議新手使用

**版本：** Windows 11 Pro (ARM64)

**組建：** 22000.466

**大小：** 3.32GB

**下載：** [Part 1](https://github.com/WhatTheBlock/WindowsSimplify/releases/download/w11.220123/22000.466_arm_220123.part1.rar)、[Part 2](https://github.com/WhatTheBlock/WindowsSimplify/releases/download/w11.220123/22000.466_arm_220123.part2.rar)

**SHA-256：** 5b53f37080e4094b99fde2a916c7249bfe07a71324c3bb58012245dd58dc4b91

**注意事項：**
- 無測試過，不建議新手使用
- 不保證可安裝CU更新
- 若boot.wim或autounattend.xml有問題導致無法正常安裝請利用WinPE直接安裝install.esd

----

![1.png](/preview/Win11_22000.282_211027.png)

#### 發布時間：2021/10/27

**簡介：** 預裝修改版WSA，Play商店登錄前置步驟可至該版本[Release](https://github.com/WhatTheBlock/WindowsSimplify/releases/tag/w11.211027)頁面查看

**版本：** Windows 11 Pro

**組建：** 22000.282

**大小：** 3.29GB (Ver.1)、2.74GB (Ver.2)

**下載：** [Ver.1](https://drive.google.com/uc?export=download&id=1ZywVTPHcTZ2Fu320usL6W5nmPSlWwzxp)、[Ver.2](https://drive.google.com/uc?export=download&id=1C02XqCJvmvY4tKcy9UQHrzvixK2IHTDJ)

**SHA-256：**
- Ver.1: 8E7E26C40F7F8FCBF8755B84F271F917E858B6AFBB623BB095439E7559314FB1
- Ver.2: 5FABBFA7FBA139724903912A5C8E4DECAF3A128EAA7905765D47268B5A94806E

**注意事項：**
- 系統安裝完畢後請至C槽根目錄執行`install.cmd`安裝WSA
- 執行WSA之前務必先安裝其他裝置驅動，避免執行效能過差
- `Ver.1`不保證可安裝CU更新，`Ver.2`則無法更新
- 預覽圖為`Ver.2`
- Windows Store需等待系統自動更新為藍色圖標的新版本才可開啟
- WSA有修改，系統地區可設定為美國或台灣
- ADB工具位於`C:\adb_tools`
- 此系統無瀏覽器，請自行執行C槽根目錄下的`Get Latest Chrome.cmd`安裝Chrome

----

#### 發布時間：2021/10/26

簡介：首個預裝WSA的版本，APK安裝步驟可至該版本[Release](https://github.com/WhatTheBlock/WindowsSimplify/releases/tag/w11.211026)頁面查看

版本：Windows 11 Pro

組建：22000.282

大小：3.32GB

下載：[Link](https://drive.google.com/uc?export=download&id=1zDpFhPwH1Uj23w8--8vP1rNgTw1OjX_u)

SHA-256：A3F78939A5ECF2A015DC7BBEEC1B8F741CFB85912BDBDF82B0ADAA693B3AB2A9

已知問題：
- Windows Defender功能異常

注意事項：
- 執行WSA之前請務必先安裝其他裝置驅動，避免執行效能過差
- Windows Store需等待系統自動更新為藍色圖標的新版本才可開啟
- WSA無修改，系統地區不可設定為美國和英國以外之地區
- ADB工具位於`C:\adb_tools`

----

![1.png](/preview/Win11_22000.282_211018.png)

#### 發布時間：2021/10/19

簡介：大致與`Win11_22000.194_211012`相同，但本次將Windows Update頁面也一併破壞，並移除系統自動下載安裝驅動的功能。虛擬機測試過VMware Tools驅動可正常安裝使用，其餘裝置不保證功能正常

版本：Windows 11 Pro

組建：22000.282

大小：1.76GB

下載：[Link](https://drive.google.com/uc?export=download&id=1d7Vy4TqV6KRkeljyCisPIVCBW-A-Xc71)

SHA-256：0933F630F084F32DFC6C265ADEFB0B5CB91B4C089544E50B2D993C8D55245953

注意事項：
- 此系統無瀏覽器，請自行執行C槽根目錄下的`Get Latest Chrome.cmd`安裝Chrome
- 已停用Virtualization-based Security，對安全性有疑慮的人請勿使用

----

![1.png](/preview/Win11_22000.194_211012.png)

#### 發布時間：2021/10/13

簡介：檔案總管已改回傳統介面，工作列置左也能讓不習慣置中的人使用，此版本精簡程度相當高，不建議日常使用

版本：Windows 11 Pro

組建：22000.194

大小：1.63GB

下載：[Link](https://drive.google.com/uc?export=download&id=1BDiRHZ976WhDeq5x1WO3Yds59VN1GZBp)

SHA-256：ED894255E820B21088B9D684D45B3BFBED083F037CFF9F69B21A54907741FB3B

注意事項：
- 此系統無瀏覽器，請自行執行C槽根目錄下的`Get Latest Chrome.cmd`安裝Chrome
- 已停用Virtualization-based Security，對安全性有疑慮的人請勿使用

----

![1.png](/preview/Win11_22000.194_211006.png)

#### 發布時間：2021/10/08

簡介：Win11現階段精簡工具尚未完美支援，即便精簡的比較保守也不能保證其穩定性

版本：Windows 11 Pro

組建：22000.194

大小：3.24GB (Stable)、2.32GB (Extreme)

下載：[Stable](https://drive.google.com/uc?export=download&id=1cdSNVDBTySy_K4AJGcBP0WlnLwPuKX8w)、[Extreme](https://drive.google.com/uc?export=download&id=1zG-c7pf4kkS7X1es3WBfpM2ZrenobRdH)

SHA-256：
- Stable: 8613760589E3103475CF7166FC8A981D5D4B8A491896829E36BB35A7026C2CAD
- Extreme: 5ECA11E0E74F6A975DDDE03ABB1CA01AADF482D43EED640F60606CB85699CBEF

注意事項：
- Extreme額外移除了Edge、Store、Defender、WinSxS等
![2.png](/preview/Win11_22000.194_211006-2.png)
- 會被強制安裝Teams，目前暫時沒找到阻止安裝的方式
- 已停用Virtualization-based Security，對安全性有疑慮的人請勿使用

----

#### 發布時間：2021/09/24

簡介：Insider Preview 僅供嘗鮮

版本：Windows 11 Pro

組建：22463.1000

大小：2.46GB (Stable)、2.17GB (Extreme)

下載：[Stable](https://drive.google.com/uc?export=download&id=1SOV7uRS2Q6bEA_Xvet8pYZ9F5OBkjiSC)、[Extreme](https://drive.google.com/uc?export=download&id=1AxK2omomPMqjRQr1WEZhYtvKxTfWJjZi)

SHA-256：
- Stable: EFBB5009676C2FCAA9DDF27B579134245E4A0ECD74438FED14AFC14BEAB3A37D
- Extreme: 33626BEE8A0F11C2672ED1E1B2EB5426A393D85A95B32BA597E10135F9B53F1B

----

![1.png](/preview/Win11_22000.100_210723.png)

#### 發布時間：2021/07/23

簡介：Insider Preview 僅供嘗鮮

版本：Windows 11 Pro

組建：22000.100

大小：1.79GB

下載：[Extreme](https://github.com/WhatTheBlock/WindowsSimplify/releases/download/v2021.07.18/Win11_22000.100_210723.iso)

SHA-256：26752820BBEBC6067B04D3CF267D9A744AB1BBCBE089D5BB041FFAB719B966B3

注意事項：
- 請參考22000.51

----

![1.png](/preview/Win11_22000.71_210718.png)

![2.png](/preview/Win11_22000.71_210718_2.png)

#### 發布時間：2021/07/18

簡介：Insider Preview 僅供嘗鮮

版本：Windows 11 Pro

組建：22000.71

大小：1.79GB

下載：[Extreme](https://drive.google.com/uc?export=download&id=1g60_Eg1quODm_QWeR9weVoiYxzmLQSTZ)

SHA-256：0AE0E515F9D443D4DADCAD12446D14529F58CED6A063100AEB824F0F8BD7FE00

注意事項：
- 請參考22000.51

----

![1.png](/preview/Win11_22000.51_210629.png)

![2.png](/preview/Win11_22000.51_210629_2.png)

#### 發布時間：2021/06/29

簡介：Insider Preview 僅供嘗鮮

版本：Windows 11 Pro

組建：22000.51

大小：2.24GB (Stable)、1.81GB (Extreme)

下載：[Stable](https://drive.google.com/uc?export=download&id=11SpW-VC2-cyq3xLkAqzX04TCz9aw8qnu)、[Extreme](https://drive.google.com/uc?export=download&id=1Q-FS6PdWh-E3iHDu7WC2Xn_sXBkdSh1a)

SHA-256：
- Stable: EFBB5009676C2FCAA9DDF27B579134245E4A0ECD74438FED14AFC14BEAB3A37D
- Extreme: 33626BEE8A0F11C2672ED1E1B2EB5426A393D85A95B32BA597E10135F9B53F1B

注意事項：
- 此系統不含瀏覽器 (Win11的IE需依賴Edge，所以無法使用)，請自備安裝檔或使用商店下載瀏覽器再下載瀏覽器，例如這款
![1.png](/tutorial/web_browser.png)

- 此為Insider Preview，可能有相當多的Bug，僅供嘗鮮

- Extreme移除了WinSxS，無法安裝系統更新
