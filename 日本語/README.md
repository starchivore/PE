[http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=60426](http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=60426)
>These are left running, and the rest is at “stop.”
>
>1. AudioendpointB
>2. Audiosrv
>3. Dcomlaunch
>4. LSM
>5. RpcEptMapper
>6. RpcSc
>7. SamSc

[http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=62884](http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=62884)
>1. ULTRALITE (Shell: Processhacker)  
>processes=17  
>threads=148  
>handles=3718  
>CPU=0.23%

[http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=64022](http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=64022)
>bringing the final size of Win11PE audiophile to **93.8 MB** with ASIO drivers and F2k + BugHead 7.27.  
>The size of Win11PE bare audio is **78.7 MB**.

[http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=65633](http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=65633)
>System Idle Process  
>System  
>smss.exe (Suspended in Process Hacker, then all handles closed in handles tab)  
>Registry  
>csrss.exe (Suspended in Process Hacker, then some threads and handles closed, can post screenshots later of which ones if there is interest)  
>wininit.exe (Suspended in Process Hacker, then some handles closed, can post screenshot of which ones if there is interest)  
>services.exe  
>svchost.exe (RpcSs, RpcEptMapper)  
>svchost.exe (AudioEndpointBuilder)  
>svchost.exe (AudioSrv)  
>audiodg.exe  
>svchost.exe (CryptSvc)  
>lsass.exe  
>csrss.exe  
>(Various TIDAL.exe/TIDALPlayer.exe processes)  
>fontdrvhost.exe

---

Start downloading both `WinPE_JA-JP.ISO` and `Windows10PE v1.iso` because the speed should be slow, then keep reading the rest of this document.

At first it might seem to be overwhelming but ultimately it's just a matter of taking the time to read so that we could get a better understanding.

[https://archive.org/download/winpe_iso/Win7PE_ja-JP.ISO](https://archive.org/download/winpe_iso/Win7PE_ja-JP.ISO)

[https://archive.org/download/winpe_iso/Win11PE_JA-JP.ISO](https://archive.org/download/winpe_iso/Win11PE_JA-JP.ISO)

WinPE JA JP, Windows 11 PE, WinPE, Windows パスワードのクラッキング、 日本語版、Win11PE、Windows プレインストール環境日本語版、説明内のリンク

[https://www.youtube.com/watch?v=xbm6Njan63I](https://www.youtube.com/watch?v=xbm6Njan63I)

yuu331

[https://archive.org/details/@yuu331](https://archive.org/details/@yuu331)

Windows 10 PE v1 ja-jp

[https://archive.org/download/windows-10-pe-v1/Windows10PE%20v1.iso](https://archive.org/download/windows-10-pe-v1/Windows10PE%20v1.iso)

WinPE 11 – Extended Recovery Environment for Windows

[https://www.aioboot.com/en/winpe-11/](https://www.aioboot.com/en/winpe-11/)

[https://drive.google.com/file/d/1AJMhaK6j3SVIeBBNuK-fg_ePMLQAOtu1/view](https://drive.google.com/file/d/1AJMhaK6j3SVIeBBNuK-fg_ePMLQAOtu1/view)

AIO Boot NewGen – A lightweight version with a new design

[https://www.aioboot.com/en/newgen/](https://www.aioboot.com/en/newgen/)

[https://files1.majorgeeks.com/10afebdbffcd4742c81a3cb0f6ce4092156b4375/diagnostics/AIO_Boot_NewGen_Setup.exe](https://files1.majorgeeks.com/10afebdbffcd4742c81a3cb0f6ce4092156b4375/diagnostics/AIO_Boot_NewGen_Setup.exe)

AOMEI PE Builder: Create A Custom WinPE

[https://www.youtube.com/watch?v=wT4rhw9eK98](https://www.youtube.com/watch?v=wT4rhw9eK98)

Portable AOMEI PE Builder v2.0

[https://www.fcportables.com/aomei-pe-builder-portable/](https://www.fcportables.com/aomei-pe-builder-portable/)

[https://uploadrar.com/oqa40iza8dkd](https://uploadrar.com/oqa40iza8dkd)

[https://rapidgator.net/file/025ade9db59ae478a0e127f3add1ee94](https://rapidgator.net/file/025ade9db59ae478a0e127f3add1ee94)

[https://uploadrar.com/v5ckke99dx6j](https://uploadrar.com/v5ckke99dx6j)

Vector 新着ソフトレビュー 「AOMEI PE Builder」 - より実用的なWindows PE環境のブータブルメディアを手軽に作成できるソフト

[https://www.vector.co.jp/magazine/softnews/141120/n1411201.html](https://www.vector.co.jp/magazine/softnews/141120/n1411201.html)

[https://ftp.vector.co.jp/65/80/2317/PEBuilder.exe](https://ftp.vector.co.jp/65/80/2317/PEBuilder.exe)

Download Windows PE Build Environment

[https://www.aomeitech.com/windows-tips/win-pe.html](https://www.aomeitech.com/windows-tips/win-pe.html)

[https://www2.aomeisoftware.com/download/pe/2.0/full/PEBuilder.exe](https://www2.aomeisoftware.com/download/pe/2.0/full/PEBuilder.exe)

[https://www2.aomeisoftware.com/download/pe/2.0/PEBuilder.exe](https://www2.aomeisoftware.com/download/pe/2.0/PEBuilder.exe)

[https://archive.org/download/pe-builder-2.0/PEBuilder.exe](https://archive.org/download/pe-builder-2.0/PEBuilder.exe)

[https://files1.majorgeeks.com/10afebdbffcd4742c81a3cb0f6ce4092156b4375/backup/PEBuilder.exe](https://files1.majorgeeks.com/10afebdbffcd4742c81a3cb0f6ce4092156b4375/backup/PEBuilder.exe)

[https://web.archive.org/web/20181107184903id_/https://www2.aomeisoftware.com/download/pe/2.0/PEBuilder.exe](https://web.archive.org/web/20181107184903id_/https://www2.aomeisoftware.com/download/pe/2.0/PEBuilder.exe)

AOMEI PE Builder is a software which enables you to create a bootable USB/CD based on Winddows PE.

[https://www.aomeitech.com/windows-tips/pe-builder.html](https://www.aomeitech.com/windows-tips/pe-builder.html)

[https://1drv.ms/f/s!AnwDzP9NGW0wgaFb1eB7m4mJu2Pc8g](https://1drv.ms/f/s!AnwDzP9NGW0wgaFb1eB7m4mJu2Pc8g)

---

これ一つでWindowsトラブルに対応できる必須ツール『AOMEI PE Builder 2.0』

[https://suraugi.com/?p=457](https://suraugi.com/?p=457)

Aomei PE Builderの使い方・インストール方法を紹介！

[https://aprico-media.com/posts/6508](https://aprico-media.com/posts/6508)

AOMEI PE Builder で OC 後の WinPE ベースなストレステスト環境を構築する

[https://bucci.bp7.org/archives/43370/](https://bucci.bp7.org/archives/43370/)

手軽にWindows PE環境を作成できる「AOMEI PE Builder」が2.0にアップデート。EFI/BIOSの両方に対応

[https://satsumahomeserver.com/blog/284439](https://satsumahomeserver.com/blog/284439)

Windows PE (AOMEI)は、AOMEI PE Builderというソフトで作成できる自作PEである。

[https://yuuya.fandom.com/ja/wiki/Windows_PE_(AOMEI)](https://yuuya.fandom.com/ja/wiki/Windows_PE_(AOMEI))

Windows が正常に起動しなくなった場合などの緊急時に利用できる Windows PE ブータブルディスクを作成できるソフト

[https://freesoft-100.com/review/aomei-pe-builder.html](https://freesoft-100.com/review/aomei-pe-builder.html)

「Windows PE」ベースの復旧メディアを手軽に作成できる「AOMEI PE Builder」

[https://forest.watch.impress.co.jp/docs/review/1102042.html](https://forest.watch.impress.co.jp/docs/review/1102042.html)

AOMEI PE Builder2.0 日本語化　その1

[http://blog.livedoor.jp/hichitose/archives/52425773.html](http://blog.livedoor.jp/hichitose/archives/52425773.html)

AOMEI PE Builder2.0 日本語化　その2

[http://blog.livedoor.jp/hichitose/archives/52425934.html](http://blog.livedoor.jp/hichitose/archives/52425934.html)

AOMEI PE Builder2.0 日本語化　その3

[http://blog.livedoor.jp/hichitose/archives/52426172.html](http://blog.livedoor.jp/hichitose/archives/52426172.html)

AOMEI PE Builderから日本語化したWindowsPE環境を作る方法

[https://qwerty.work/blog/2020/03/aome-pe-builder-japanese-version.php](https://qwerty.work/blog/2020/03/aome-pe-builder-japanese-version.php)

---

トピック: Windows PEの起動ディスクの作成について

[https://pctrouble.net/bbs/topic/555/](https://pctrouble.net/bbs/topic/555/)

オーバークロック設定後のストレステスト環境を WinPE ベースで構築する

[https://bucci.bp7.org/archives/43332/](https://bucci.bp7.org/archives/43332/)

WinPe-tchのダウンロード等

[https://ftp.vector.co.jp/75/17/2694/pex.zip](https://ftp.vector.co.jp/75/17/2694/pex.zip)

[https://kiki2.suppa.jp/pe_winpetch.htm](https://kiki2.suppa.jp/pe_winpetch.htm)

WinPe-tch Directの使い方

[https://kiki2.suppa.jp/pe_winpetchd-howto.htm](https://kiki2.suppa.jp/pe_winpetchd-howto.htm)

WinPEを作成 (Win10PESE、WinPtchX)

[https://qiita.com/tukiyo3/items/f1cd3e8eaaaba50ac9e5](https://qiita.com/tukiyo3/items/f1cd3e8eaaaba50ac9e5)

WinPtchX のダウンロード・使い方

[https://freesoft-100.com/review/winptchx.html](https://freesoft-100.com/review/winptchx.html)

WinPtchXを使ってセキュアブート対応WindowsPEを作る

[https://jisaku-pc.net/hddnavi/winptchx.html](https://jisaku-pc.net/hddnavi/winptchx.html)

日本語版Windows PE + Macrium Reflect 起動USBの作成

[http://tasys.blog7.fc2.com/blog-entry-40.html](http://tasys.blog7.fc2.com/blog-entry-40.html)

WinPE6.0 (Windows10)の作成方法　～　windows

[http://memo.eightban.com/windows/winpe60](http://memo.eightban.com/windows/winpe60)

Windows 8.1/10 ベースの Windows PEを作成できるソフト

[https://freesoft-100.com/review/winptchx.html](https://freesoft-100.com/review/winptchx.html)

日本語版WindowsPEメディアを作成する方法

[https://qiita.com/SkyLaptor/items/204245cf6bb4fee5b19d](https://qiita.com/SkyLaptor/items/204245cf6bb4fee5b19d)

WindowsPEにもっと簡単にアプリケーションを追加する

[https://qiita.com/yuriyuriyuriyuri/items/c591842a67e047e67d90](https://qiita.com/yuriyuriyuriyuri/items/c591842a67e047e67d90)

★1CD起動★☆★Windows PE★☆★手作りOS★

[https://mevius.5ch.net/test/read.cgi/win/1257735910/](https://mevius.5ch.net/test/read.cgi/win/1257735910/)

---

Windows ADKのダウンロードとインストール

[https://support.lifeboat.jp/docs/rmb/RMB_guide.pdf](https://support.lifeboat.jp/docs/rmb/RMB_guide.pdf)

[https://www.lifeboat.jp/info/wadk10_dl.php](https://www.lifeboat.jp/info/wadk10_dl.php)

---

Some users of Windows PE might prefer 22000 (Windows 11 Version 21H2) and here's the Japanese version of the ISO image:

[https://archive.org/download/22000.1.210604-1628.-co-release-clientmulti-x-64-fre-ja-jp_202107/22000.1.210604-1628.CO_RELEASE_CLIENTMULTI_X64FRE_JA-JP.ISO](https://archive.org/download/22000.1.210604-1628.-co-release-clientmulti-x-64-fre-ja-jp_202107/22000.1.210604-1628.CO_RELEASE_CLIENTMULTI_X64FRE_JA-JP.ISO)

---

And then here's the Japanese version of 20348 (Windows Server 2022) ISO image:

[https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_SERVER_EVAL_x64FRE_ja-jp.iso](https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_SERVER_EVAL_x64FRE_ja-jp.iso)

---

Others would actually like 19041 (Windows 10 Version 2004) instead, only English version could be found so far:

[https://archive.org/download/19041.1-professional-x-64-en-us/19041.1_PROFESSIONAL_X64_EN-US.ISO](https://archive.org/download/19041.1-professional-x-64-en-us/19041.1_PROFESSIONAL_X64_EN-US.ISO)

---

[https://www.microsoft.com/ja-jp/evalcenter/download-windows-10-enterprise](https://www.microsoft.com/ja-jp/evalcenter/download-windows-10-enterprise)

[https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66750/19045.2006.220908-0225.22h2_release_svc_refresh_CLIENTENTERPRISEEVAL_OEMRET_x64FRE_ja-jp.iso](https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66750/19045.2006.220908-0225.22h2_release_svc_refresh_CLIENTENTERPRISEEVAL_OEMRET_x64FRE_ja-jp.iso)

[http://dl.delivery.mp.microsoft.com/filestreamingservice/files/21fca164-78ff-49f2-b344-5bdd3a049c26/19041.264.200511-0456.vb_release_svc_refresh_CLIENTBUSINESS_VOL_x64FRE_ja-jp.esd](http://dl.delivery.mp.microsoft.com/filestreamingservice/files/21fca164-78ff-49f2-b344-5bdd3a049c26/19041.264.200511-0456.vb_release_svc_refresh_CLIENTBUSINESS_VOL_x64FRE_ja-jp.esd)

[http://dl.delivery.mp.microsoft.com/filestreamingservice/files/92e5b2b8-a02c-4389-90dd-5cec89159f3c/19041.264.200511-0456.vb_release_svc_refresh_CLIENTCONSUMER_RET_x64FRE_ja-jp.esd](http://dl.delivery.mp.microsoft.com/filestreamingservice/files/92e5b2b8-a02c-4389-90dd-5cec89159f3c/19041.264.200511-0456.vb_release_svc_refresh_CLIENTCONSUMER_RET_x64FRE_ja-jp.esd)

[http://dl.delivery.mp.microsoft.com/filestreamingservice/files/b994e4e1-f3a5-4175-a888-5fa2a81b4d70/19045.2006.220908-0225.22h2_release_svc_refresh_CLIENTBUSINESS_VOL_x64FRE_ja-jp.esd](http://dl.delivery.mp.microsoft.com/filestreamingservice/files/b994e4e1-f3a5-4175-a888-5fa2a81b4d70/19045.2006.220908-0225.22h2_release_svc_refresh_CLIENTBUSINESS_VOL_x64FRE_ja-jp.esd)

[http://dl.delivery.mp.microsoft.com/filestreamingservice/files/5a3d3076-277c-40af-802a-804482e396be/19045.2006.220908-0225.22h2_release_svc_refresh_CLIENTCONSUMER_RET_x64FRE_ja-jp.esd](http://dl.delivery.mp.microsoft.com/filestreamingservice/files/5a3d3076-277c-40af-802a-804482e396be/19045.2006.220908-0225.22h2_release_svc_refresh_CLIENTCONSUMER_RET_x64FRE_ja-jp.esd)

[https://msdl.gravesoft.dev/#2618](https://msdl.gravesoft.dev/#2618)

[https://archive.org/download/win-11-japanese-x-64/Win11_Japanese_x64.iso](https://archive.org/download/win-11-japanese-x-64/Win11_Japanese_x64.iso)

---

Intel® Ethernet Adapter Complete Driver Pack

[https://downloadmirror.intel.com/825752/Release_29.1.2.zip](https://downloadmirror.intel.com/825752/Release_29.1.2.zip)

[https://www.intel.com/content/www/us/en/download/15084/intel-ethernet-adapter-complete-driver-pack.html](https://www.intel.com/content/www/us/en/download/15084/intel-ethernet-adapter-complete-driver-pack.html)

Intel® Network Adapter Driver for Microsoft* Windows* 11

[https://downloadmirror.intel.com/822659/Wired_driver_29.1_x64.zip](https://downloadmirror.intel.com/822659/Wired_driver_29.1_x64.zip)

[https://www.intel.com/content/www/us/en/download/727998/intel-network-adapter-driver-for-microsoft-windows-11.html](https://www.intel.com/content/www/us/en/download/727998/intel-network-adapter-driver-for-microsoft-windows-11.html)

[DRIVERS] Intel Ethernet/WiFi/Bluetooth

[https://rog-forum.asus.com/t5/downloads-for-motherboards/drivers-intel-ethernet-wifi-bluetooth/td-p/878985](https://rog-forum.asus.com/t5/downloads-for-motherboards/drivers-intel-ethernet-wifi-bluetooth/td-p/878985)

[DRIVERS] Realtek Ethernet/WiFi/Bluetooth

[https://rog-forum.asus.com/t5/downloads-for-motherboards/drivers-realtek-ethernet-wifi-bluetooth/td-p/871130](https://rog-forum.asus.com/t5/downloads-for-motherboards/drivers-realtek-ethernet-wifi-bluetooth/td-p/871130)

[DRIVERS] Intel Chipset/MEI/VMD (6xx/7xx)

[https://rog-forum.asus.com/t5/downloads-for-motherboards/drivers-intel-chipset-mei-vmd-6xx-7xx/td-p/892895](https://rog-forum.asus.com/t5/downloads-for-motherboards/drivers-intel-chipset-mei-vmd-6xx-7xx/td-p/892895)

[DRIVERS] Intel Chipset/MEI/SATA (1xx/2xx/3xx/4xx/5xx)

[https://rog-forum.asus.com/t5/downloads-for-motherboards/drivers-intel-chipset-mei-sata-1xx-2xx-3xx-4xx-5xx/td-p/855805](https://rog-forum.asus.com/t5/downloads-for-motherboards/drivers-intel-chipset-mei-sata-1xx-2xx-3xx-4xx-5xx/td-p/855805)

SM750 VGA driver ver:10.00.17.00

[https://download.asrock.com/Drivers/All/VGA/SM750(v10.00.17.00).zip](https://download.asrock.com/Drivers/All/VGA/SM750(v10.00.17.00).zip)

SM750 WDDM2.0 v10.00.12.00 WHQL

[https://www.sunix.com/download/driver/2019/20190822160201_SM750_WDDM2.0_v10.00.12.00_WHQL.zip](https://www.sunix.com/download/driver/2019/20190822160201_SM750_WDDM2.0_v10.00.12.00_WHQL.zip)

SiliconMotion - Display - 2.20.1.0

[https://catalog.s.download.windowsupdate.com/d/msdownload/update/driver/drvs/2024/06/8c16a957-d264-4f37-81a5-e54ded33b7fe_02036d747aeda5b3bc11a0c2ae1db57d6208b246.cab](https://catalog.s.download.windowsupdate.com/d/msdownload/update/driver/drvs/2024/06/8c16a957-d264-4f37-81a5-e54ded33b7fe_02036d747aeda5b3bc11a0c2ae1db57d6208b246.cab)

ASMedia Technology Inc - USB - 1.16.61.1	

[https://catalog.s.download.windowsupdate.com/c/msdownload/update/driver/drvs/2020/08/eaac4795-c4df-40b5-b545-433537eba5bf_a5b6416f7953c9236d3cd04a6836a91b8b4744dc.cab](https://catalog.s.download.windowsupdate.com/c/msdownload/update/driver/drvs/2020/08/eaac4795-c4df-40b5-b545-433537eba5bf_a5b6416f7953c9236d3cd04a6836a91b8b4744dc.cab)

インテル® SSD 用データセンター NVMe* Microsoft Windows* ドライバー

[https://dl.driverpack.io/driverpacks/repack/MassStorage/Intel/FORCED/NVMe/88110x64/5.3.0.1010/Intel-FORCED-NVMe-88110x64-5.3.0.1010-drp.zip](https://dl.driverpack.io/driverpacks/repack/MassStorage/Intel/FORCED/NVMe/88110x64/5.3.0.1010/Intel-FORCED-NVMe-88110x64-5.3.0.1010-drp.zip)

[https://web.archive.org/web/20221221202522/https://www.intel.co.jp/content/www/jp/ja/download/17797/datacenter-nvme-microsoft-windows-drivers-for-intel-ssds.html](https://web.archive.org/web/20221221202522/https://www.intel.co.jp/content/www/jp/ja/download/17797/datacenter-nvme-microsoft-windows-drivers-for-intel-ssds.html)

Solidigm™ Data Center NVMe Windows Driver

[https://web.archive.org/web/20230322153431id_/https://sdmsdfwdriver.blob.core.windows.net/files/kba-gcc/drivers-downloads/ka-00095--ddriver/5-3-0-1005/datacenter-x64.zip](https://web.archive.org/web/20230322153431id_/https://sdmsdfwdriver.blob.core.windows.net/files/kba-gcc/drivers-downloads/ka-00095--ddriver/5-3-0-1005/datacenter-x64.zip)

[https://web.archive.org/web/20221215161807/https://www.solidigm.com/content/solidigm/us/en/support-page/drivers-downloads/ka-00095.html](https://web.archive.org/web/20221215161807/https://www.solidigm.com/content/solidigm/us/en/support-page/drivers-downloads/ka-00095.html)

Intel NVMe drivers discontinued - Optane 905p, P5800X, etc

[https://forum.level1techs.com/t/intel-nvme-drivers-discontinued-optane-905p-p5800x-etc/194003/4](https://forum.level1techs.com/t/intel-nvme-drivers-discontinued-optane-905p-p5800x-etc/194003/4)

---

How to Install the ASPEED Windows 11 VGA Driver for Better Video

[https://www.aspeedtech.com/file/support/v11502_windows.zip](https://www.aspeedtech.com/file/support/v11502_windows.zip)

[https://www.servethehome.com/how-to-install-the-aspeed-windows-11-vga-driver-for-better-video/](https://www.servethehome.com/how-to-install-the-aspeed-windows-11-vga-driver-for-better-video/)

---

ASIO driver for USB DACs:

[http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=63240](http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=63240)

[http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=64366](http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=64366)

[http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=65869](http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=65869)

---

Dism ++ 10.1.1002.2

[https://softaro.net/dism-plus-plus/](https://softaro.net/dism-plus-plus/)

[https://files1.majorgeeks.com/10afebdbffcd4742c81a3cb0f6ce4092156b4375/allinone/Dism++10.1.1002.1B.zip](https://files1.majorgeeks.com/10afebdbffcd4742c81a3cb0f6ce4092156b4375/allinone/Dism++10.1.1002.1B.zip)

[https://github.com/Chuyu-Team/Dism-Multi-language/releases/download/v10.1.1002.2/Dism++10.1.1002.1B.zip](https://github.com/Chuyu-Team/Dism-Multi-language/releases/download/v10.1.1002.2/Dism++10.1.1002.1B.zip)

---

TuneBrowser might need the file `WMVCORE.dll` if that were missing, it could be extracted from Media Feature Pack.

We don't really need to reinstall TuneBrowser, copy 5 folders as shown below while exporting / importing the registry keys from 2 specific locations:

[https://tikisoft.net/software/TuneBrowser(x64.AVX2)Setup5.5.1.zip](https://tikisoft.net/software/TuneBrowser(x64.AVX2)Setup5.5.1.zip)

[https://tunebrowser.tikisoft.net/forums/topic/13322/#post-13328](https://tunebrowser.tikisoft.net/forums/topic/13322/#post-13328)
>ディレクトリ群
>
>- %APPDATA%/Local/TuneBrowser  
>- %APPDATA%/Local/Tiki  
>- %APPDATA%/Roaming/Tiki  
>- %ProgramData%/Tiki  
>- %ProgramFiles%/TuneBrowser  
>
>レジストリ
>- HKEY_CURRENT_USER\SOFTWARE\Tiki  
>- HKEY_LOCAL_MACHINE\SOFTWARE\Tiki
```
C:\Users\○○\AppData\Local\TuneBrowser
C:\Users\○○\AppData\Local\Tiki
C:\Users\○○\AppData\Roaming\Tiki
C:\ProgramData\Tiki
C:\Program Files\TuneBrowser
```
```
X:\Users\Administrator\AppData\Local\TuneBrowser
X:\Users\Administrator\AppData\Local\Tiki
X:\Users\Administrator\AppData\Roaming\Tiki
X:\ProgramData\Tiki
X:\Program Files\TuneBrowser
```
Media Feature Pack list for Windows N editions

[https://support.microsoft.com/en-us/topic/media-feature-pack-list-for-windows-n-editions-c1c6fffa-d052-8338-7a79-a4bb980a700a](https://support.microsoft.com/en-us/topic/media-feature-pack-list-for-windows-n-editions-c1c6fffa-d052-8338-7a79-a4bb980a700a)

26100

[https://catalog.sf.dl.delivery.mp.microsoft.com/filestreamingservice/files/f871b923-f0d0-442a-be61-b461cb1c73c9/public/Microsoft-Windows-Media-Features-Package~31bf3856ad364e35~amd64~~_89ad81bbe632d58bee4ba55493e7cbb43103e4d7.cab](https://catalog.sf.dl.delivery.mp.microsoft.com/filestreamingservice/files/f871b923-f0d0-442a-be61-b461cb1c73c9/public/Microsoft-Windows-Media-Features-Package~31bf3856ad364e35~amd64~~_89ad81bbe632d58bee4ba55493e7cbb43103e4d7.cab)

25398

[https://catalog.sf.dl.delivery.mp.microsoft.com/filestreamingservice/files/4a332d62-ef43-4743-b9a9-beb9d3ba0a26/public/Microsoft-Windows-Media-Features-Package~31bf3856ad364e35~amd64~~_732cc12966106e8698f77f8f8ee9939cfa8d95e9.cab](https://catalog.sf.dl.delivery.mp.microsoft.com/filestreamingservice/files/4a332d62-ef43-4743-b9a9-beb9d3ba0a26/public/Microsoft-Windows-Media-Features-Package~31bf3856ad364e35~amd64~~_732cc12966106e8698f77f8f8ee9939cfa8d95e9.cab)

22621

[https://catalog.sf.dl.delivery.mp.microsoft.com/filestreamingservice/files/10ca86a3-424d-4730-a059-23c212d9afdc/public/Microsoft-Windows-Media-Features-Package~31bf3856ad364e35~amd64~~_a097c6eaabb77fa99017acc91aad0bf88b6780e8.cab](https://catalog.sf.dl.delivery.mp.microsoft.com/filestreamingservice/files/10ca86a3-424d-4730-a059-23c212d9afdc/public/Microsoft-Windows-Media-Features-Package~31bf3856ad364e35~amd64~~_a097c6eaabb77fa99017acc91aad0bf88b6780e8.cab)

22000

[https://uupdump.net/getfile.php?id=507cf67d-d0b0-4139-af31-6ad2c42d9aa4&file=Microsoft-Windows-Media-Features-Package-amd64.cab](https://uupdump.net/getfile.php?id=507cf67d-d0b0-4139-af31-6ad2c42d9aa4&file=Microsoft-Windows-Media-Features-Package-amd64.cab)

20348

[https://uupdump.net/getfile.php?id=a341031f-9835-4c4b-bcad-b5d7eb7ef76d&file=Microsoft-Windows-Media-Features-Package-amd64.cab](https://uupdump.net/getfile.php?id=a341031f-9835-4c4b-bcad-b5d7eb7ef76d&file=Microsoft-Windows-Media-Features-Package-amd64.cab)

19041

[https://uupdump.net/getfile.php?id=6d014c9e-61a2-431b-a229-bc7ea20518ba&file=Microsoft-Windows-Media-Features-Package-amd64.cab](https://uupdump.net/getfile.php?id=6d014c9e-61a2-431b-a229-bc7ea20518ba&file=Microsoft-Windows-Media-Features-Package-amd64.cab)

18362

[https://uupdump.net/getfile.php?id=d371aab7-52f8-45f3-b2a4-a417d8e54cb5&file=Microsoft-Windows-Media-Features-Package-amd64.cab](https://uupdump.net/getfile.php?id=d371aab7-52f8-45f3-b2a4-a417d8e54cb5&file=Microsoft-Windows-Media-Features-Package-amd64.cab)

9600

[https://download.microsoft.com/download/8/9/7/89775613-432E-4ECF-93A9-5BAFCB5B7807/Windows8.1-KB2929699-x64.msu](https://download.microsoft.com/download/8/9/7/89775613-432E-4ECF-93A9-5BAFCB5B7807/Windows8.1-KB2929699-x64.msu)

---

[http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=69412](http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=69412)
>You should try running PE in exFAT. It sounds so much better than NTFS.  

[http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=69483](http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=69483)
>You can explain how best to do it?

[http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=69490](http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=69490)
>Everything is super easy if read seeteeyou’s posts carefully. For example here [http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=60598](http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=60598)
>
>So what exactly do we need to then? Basically it all boils down to these files listed below
>
>```
>\Boot\boot.sdi
>
>\Windows\System32\Drivers\exfatsys
>
>\Windows\fbwf.cfg
>
>\Windows\System32\Drivers\fbwf.sys
>```
>
>**boot.sdi** - [https://raw.githubusercontent.com/slorelee/wimbuilder2/master/Projects/WIN10XPE/zz-ISO/boot.sdi](https://raw.githubusercontent.com/slorelee/wimbuilder2/master/Projects/WIN10XPE/zz-ISO/boot.sdi)
>
>**exfat.sys** is already there in your system if it`s not older 2020 as I understand;
>
>**fbwf.sys** - [https://raw.githubusercontent.com/slorelee/wimbuilder2/master/Projects/WIN10XPE/00-Configures/System/fbwf.sys](https://raw.githubusercontent.com/slorelee/wimbuilder2/master/Projects/WIN10XPE/00-Configures/System/fbwf.sys)
>
>**fbwf.cfg** - [https://github.com/slorelee/wimbuilder2/issues/23#issuecomment-596481522](https://github.com/slorelee/wimbuilder2/issues/23#issuecomment-596481522)
>
>it depends to what cache size of PE you prefer. 1024mb suits for me.
>
>So what`s next?  
>You got your VHD arranged and ready to make ISO to load it to RAM.
>
>1. Go to `Windows\System32\Drivers` and replace `fbwf.sys` with one you dowloaded;
>
>2. Put `fbwf.cfg` (The one that suits you - `512`, `1024`, `2048` ...) into `Windows` folder;
>
>3. Then your need to  make some registry changes. Go to [HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\exfat] and change the default value of `Start` from `3` to `0`. Use Remote Registry of Sergei Strelec's ISO or just download reg file ([https://disk.yandex.ru/d/L6OsXAbAT7ACtA](https://disk.yandex.ru/d/L6OsXAbAT7ACtA)) and use DISM++ to make changes to your VHD registry.  
>and save you `WIM` file
>
>4. The next step is making your `ISO`. Open [Ultra ISO](https://uploadrar.com/jcojr576u8um) and replace `boot.sdi` file with the one you dowloaded.
>
>Save your `ISO` and load it to check everything works.

[https://usbtor.ru/viewtopic.php?p=84826#84826](https://usbtor.ru/viewtopic.php?p=84826#84826)
>[http://bbs.wuyou.net/forum.php?mod=attachment&aid=NDYyNjY2fDIwNTkxM2Y5ZGEyYTM0NjY1YWJiMmZiM2RkNzNmN2FjfDE2MTgxMzE0ODM%3D&request=yes&_f=.zip](http://bbs.wuyou.net/forum.php?mod=attachment&aid=NDYyNjY2fDIwNTkxM2Y5ZGEyYTM0NjY1YWJiMmZiM2RkNzNmN2FjfDE2MTgxMzE0ODM%3D&request=yes&_f=.zip)

Registry Editor PE

[https://downloads.sourceforge.net/regeditpe/Registry%20Editor%20PE/1.0a/RegistryEditorPEv1.0a_Beta1.cab](https://downloads.sourceforge.net/regeditpe/Registry%20Editor%20PE/1.0a/RegistryEditorPEv1.0a_Beta1.cab)

[https://regeditpe.sourceforge.net](https://regeditpe.sourceforge.net)

Registry Editor PE - Edit registry without starting windows #registry #regedit

[https://www.youtube.com/watch?v=6W9evdYaFuM](https://www.youtube.com/watch?v=6W9evdYaFuM)

Edit windows registry without booting (offline) – Registry Editor PE [Video]

[https://knowitnow.quora.com/Edit-windows-registry-without-booting-offline-Registry-Editor-PE-Video](https://knowitnow.quora.com/Edit-windows-registry-without-booting-offline-Registry-Editor-PE-Video)

---

Windows PEの稼働時間

[https://port139.hatenablog.com/entry/20090916/1253063817](https://port139.hatenablog.com/entry/20090916/1253063817)
>古いバージョンだと24時間制限（再起動がかかる）という記載があったのでてっきり24時間だと思っていたのですが、最近のバージョンでは「72時間」になっているんですね。

---

PsSuspend

[https://live.sysinternals.com/pssuspend64.exe](https://live.sysinternals.com/pssuspend64.exe)

[https://download.sysinternals.com/files/PSTools.zip](https://download.sysinternals.com/files/PSTools.zip)

[https://learn.microsoft.com/en-us/sysinternals/downloads/pssuspend](https://learn.microsoft.com/en-us/sysinternals/downloads/pssuspend)

[https://reboot.pro/index.php?app=downloads&showfile=229](https://reboot.pro/index.php?app=downloads&showfile=229)

[https://reboot.pro/index.php?showtopic=14731&page=4#entry159223](https://reboot.pro/index.php?showtopic=14731&page=4#entry159223)

[https://support.arcserve.com/s/article/202807255?language=en_US](https://support.arcserve.com/s/article/202807255?language=en_US)
>`pssuspend64.exe winlogon.exe`
>
>This should prevent automatic WinPE reboot and allow recovery of a full-system that exceeds a duration of 72 hours.

---

[http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=60990](http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=60990)
>You can kill the "winlogon.exe" process in Win11XPE audio:
>
>Previously it is necessary to suspend the svchost.exe corresponding to "RpcEptMapper" and "RPC", so excluding processhacker, there are only 10 active processes left.

[http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=60998](http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=60998)
>Fantastic discovery, samotc. It had not occurred to me to try and suspend RpcEptMapper/RPC’s Svchost process.

[http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=61003](http://jplay.eu/forum/index.php?/topic/4410-windows-11-pe-audiophile-creation-guide/?p=61003)
>Anyway, the best news is that eliminating winlogon.exe is definitely an audible improvement, at least to my ears!

Closing Winlogon.exe in Windows PE?

[https://www.youtube.com/watch?v=LxTfpL31Xi8](https://www.youtube.com/watch?v=LxTfpL31Xi8)

---

HotSwap!

[https://files1.majorgeeks.com/10afebdbffcd4742c81a3cb0f6ce4092156b4375/drives/HotSwap!%206.3.0.0.ZIP](https://files1.majorgeeks.com/10afebdbffcd4742c81a3cb0f6ce4092156b4375/drives/HotSwap!%206.3.0.0.ZIP)

[http://mt-naka.com/hotswap/file/HotSwap!%206.3.0.0.ZIP](http://mt-naka.com/hotswap/file/HotSwap!%206.3.0.0.ZIP)

[http://mt-naka.com/hotswap/index_jpn.htm](http://mt-naka.com/hotswap/index_jpn.htm)
>Windowsの「ハードウェアの安全な取り外し」アイコンと同等なユーザーインターフェース。

---

System Informer (formerly known as Process Hacker)

[https://downloads.sourceforge.net/portableapps/SystemInformerPortable_3.0.7578_English.paf.exe](https://downloads.sourceforge.net/portableapps/SystemInformerPortable_3.0.7578_English.paf.exe)

[https://github.com/PortableApps/Downloads/releases/download/download/SystemInformerPortable_3.0.7578_English.paf.exe](https://github.com/PortableApps/Downloads/releases/download/download/SystemInformerPortable_3.0.7578_English.paf.exe)

[https://sourceforge.net/projects/systeminformer/files/](https://sourceforge.net/projects/systeminformer/files/)

---

Shortcut

[https://www.optimumx.com/download/Shortcut.zip](https://www.optimumx.com/download/Shortcut.zip)

[https://www.optimumx.com/downloads.html#Shortcut](https://www.optimumx.com/downloads.html#Shortcut)

---

7-Zip

[https://downloads.sourceforge.net/portableapps/7-ZipPortable_24.07.paf.exe](https://downloads.sourceforge.net/portableapps/7-ZipPortable_24.07.paf.exe)

---

ServiWin

[https://www.nirsoft.net/utils/serviwin-x64.zip](https://www.nirsoft.net/utils/serviwin-x64.zip)

[https://www.nirsoft.net/utils/serviwin.html](https://www.nirsoft.net/utils/serviwin.html)

---

DevManView

[https://www.nirsoft.net/utils/devmanview-x64.zip](https://www.nirsoft.net/utils/devmanview-x64.zip)

[https://www.nirsoft.net/utils/device_manager_view.html](https://www.nirsoft.net/utils/device_manager_view.html)

---

USBDeview

[https://www.nirsoft.net/utils/usbdeview-x64.zip](https://www.nirsoft.net/utils/usbdeview-x64.zip)

[https://www.nirsoft.net/utils/usb_devices_view.html](https://www.nirsoft.net/utils/usb_devices_view.html)

---

DriverView

[https://www.nirsoft.net/utils/driverview-x64.zip](https://www.nirsoft.net/utils/driverview-x64.zip)

[https://www.nirsoft.net/utils/driverview.html](https://www.nirsoft.net/utils/driverview.html)

---

InstalledDriversList

[https://www.nirsoft.net/utils/installeddriverslist-x64.zip](https://www.nirsoft.net/utils/installeddriverslist-x64.zip)

[https://www.nirsoft.net/utils/installed_drivers_list.html](https://www.nirsoft.net/utils/installed_drivers_list.html)

---

LoadedDllsView

[https://www.nirsoft.net/utils/loadeddllsview-x64.zip](https://www.nirsoft.net/utils/loadeddllsview-x64.zip)

[https://www.nirsoft.net/utils/loaded_dll_view.html](https://www.nirsoft.net/utils/loaded_dll_view.html)

---

ListDLLs

[https://live.sysinternals.com/Listdlls64.exe](https://live.sysinternals.com/Listdlls64.exe)

[https://download.sysinternals.com/files/ListDlls.zip](https://download.sysinternals.com/files/ListDlls.zip)

[https://learn.microsoft.com/en-us/sysinternals/downloads/listdlls](https://learn.microsoft.com/en-us/sysinternals/downloads/listdlls)

---

USB Device Tree Viewer

[https://www.uwe-sieber.de/files/UsbTreeView_x64.zip](https://www.uwe-sieber.de/files/UsbTreeView_x64.zip)

[https://www.uwe-sieber.de/usbtreeview_e.html](https://www.uwe-sieber.de/usbtreeview_e.html)

---

jsMSIx.exe - Simple MSI/MSM Unpacker Program

[https://web.archive.org/web/20210629083720id_/https://www.jsware.net/jsware/zips/jsmsix19.zip](https://web.archive.org/web/20210629083720id_/https://www.jsware.net/jsware/zips/jsmsix19.zip)

[https://www.jsware.net/jsware/msicode.html#unpackx](https://www.jsware.net/jsware/msicode.html#unpackx)

---

Free Shooter

[https://github.com/henrypp/freeshooter/releases/download/v.2.1.1/freeshooter-2.1.1-bin.zip](https://github.com/henrypp/freeshooter/releases/download/v.2.1.1/freeshooter-2.1.1-bin.zip)

[https://web.archive.org/web/20231113061759/https://www.henrypp.org/product/freeshooter](https://web.archive.org/web/20231113061759/https://www.henrypp.org/product/freeshooter)

[https://github.com/henrypp/freeshooter#features](https://github.com/henrypp/freeshooter#features)
>To activate portable mode, create `freeshooter.ini` in application folder, or move it from `%APPDATA%\Henry++\Free Shooter`.

[https://github.com/henrypp/freeshooter#system-requirements](https://github.com/henrypp/freeshooter#system-requirements)
>System requirements:
>- Windows 7SP1 and above operating system.
>- Visual C++ 2022 Redistributable package

---

Visual C++ Redistributable

[https://github.com/abbodi1406/vcredist/releases/download/v0.82.0/VisualCppRedist_AIO_x86_x64_82.zip](https://github.com/abbodi1406/vcredist/releases/download/v0.82.0/VisualCppRedist_AIO_x86_x64_82.zip)
```
curl -N -r 4783921152-4784243823 -o "concrt140.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4784244736-4784817743 -o "msvcp140.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4784818176-4784854095 -o "msvcp140_1.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4784855040-4785123431 -o "msvcp140_2.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4785125376-4785175655 -o "msvcp140_atomic_wait.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4785176576-4785208431 -o "msvcp140_codecvt_ids.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4785209344-4785558127 -o "vccorlib140.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4785559552-4785678927 -o "vcruntime140.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4785680384-4785730127 -o "vcruntime140_1.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4785731584-4785770095 -o "vcruntime140_threads.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4785770496-4786183247 -o "vcamp140.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4786184192-4791815247 -o "mfc140.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4791816192-4797481551 -o "mfc140u.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4797483008-4797579887 -o "mfcm140.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4797581312-4797678159 -o "mfcm140u.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4797679616-4797730895 -o "mfc140chs.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4797732864-4797784143 -o "mfc140cht.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4797786112-4797866087 -o "mfc140deu.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4797868032-4797938255 -o "mfc140enu.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4797939712-4798018639 -o "mfc140esn.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4798019584-4798099535 -o "mfc140fra.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4798101504-4798179431 -o "mfc140ita.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4798181376-4798240335 -o "mfc140jpn.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4798240768-4798299215 -o "mfc140kor.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4798300160-4798376039 -o "mfc140rus.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
curl -N -r 4798377984-4798574671 -o "vcomp140.dll" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/EWDK_ge_release_26100_240331-1435.iso
```
---

We only need .NET Framework for Windows PE if we're interested in Grayscale color filters by running NegativeScreen:

```
17763 = Version 1809 (Client)
18362 = Version 1903 (Client)
19041 = Version 2004 (Client)
20348 = Version 21H2 (Server)
22000 = Version 21H2 (Client)
22621 = Version 22H2 (Client)
25398 = Version 23H2 (Server)
26100 = Version 24H2 (Client)
```
[https://updates.macrium.com/reflect/v8/getfeaturelist.asp](https://updates.macrium.com/reflect/v8/getfeaturelist.asp)

17763
```
curl -N -r 1455851520-2211161796 -o "9722214af0ab8aa9dffb6cfdafd937b7.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_amd64fre_adkwinpeaddons.iso
```
18362
```
curl -N -r 1453352960-2213773551 -o "9722214af0ab8aa9dffb6cfdafd937b7.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_amd64fre_adkwinpeaddons.iso
```
19041
```
curl -N -r 1450903552-2085210783 -o "9722214af0ab8aa9dffb6cfdafd937b7.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_amd64fre_adkwinpeaddons.iso
```
20348
```
curl -N -r 1530220544-1849979886 -o "9722214af0ab8aa9dffb6cfdafd937b7.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_adkwinpeaddons.iso
```
22000
```
curl -N -r 1624098816-1943742719 -o "9722214af0ab8aa9dffb6cfdafd937b7.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_adkwinpeaddons.iso
```
22621
```
curl -N -r 938020864-1266877568 -o "9722214af0ab8aa9dffb6cfdafd937b7.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_adkwinpeaddons.iso
```
25398
```
curl -N -r 958357504-1290512426 -o "9722214af0ab8aa9dffb6cfdafd937b7.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_adkwinpeaddons.iso
```
26100
```
curl -N -r 987963392-1322470965 -o "9722214af0ab8aa9dffb6cfdafd937b7.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_adkwinpeaddons.iso
```
```
7z e 9722214af0ab8aa9dffb6cfdafd937b7.cab filacfdff6b0ca55226d12bdcb8583fe7f7 filb8eaee8243f0d40642def467974eb651
ren filacfdff6b0ca55226d12bdcb8583fe7f7 WinPE-NetFx.cab
ren filb8eaee8243f0d40642def467974eb651 WinPE-WMI.cab
```
17763
```
curl -N -r 5499510784-5499524352 -o "WinPE-ATBroker_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5499525120-5499545385 -o "WinPE-AppxPackaging_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5499545600-5499584593 -o "WinPE-AudioCore_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5499586560-5499615366 -o "WinPE-AudioDrivers_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5499617280-5499631129 -o "WinPE-DismCmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5499631616-5499755466 -o "WinPE-Dot3Svc_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5499756544-5499770459 -o "WinPE-EnhancedStorage_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5499770880-5500454822 -o "WinPE-HTA_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5500454912-5500503519 -o "WinPE-LegacySetup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5500504064-5500944031 -o "WinPE-MDAC_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5500944384-5500961006 -o "WinPE-Narrator_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5500962816-5508162126 -o "WinPE-NetFx_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5508163584-5508175010 -o "WinPE-OpcServices_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5508175872-5508207807 -o "WinPE-PPPoE_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5508208640-5508228304 -o "WinPE-PlatformId_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5508229120-5508441021 -o "WinPE-PowerShell_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5508442112-5508453307 -o "WinPE-RNDIS_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5508454400-5508472170 -o "WinPE-Rejuv_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5508472832-5508536274 -o "WinPE-SRH_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5508536320-5508712224 -o "WinPE-SRT_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5508712448-5508742285 -o "WinPE-Scripting_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5508743168-5508756163 -o "WinPE-SecureBootCmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5508757504-5508806023 -o "WinPE-SecureStartup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5508806656-5508815932 -o "WinPE-Setup-Client_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5508816896-5508826172 -o "WinPE-Setup-Server_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5508827136-5508988948 -o "WinPE-Setup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5508990976-5509008152 -o "WinPE-Speech-TTS_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5509009408-5509137900 -o "WinPE-StorageWMI_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5509138432-5509167968 -o "WinPE-WDS-Tools_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5509169152-5509676038 -o "WinPE-WMI_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5509677056-5509788286 -o "WinPE-WiFi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5509789696-5509806190 -o "WinPE-WinReCfg_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5509808128-5513844454 -o "lp.cab" https://software-static.download.prss.microsoft.com/dbazure/17763.1.180914-1434.rs5_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
```
18362
```
curl -N -r 5588578304-5592484844 -o "lp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5592485888-5592502593 -o "winpe-appxpackaging_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5592504320-5592512602 -o "winpe-atbroker_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5592514560-5592550315 -o "winpe-audiocore_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5592551424-5592575520 -o "winpe-audiodrivers_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5592576000-5592587535 -o "winpe-dismcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5592588288-5592711434 -o "winpe-dot3svc_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5592713216-5592724349 -o "winpe-enhancedstorage_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5592725504-5592742057 -o "winpe-gamingperipherals_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5592743936-5593419698 -o "winpe-hta_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5593419776-5593463051 -o "winpe-legacysetup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5593464832-5593900583 -o "winpe-mdac_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5593901056-5593914830 -o "winpe-narrator_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5593915392-5601478070 -o "winpe-netfx_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5601478656-5601486908 -o "winpe-opcservices_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5601488896-5601504596 -o "winpe-platformid_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5601505280-5601689993 -o "winpe-powershell_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5601691648-5601719765 -o "winpe-pppoe_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5601720320-5601735016 -o "winpe-rejuv_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5601736704-5601744829 -o "winpe-rndis_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5601744896-5601771085 -o "winpe-scripting_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5601771520-5601781821 -o "winpe-securebootcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5601783808-5601832117 -o "winpe-securestartup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5601832960-5601839260 -o "winpe-setup-client_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5601841152-5601847606 -o "winpe-setup-server_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5601849344-5602007914 -o "winpe-setup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5602009088-5602023764 -o "winpe-speech-tts_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5602025472-5602083758 -o "winpe-srh_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5602084864-5602257040 -o "winpe-srt_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5602258944-5602387096 -o "winpe-storagewmi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5602387968-5602417124 -o "winpe-wds-tools_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5602418688-5602529532 -o "winpe-wifi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5602531328-5602547794 -o "winpe-winrecfg_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5602549760-5603047720 -o "winpe-wmi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/18362.1.190318-1202.19h1_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
```
19041
```
curl -N -r 5460205568-5463958744 -o "lp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5463959552-5463977657 -o "winpe-appxpackaging_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5463977984-5463986352 -o "winpe-atbroker_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5463988224-5464026290 -o "winpe-audiocore_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5464027136-5464048630 -o "winpe-audiodrivers_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5464049664-5464061361 -o "winpe-dismcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5464061952-5464182160 -o "winpe-dot3svc_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5464182784-5464193761 -o "winpe-enhancedstorage_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5464195072-5464210503 -o "winpe-gamingperipherals_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5464211456-5464886012 -o "winpe-hta_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5464887296-5464933487 -o "winpe-legacysetup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5464934400-5465372167 -o "winpe-mdac_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5465372672-5465385570 -o "winpe-narrator_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5465387008-5469505909 -o "winpe-netfx_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5469507584-5469515832 -o "winpe-opcservices_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5469517824-5469536237 -o "winpe-platformid_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5469536256-5469545850 -o "winpe-pmemcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5469546496-5469731451 -o "winpe-powershell_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5469732864-5469761643 -o "winpe-pppoe_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5469763584-5469778572 -o "winpe-rejuv_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5469779968-5469788249 -o "winpe-rndis_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5469790208-5469817521 -o "winpe-scripting_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5469818880-5469829179 -o "winpe-securebootcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5469831168-5469879503 -o "winpe-securestartup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5469880320-5469886624 -o "winpe-setup-client_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5469888512-5469894818 -o "winpe-setup-server_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5469896704-5470058608 -o "winpe-setup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5470060544-5470075322 -o "winpe-speech-tts_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5470076928-5470136708 -o "winpe-srh_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5470138368-5470308731 -o "winpe-srt_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5470310400-5470439184 -o "winpe-storagewmi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5470439424-5470468416 -o "winpe-wds-tools_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5470470144-5470580898 -o "winpe-wifi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5470582784-5470599542 -o "winpe-winrecfg_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
curl -N -r 5470601216-5471106832 -o "winpe-wmi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/19041.1.191206-1406.vb_release_CLIENTLANGPACKDVD_OEM_MULTI.iso
```
20348
```
curl -N -r 5915379712-5919219393 -o "lp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5919219712-5919238123 -o "winpe-appxpackaging_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5919238144-5919246444 -o "winpe-atbroker_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5919248384-5919285172 -o "winpe-audiocore_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5919285248-5919305432 -o "winpe-audiodrivers_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5919305728-5919348080 -o "winpe-azmos_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5919348736-5919360423 -o "winpe-dismcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5919361024-5919479510 -o "winpe-dot3svc_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5919479808-5919490811 -o "winpe-enhancedstorage_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5919492096-5919508373 -o "winpe-gamingperipherals_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5919508480-5919997552 -o "winpe-hta_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5919997952-5920040407 -o "winpe-legacysetup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5920040960-5920477017 -o "winpe-mdac_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5920477184-5920490936 -o "winpe-narrator_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5920491520-5924638169 -o "winpe-netfx_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5924638720-5924646918 -o "winpe-opcservices_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5924648960-5924667495 -o "winpe-platformid_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5924669440-5924679642 -o "winpe-pmemcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5924679680-5924864885 -o "winpe-powershell_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5924866048-5924894813 -o "winpe-pppoe_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5924896768-5924910604 -o "winpe-rejuv_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5924911104-5924919233 -o "winpe-rndis_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5924919296-5924946059 -o "winpe-scripting_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5924947968-5924958265 -o "winpe-securebootcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5924960256-5925008779 -o "winpe-securestartup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5925009408-5925015720 -o "winpe-setup-client_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5925017600-5925023914 -o "winpe-setup-server_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5925025792-5925179194 -o "winpe-setup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5925179392-5925193818 -o "winpe-speech-tts_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5925195776-5925253996 -o "winpe-srh_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5925255168-5925420650 -o "winpe-srt_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5925421056-5925549966 -o "winpe-storagewmi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5925550080-5925581102 -o "winpe-wds-tools_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5925582848-5925692656 -o "winpe-wifi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5925693440-5925709908 -o "winpe-winrecfg_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 5925711872-5926214240 -o "winpe-wmi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/20348.1.210507-1500.fe_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
```
22000
```
curl -N -r 7494184960-7498064668 -o "lp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7498065920-7498084533 -o "winpe-appxpackaging_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7498086400-7498094768 -o "winpe-atbroker_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7498096640-7498133822 -o "winpe-audiocore_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7498135552-7498157930 -o "winpe-audiodrivers_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7498158080-7498200446 -o "winpe-azmos_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7498201088-7498212767 -o "winpe-dismcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7498213376-7498333624 -o "winpe-dot3svc_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7498334208-7498345199 -o "winpe-enhancedstorage_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7498346496-7498361907 -o "winpe-gamingperipherals_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7498362880-7498852066 -o "winpe-hta_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7498852352-7498894439 -o "winpe-legacysetup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7498895360-7499332787 -o "winpe-mdac_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7499333632-7499345688 -o "winpe-narrator_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7499345920-7503491465 -o "winpe-netfx_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7503493120-7503501318 -o "winpe-opcservices_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7503503360-7503522193 -o "winpe-platformid_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7503523840-7503533960 -o "winpe-pmemcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7503534080-7503719231 -o "winpe-powershell_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7503720448-7503749285 -o "winpe-pppoe_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7503751168-7503765042 -o "winpe-rejuv_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7503765504-7503773647 -o "winpe-rndis_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7503773696-7503790868 -o "winpe-sample-oc_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7503792128-7503819013 -o "winpe-scripting_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7503820800-7503831103 -o "winpe-securebootcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7503833088-7503881601 -o "winpe-securestartup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7503882240-7503888538 -o "winpe-setup-client_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7503890432-7503896742 -o "winpe-setup-server_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7503898624-7504053035 -o "winpe-setup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7504054272-7504068794 -o "winpe-speech-tts_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7504070656-7504128484 -o "winpe-srh_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7504130048-7504296968 -o "winpe-srt_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7504297984-7504427848 -o "winpe-storagewmi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7504429056-7504459128 -o "winpe-wds-tools_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7504459776-7504571860 -o "winpe-wifi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7504572416-7504588870 -o "winpe-winrecfg_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7504590848-7505094882 -o "winpe-wmi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/22000.1.210604-1628.co_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
```
22621
```
curl -N -r 7022931968-7026913867 -o "lp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7026915328-7027251001 -o "winpe-appxdeployment_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7027251200-7027272655 -o "winpe-appxpackaging_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7027273728-7027283992 -o "winpe-atbroker_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7027286016-7027326464 -o "winpe-audiocore_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7027326976-7027351580 -o "winpe-audiodrivers_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7027353600-7027456658 -o "winpe-azmos_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7027458048-7027470833 -o "winpe-dismcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7027472384-7027595608 -o "winpe-dot3svc_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7027597312-7027609477 -o "winpe-enhancedstorage_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7027609600-7027628517 -o "winpe-gamingperipherals_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7027630080-7028128792 -o "winpe-hta_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7028129792-7028180399 -o "winpe-legacysetup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7028180992-7028622833 -o "winpe-mdac_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7028623360-7028639018 -o "winpe-narrator_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7028639744-7032633317 -o "winpe-netfx_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7032633344-7032643518 -o "winpe-opcservices_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7032643584-7032664573 -o "winpe-platformid_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7032666112-7032677336 -o "winpe-pmemcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7032678400-7032864715 -o "winpe-powershell_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7032864768-7032895453 -o "winpe-pppoe_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7032895488-7032913628 -o "winpe-rejuv_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7032913920-7032923147 -o "winpe-rndis_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7032924160-7032942884 -o "winpe-sample-oc_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7032944640-7032976908 -o "winpe-scripting_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7032977408-7032988819 -o "winpe-securebootcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7032989696-7033040193 -o "winpe-securestartup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7033040896-7033048288 -o "winpe-setup-asz_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7033049088-7033056480 -o "winpe-setup-client_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7033057280-7033064656 -o "winpe-setup-server_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7033065472-7033189269 -o "winpe-setup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7033190400-7033207466 -o "winpe-speech-tts_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7033208832-7033268866 -o "winpe-srh_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7033270272-7033444854 -o "winpe-srt_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7033446400-7033577796 -o "winpe-storagewmi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7033579520-7033612464 -o "winpe-wds-tools_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7033614336-7033731398 -o "winpe-wifi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7033733120-7033806196 -o "winpe-windowsupdate_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7033806848-7033824586 -o "winpe-winrecfg_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
curl -N -r 7033825280-7034333560 -o "winpe-wmi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/988969d5-f34g-4e03-ac9d-1f9786c66749/22621.1.220506-1250.ni_release_amd64fre_CLIENT_LOF_PACKAGES_OEM.iso
```
25398
```
curl -N -r 6631835648-6635887582 -o "lp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6635888640-6635936013 -o "winpe-appxdeployment_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6635937792-6635959323 -o "winpe-appxpackaging_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6635960320-6635971090 -o "winpe-atbroker_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6635972608-6636013770 -o "winpe-audiocore_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6636015616-6636040242 -o "winpe-audiodrivers_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6636042240-6636055097 -o "winpe-dismcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6636056576-6636182162 -o "winpe-dot3svc_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6636183552-6636195801 -o "winpe-enhancedstorage_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6636195840-6636214727 -o "winpe-gamingperipherals_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6636216320-6636713198 -o "winpe-hta_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6636713984-6636764631 -o "winpe-legacysetup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6636765184-6637205799 -o "winpe-mdac_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6637207552-6637222592 -o "winpe-narrator_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6637223936-6641223505 -o "winpe-netfx_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641223680-6641232378 -o "winpe-opcservices_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641233920-6641255605 -o "winpe-platformid_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641256448-6641267726 -o "winpe-pmemcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641268736-6641455253 -o "winpe-powershell_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641457152-6641488563 -o "winpe-pppoe_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641489920-6641506536 -o "winpe-rejuv_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641508352-6641517575 -o "winpe-rndis_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641518592-6641538756 -o "winpe-sample-oc_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641539072-6641570036 -o "winpe-scripting_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641571840-6641583297 -o "winpe-securebootcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641584128-6641635545 -o "winpe-securestartup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641637376-6641684023 -o "winpe-setup-asz_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641684480-6641731187 -o "winpe-setup-client_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641731584-6641778491 -o "winpe-setup-server_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641778688-6641901397 -o "winpe-setup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641901568-6641918626 -o "winpe-speech-tts_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641920000-6641981388 -o "winpe-srh_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6641981440-6642156847 -o "winpe-srt_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6642157568-6642291490 -o "winpe-storagewmi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6642292736-6642325650 -o "winpe-wds-tools_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6642327552-6642444736 -o "winpe-wifi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6642446336-6642530046 -o "winpe-windowsupdate_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6642530304-6642548046 -o "winpe-winrecfg_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6642548736-6643059030 -o "winpe-wmi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6643060736-6643071524 -o "winpe-wow-support_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/25398.1.230610-1204.zn_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
```
26100
```
curl -N -r 6680068096-6684331029 -o "lp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6684332032-6684379293 -o "winpe-appxdeployment_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6684381184-6684402363 -o "winpe-appxpackaging_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6684403712-6684410649 -o "winpe-arm64ec-support_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6684411904-6684422648 -o "winpe-atbroker_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6684424192-6684465952 -o "winpe-audiocore_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6684467200-6684496816 -o "winpe-audiodrivers_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6684497920-6684517693 -o "winpe-connectivity_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6684518400-6684531229 -o "winpe-dismcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6684532736-6684654390 -o "winpe-dot3svc_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6684655616-6684667971 -o "winpe-enhancedstorage_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6684669952-6684688999 -o "winpe-gamingperipherals_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6684690432-6685188726 -o "winpe-hta_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6685190144-6685239231 -o "winpe-legacysetup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6685239296-6685685983 -o "winpe-mdac_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6685687808-6685703686 -o "winpe-narrator_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6685704192-6689704161 -o "winpe-netfx_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6689705984-6689716278 -o "winpe-opcservices_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6689718272-6689740045 -o "winpe-platformid_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6689740800-6689752178 -o "winpe-pmemcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6689753088-6689939821 -o "winpe-powershell_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6689941504-6689972221 -o "winpe-pppoe_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6689972224-6689990508 -o "winpe-rejuv_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6689990656-6689999845 -o "winpe-rndis_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6690000896-6690021122 -o "winpe-sample-oc_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6690021376-6690053772 -o "winpe-scripting_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6690054144-6690065721 -o "winpe-securebootcmdlets_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6690066432-6690118017 -o "winpe-securestartup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6690119680-6690166291 -o "winpe-setup-asz_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6690166784-6690213557 -o "winpe-setup-client_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6690213888-6690260915 -o "winpe-setup-server_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6690260992-6690387629 -o "winpe-setup_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6690387968-6690404970 -o "winpe-speech-tts_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6690406400-6690465962 -o "winpe-srh_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6690467840-6690641881 -o "winpe-srt_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6690641920-6690776764 -o "winpe-storagewmi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6690777088-6690810836 -o "winpe-wds-tools_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6690811904-6690930512 -o "winpe-wifi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6690930688-6691015006 -o "winpe-windowsupdate_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6691016704-6691034436 -o "winpe-winrecfg_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
curl -N -r 6691035136-6691546516 -o "winpe-wmi_ja-jp.cab" https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26100.1.240331-1435.ge_release_amd64fre_SERVER_LOF_PACKAGES_OEM.iso
```
---

汎用性の高いWindows PE 5.0 (x64)メディアの作り方

[https://idinor.hatenablog.com/entry/20140224/1393249489](https://idinor.hatenablog.com/entry/20140224/1393249489)

Windows 10 用の Windows PE (WinPE) のUSBメモリセットアップ例

[https://qiita.com/msakamoto_sf/items/3fff0e7c68e6aaf1a60e](https://qiita.com/msakamoto_sf/items/3fff0e7c68e6aaf1a60e)
```
Dism /Add-Package /Image:"C:\WinPE_amd64\mount" /PackagePath:"C:\Program Files (x86)\Windows Kits\10\Assessment and Deployment Kit\Windows Preinstallation Environment\amd64\WinPE_OCs\WinPE-WMI.cab"

Dism /Add-Package /Image:"C:\WinPE_amd64\mount" /PackagePath:"C:\Program Files (x86)\Windows Kits\10\Assessment and Deployment Kit\Windows Preinstallation Environment\amd64\WinPE_OCs\ja-jp\WinPE-WMI_ja-jp.cab"

Dism /Add-Package /Image:"C:\WinPE_amd64\mount" /PackagePath:"C:\Program Files (x86)\Windows Kits\10\Assessment and Deployment Kit\Windows Preinstallation Environment\amd64\WinPE_OCs\WinPE-NetFx.cab"

Dism /Add-Package /Image:"C:\WinPE_amd64\mount" /PackagePath:"C:\Program Files (x86)\Windows Kits\10\Assessment and Deployment Kit\Windows Preinstallation Environment\amd64\WinPE_OCs\ja-jp\WinPE-NetFx_ja-jp.cab"
```
WinPE オプション コンポーネント (OC) リファレンス

Microsoft .NET/WinPE-NetFx

[https://learn.microsoft.com/ja-jp/windows-hardware/manufacture/desktop/winpe-add-packages--optional-components-reference#10](https://learn.microsoft.com/ja-jp/windows-hardware/manufacture/desktop/winpe-add-packages--optional-components-reference#10)

NegativeScreen

[https://zerowidthjoiner.net/negativescreen](https://zerowidthjoiner.net/negativescreen)

[https://github.com/mlaily/NegativeScreen/releases/download/Release_2.6.1/Binary.zip](https://github.com/mlaily/NegativeScreen/releases/download/Release_2.6.1/Binary.zip)
