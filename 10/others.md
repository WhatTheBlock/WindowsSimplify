# 其他

#### 發布時間：2021/11/18

**簡介：** LTSC 2021記憶體佔用相當高，不太推薦在效能極差的裝置使用，但系統較新，也可自行安裝appx運行最新的UWP App

**版本：** Enterprise LTSC 2021 (x86)

**組建：** 19044.1288

**大小：** 1.33GB (Ver.1)、1.28GB (Ver.2)

**下載：** [Ver.1](https://github.com/WhatTheBlock/WindowsSimplify/releases/download/ltsc.x86.211118/LTSC_19044.1288_x86_211118.iso)、[Ver.2](https://github.com/WhatTheBlock/WindowsSimplify/releases/download/ltsc.x86.211118/LTSC_19044.1288_x86_211118v2.iso)

**SHA-256：**
- Ver.1: 691082469EC54BE8A9011EBF19C3BD8C433EA5170E4878125BB8C3F6529B3BF3
- Ver.2: 69C208B83C319222546EAAE12E73B16F7B3FE664A21ACA09EBA2E1EEDB9365FE

**注意事項：**
- 無法安裝CU更新
- Ver.2有精簡.NET框架，相容性會受到影響，但測試過可使用Office LTSC 2021

----

![img](/preview/Win10_20H2_(19042.867)_20210428.png)

#### 發布時間：2021/05/02

簡介：內含VirtIO驅動，專為KVM虛擬機設計，Windows Update功能正常，測試過可正常更新至19042.928

版本：Windows 10 Pro (x64)

組建：19042.867

大小：2.37GB

下載：[Google雲端_TW](http://tiny.cc/w10_20H2_20210428_t)、[Google雲端_HK](http://tiny.cc/w10_20H2_20210428_h)

SHA-256：
- [TW] 1558C7DE874F4F8D45E46FFB9479A37D70D0EDEFE603BCD571AF5C94F90A9A04
- [HK] 878F33B25420DD5EDF86CEDC6DB455BEBCD659961F63A2FB7F2FF8F854F4101C

安裝時若因為沒有SCSI驅動而找不到硬碟的話請依照Release頁面的步驟操作

[點我查看](https://github.com/WhatTheBlock/Win10_Simplify/releases/tag/v2021.04.28_2)

----

![img](/preview/Win10_21H1_(19043.962)_20210422.png)

#### 發布時間：2021/04/22

簡介：微幅精簡並加入額外的程式增加相容性、功能性 (例：NET 3.5、NET 5.0、Windows Terminal、PowerShell 7)，確保可使用於任何文書、程式開發等辦公使用環境，此版有沒有刻意破壞Windows Update，但不保證能正常更新，若未來搜尋不到新更新可自行下載更新檔，並嘗試使用dism或dism++套用更新檔

版本：Windows 10 Pro (x64)

組建：19043.962

大小：2.62GB

下載：[Google雲端](http://tiny.cc/w10_21H1_20210422)、[OneDrive](http://tiny.cc/w10_21H1_20210422_o)

SHA-256：B388AF6C978F512146F2D8D71B8DD4167C577E6B49F221E68216A5F948B52D91

已知問題：
- 安裝時間過久，原因未知
