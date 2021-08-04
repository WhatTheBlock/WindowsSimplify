# Win10 boot.wim

### 簡介：
使用精簡系統時若因為驅動等原因而無法安裝，這裡會提供一個手動修復的方案，只要使用精簡版遇到問題一律改用原版boot，如果使用原版還遇到問題請注意是否符合以下條件
1. 使用USB開機安裝
2. 映像語系是否相同 (boot & install)
3. 位元是否相同 (boot & install)

### 使用說明：
使用方式有兩種，一種是先製作USB開機碟再替換檔案，一種是製作新的ISO檔，如果是給虛擬機使用就只能製作新的ISO，不過...如果使用虛擬機在安裝時遇到問題首先要檢查的是虛擬機設定而不是我製作的系統= =

首先介紹先製作USB開機碟的方式
1. 保留以下檔案，其餘刪除
<pre><code>X:\autounattend.xml (如果有的話)
X:\sources\install.esd (or install.wim)
X:\sources\$OEM$ (如果有的話)</code></pre>
2. 將壓縮檔內的檔案解壓到開機碟的根目錄

製作新的ISO檔
1. 將壓縮檔內的檔案解壓到自訂的目錄 (以 D:\iso 舉例)
2. 將以下ISO內的檔案複製到自訂的目錄中
<pre><code>autounattend.xml (如果有的話)
sources\install.esd (or install.wim)
sources\$OEM$ (如果有的話)</code></pre>
3. 確認各檔案路徑是否正確
<pre><code>D:\iso\autounattend.xml (如果有的話)
D:\iso\sources\install.esd (or install.wim)
D:\iso\sources\$OEM$ (如果有的話)</code></pre>
4. 利用DISM++或MSMG等工具建立ISO檔

![preview.png](/tutorial/iso.png)

### 注意事項：
- 盡量避免使用覆蓋檔案的方式替換檔案，除非你對ISO裡面的檔案架構非常了解
- 精簡版建議配合我製作的autounattend.xml一起使用，否則可能出現預期外的狀況

----

#### 繁體中文精簡版

下載：(適用19041.1以前系統)
- x86 (197MB) - [Google雲端](https://drive.google.com/uc?export=download&id=1QLFTYzZaJMZfKSMmgIF66gfsQQr8TiF1)、[Github](https://github.com/WhatTheBlock/Win10_Simplify/releases/download/v2021.05.06/boot_ct_x86_lite.7z)
- x64 (145MB) - [Google雲端](https://drive.google.com/uc?export=download&id=10J1NOommQQeuSx9JwIm1n4dbxgBsuuao)、[Github](https://github.com/WhatTheBlock/Win10_Simplify/releases/download/v2021.05.06/boot_ct_x64_lite.7z)

下載：(適用19041.1以後系統)
- x64 (351MB) - [Github](https://github.com/WhatTheBlock/WindowsSimplify/releases/download/v2021.05.06/boot_19041_ct_x64_lite.7z)

----

#### 繁體中文原版

下載：(適用19041.1以前系統)
- x86 (237MB) - [Google雲端](https://drive.google.com/uc?export=download&id=1OVgAIJgVIvoEj2OtVjquOVGc8H0V1t3V)、[Github](https://github.com/WhatTheBlock/Win10_Simplify/releases/download/v2021.05.06/boot_ct_x86.7z)
- x64 (287MB) - [Google雲端](https://drive.google.com/uc?export=download&id=1r9AInIGB7BMlZufCVY4cKD_AlM-xjWyc)、[Github](https://github.com/WhatTheBlock/Win10_Simplify/releases/download/v2021.05.06/boot_ct_x64.7z)

下載：(適用19041.1以後系統)
- x64 (491MB) - [Github](https://github.com/WhatTheBlock/WindowsSimplify/releases/download/v2021.05.06/boot_19041_ct_x64.7z)

----

#### 英文精簡版

下載：
- x86 (153MB) - [Google雲端](https://drive.google.com/uc?export=download&id=122XH9Gdww7knFvZk62ctgdyTRZvf10O_)、[Github](https://github.com/WhatTheBlock/Win10_Simplify/releases/download/v2021.05.06/boot_en_x86_lite.7z)
- x64 (98.2MB) - [Google雲端](https://drive.google.com/uc?export=download&id=1ucDQf9zic9TyzxHd6SfLkiOaQcJEb-r7)、[Github](https://github.com/WhatTheBlock/Win10_Simplify/releases/download/v2021.05.06/boot_en_x64_lite.7z)

----

#### 英文原版

下載：
- x86 (201MB) - [Google雲端](https://drive.google.com/uc?export=download&id=1M829x2LbxGxECbQDtzASQNwUdhj0Voop)、[Github](https://github.com/WhatTheBlock/Win10_Simplify/releases/download/v2021.05.06/boot_en_x86.7z)
- x64 (244MB) - [Google雲端](https://drive.google.com/uc?export=download&id=1IPyiEI_iYXWKiphA8OllHHbdZ5T_EqAi)、[Github](https://github.com/WhatTheBlock/Win10_Simplify/releases/download/v2021.05.06/boot_en_x64.7z)
