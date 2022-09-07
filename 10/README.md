# Stable Release

#### Slightly optimized and debloated.
#### Usually I release additional ver.2, which removes WinSxS.

----

### x64

**Preview：**
![preview](/preview/19044.1679_220416.png)

**Edition：** Windows 10 Pro

**OS Build：** 19044.1679

**ISO Size：** 2.74GB (Ver.1)、1.75GB (Ver.2)

**Download：** [Part 1](https://github.com/WhatTheBlock/WindowsSimplify/releases/download/w10.220416/19044.1679_220416.part1.rar)、[Part 2](https://github.com/WhatTheBlock/WindowsSimplify/releases/download/w10.220416/19044.1679_220416.part2.rar)、[Ver.2](https://github.com/WhatTheBlock/WindowsSimplify/releases/download/w10.220416/19044.1679_220416-2.iso)

**SHA-256：**
- Ver.1: a605e0831500891f9612de1eaea7e921e45cd3e5419832eeb2176228ea288007
- Ver.2: 6a01e3d246abe9eb3cc121fb9ca5f3720a8d0eeeb64789b95cb76c93389d0c79

**Highlights：**
- Rectify 11 Cursors
- Windows 11 Icons
- Preinstall the new Windows Store

----

### LTSC 2021 x64

**Preview：**
![preview](/preview/LTSC_19044.1766_220619.png)

**Edition：** Enterprise LTSC 2021

**OS Build：** 19044.1826

**ISO Size：** 2.8GB

**Download：** [Link](https://drive.google.com/uc?export=download&id=1eWdYOm_ON6KkvVNuRu9tg5F1P090GbwB)

**SHA-256：** 69687f2e1b1b49704ba5d63970ec8ec1fb2b38ccfd1bf18e3462ac84acbd652c

**Highlights：**
- Rectify 11 Cursors
- Rectify 10 boot
- Windows 11 Icons
- Preinstall VC++ Runtime
- Fixed IME bug
- Debloated

----

### LTSC 2021 x64 (en-US)

**Preview：**
- Ver.1
![1](/preview/LTSC_19044.1947_220828_2.png)

- Ver.2 (Extreme Lite version, please use carefully.)
![2](/preview/LTSC_19044.1947_220828-2.png)

**Edition：** Enterprise LTSC 2021

**OS Build：** 19044.1947

**ISO Size：** 2.72GB (Ver.1)、1.51GB (Ver.2)

**Download：** [Ver.1](https://gmnfuedutw-my.sharepoint.com/:u:/g/personal/40543229_gm_nfu_edu_tw/Eel0vC_A6DJAvZWrrLQChaUB_omXog-91eEAVjajs1o7zQ?e=ohoWIn)、[Ver.2](https://gmnfuedutw-my.sharepoint.com/:u:/g/personal/40543229_gm_nfu_edu_tw/EctfZvX1qPhJjf6WejA8ZFEBtWU2jXfzyymQsVpEImCBLA?e=iGui9i)

**SHA-256：**
- Ver.1: 9dc0ec7ce20cbe669b487023d7b495f138d233bfdd47f6dea844940b18827d18
- Ver.2: df7454e1f9cc0536e4c855a5ea3d6b3c726fa2986d65d6937251715a664aab6a

**Highlights：**
- Rectify 11 Cursors
- Rectify 10 boot
- Windows 11 Icons
- Preinstall VC++ Runtime
- Debloated

----

### LTSC 2019 x64

**Preview：**
![preview](/preview/LTSC_17763.2803_220424.png)

**Edition：** Enterprise LTSC 2019

**OS Build：** 17763.2803

**ISO Size：** 2.78GB

**Download：** [Part 1](https://github.com/WhatTheBlock/WindowsSimplify/releases/download/ltsc.220424/LTSC_17763.2803_220424.part1.rar)、[Part 2](https://github.com/WhatTheBlock/WindowsSimplify/releases/download/ltsc.220424/LTSC_17763.2803_220424.part2.rar)

**SHA-256：** 1f11b2f9125c2c268cba0c57101f05c11ace771d74e827ceced03ec426a38636

**Highlights：**
- Rectify 11 Cursors
- Rectify 10 boot
- Windows 11 Icons
- Preinstall VC++ Runtime
- Debloated

**Notice：**
- Cumulative Updates need to be installed using DISM.
- If `Add-WindowsCapability` fails, use the steps below to fix it.  
<pre><code>Dism /Online /Cleanup-Image /CheckHealth
Dism /Online /Cleanup-Image /ScanHealth
Dism /Online /Cleanup-Image /RestoreHealth
sfc /scannow</code></pre>
