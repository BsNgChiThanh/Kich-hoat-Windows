# Active Windows7 #


## KÍCH HOẠT BẰNG TOOLS ##

- [Active AIO Tools V3.1.3](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_onmicrosoft_com/ETBqT5RRi4xEjUTNR_VaUsUBqsAgTjyDFD7BA-sVJ1XC4A?e=Q0vzhG)
- [Windows loader](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_onmicrosoft_com/EQHo1e7zEKRIvWuBR0leGrUBI5TgEpw9JAUl639-ghRjrw?e=AS7sDZ) pass giải nén: congdongbatdongsan

## KÍCH HOẠT BẰNG CMD ##

**[Xem video](https://youtu.be/Vt4o5XCoWAs)**

Mở NotePad lên và copy đoạn mã bên dưới, bấm **Save As** đặt tên là **kichhoatwin7.cmd** sau đó chạy file này dưới quyền **Run Administrator**

```php
@echo off
title Activate Windows 7 Professional/Enterprise for FREE!&cls&echo ============================================================================&echo #Project: Activating Microsoft software products for FREE without software&echo ============================================================================&echo.&echo #Supported products:&echo - Windows 7 Professional&echo - Windows 7 Professional N&echo - Windows 7 Professional E&echo - Windows 7 Enterprise&echo - Windows 7 Enterprise N&echo - Windows 7 Enterprise E&echo.&echo.&echo ============================================================================&echo Activating your Windows...&cd /d %windir%\system32&cscript //nologo slmgr.vbs /upk >nul&cscript //nologo slmgr.vbs /cpky >nul&set i=1&wmic os | findstr /I "enterprise" >nul
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk 33PXH-7Y6KF-2VJC9-XBBR8-HVTHH >nul&cscript //nologo slmgr.vbs /ipk YDRBP-3D83W-TY26F-D46B2-XCKRJ >nul&cscript //nologo slmgr.vbs /ipk C29WB-22CC8-VJ326-GHFJW-H9DH4 >nul&goto server) else (cscript //nologo slmgr.vbs /ipk FJ82H-XT6CR-J8D7P-XQJJ2-GPDD4 >nul&cscript //nologo slmgr.vbs /ipk MRPKT-YTG23-K7D7T-X2JMM-QY7MG >nul&cscript //nologo slmgr.vbs /ipk W82YF-2Q76Y-63HXB-FGJG9-GF7QX >nul)
:server
if %i%==1 set KMS_Sev=kms7.MSGuides.com
if %i%==2 set KMS_Sev=s8.uk.to
if %i%==3 set KMS_Sev=s9.uk.to
if %i%==4 goto unsupported
cscript //nologo slmgr.vbs /skms %KMS_Sev%:1688 >nul&echo ============================================================================&echo.&echo.
cscript //nologo slmgr.vbs /ato | find /i "successfully" && (echo.&echo ============================================================================&echo.&echo #My official blog: MSGuides.com&echo.&echo #How it works: bit.ly/kms-server&echo.&echo #Please feel free to contact me at msguides.com@gmail.com if you have any questions or concerns.&echo.&echo #Please consider supporting this project: donate.msguides.com&echo #Your support is helping me keep my servers running everyday!&echo.&echo ============================================================================&choice /n /c YN /m "Would you like to visit my blog [Y,N]?" & if errorlevel 2 exit) || (echo The connection to my KMS server failed! Trying to connect to another one... & echo Please wait... & echo. & echo. & set /a i+=1 & goto server)
explorer "http://MSGuides.com"&goto halt
:unsupported
echo ============================================================================&echo.&echo Sorry! Your version is not supported.&echo.
:halt
pause >nul
```

**Hoặc download đoạn mã từ file này: [MAS_1.5_AIO_CRC32_21D20776.txt](https://github.com/BsNgChiThanh/Active-Windows/files/8714396/MAS_1.5_AIO_CRC32_21D20776.txt)**

**[Hoặc download từ KMS AIO Github](https://github.com/abbodi1406/KMS_VL_ALL_AIO)** file **[KMS Update]( https://bsthanh-my.sharepoint.com/:f:/g/personal/0914678254_bsthanh_onmicrosoft_com/ErBkofQz8FZLkC0q8Ywiaz4BmCYcC1Y2-1SbqNVshjfmyA?e=3u81dK)**

## KÍCH HOẠT MỌI WINDOWS ##

Mở NotePad lên và copy đoạn mã bên dưới, bấm **Save As** đặt tên là **kichhoatmoiwindows.cmd** sau đó chạy file này dưới quyền **Run Administrator**

```php
@echo off
title Activate Windows Server (ALL versions) for FREE - MSGuides.com&cls&echo =====================================================================================&echo #Project: Activating Microsoft software products for FREE without additional software&echo =====================================================================================&echo.&echo #Supported products:&echo http://bit.ly/kmsclientkeys&echo.&echo.&echo ============================================================================&echo Activating your Windows...&set i=1
cscript //nologo slmgr.vbs /ipk 4DWFP-JF3DJ-B7DTH-78FJB-PDRHK >nul||cscript //nologo slmgr.vbs /ipk 22XQ2-VRXRG-P8D42-K34TD-G3QQC >nul||cscript //nologo slmgr.vbs /ipk 7M67G-PC374-GR742-YH8V4-TCBY3 >nul||cscript //nologo slmgr.vbs /ipk RCTX3-KWVHP-BR6TB-RB6DM-6X7HP >nul||cscript //nologo slmgr.vbs /ipk 39BXF-X8Q23-P2WWT-38T2F-G3FPG >nul||cscript //nologo slmgr.vbs /ipk YQGMW-MPWTJ-34KDK-48M3W-X4Q6V >nul||cscript //nologo slmgr.vbs /ipk W7VD6-7JFBR-RX26B-YKQ3Y-6FFFJ >nul||cscript //nologo slmgr.vbs /ipk TM24T-X9RMF-VWXK6-X8JC9-BFGM2 >nul||cscript //nologo slmgr.vbs /ipk WYR28-R7TFJ-3X2YQ-YCY4H-M249D >nul||cscript //nologo slmgr.vbs /ipk GT63C-RJFQ3-4GMB6-BRFB9-CB83V >nul||cscript //nologo slmgr.vbs /ipk 74YFP-3QFB3-KQT8W-PMXWJ-7M648 >nul||cscript //nologo slmgr.vbs /ipk 489J6-VHDMP-X63PK-3K798-CPX3Y >nul||cscript //nologo slmgr.vbs /ipk YC6KT-GKW9T-YTKYR-T4X34-R7VHC >nul||cscript //nologo slmgr.vbs /ipk TT8MH-CG224-D3D7Q-498W2-9QCTX >nul||cscript //nologo slmgr.vbs /ipk 6TPJF-RBVHG-WBW2R-86QPH-6RTM4 >nul||cscript //nologo slmgr.vbs /ipk 48HP8-DN98B-MYWDG-T2DCC-8W83P >nul||cscript //nologo slmgr.vbs /ipk XNH6W-2V9GX-RGJ4K-Y8X6F-QGJ2G >nul||cscript //nologo slmgr.vbs /ipk HM7DN-YVMH3-46JC3-XYTG7-CYQJJ >nul||cscript //nologo slmgr.vbs /ipk XC9B7-NBPP2-83J2H-RHMBY-92BT4 >nul||cscript //nologo slmgr.vbs /ipk 4K36P-JN4VD-GDC6V-KDT89-DYFKP >nul||cscript //nologo slmgr.vbs /ipk 2WN2H-YGCQR-KFX6K-CD6TF-84YXQ >nul||cscript //nologo slmgr.vbs /ipk 8N2M2-HWPGY-7PGT9-HGDD8-GVGGY >nul||cscript //nologo slmgr.vbs /ipk BN3D2-R7TKB-3YPBD-8DRP2-27GG4 >nul||cscript //nologo slmgr.vbs /ipk KNC87-3J2TX-XB4WP-VCPJV-M4FWM >nul||cscript //nologo slmgr.vbs /ipk W3GGN-FT8W3-Y4M27-J84CP-Q3VJ9 >nul||cscript //nologo slmgr.vbs /ipk D2N9P-3P6X9-2R39C-7RTCD-MDVJX >nul||cscript //nologo slmgr.vbs /ipk JCKRF-N37P4-C2D82-9YXRT-4M63B >nul||cscript //nologo slmgr.vbs /ipk WC2BQ-8NRM3-FDDYY-2BFGV-KHKQY >nul||cscript //nologo slmgr.vbs /ipk CB7KF-BWN84-R7R2Y-793K2-8XDDG >nul||cscript //nologo slmgr.vbs /ipk WVDHN-86M7X-466P6-VHXV7-YY726 >nul||cscript //nologo slmgr.vbs /ipk N69G4-B89J2-4G8F4-WWYCC-J464C >nul||cscript //nologo slmgr.vbs /ipk WMDGN-G9PQG-XVVXX-R3X43-63DFG >nul||cscript //nologo slmgr.vbs /ipk DPCNP-XQFKJ-BJF7R-FRC8D-GF6G4 >nul||cscript //nologo slmgr.vbs /ipk 6Y6KB-N82V8-D8CQV-23MJW-BWTG6 >nul||cscript //nologo slmgr.vbs /ipk PTXN8-JFHJM-4WC78-MPCBR-9W4KR >nul||cscript //nologo slmgr.vbs /ipk 2HXDN-KRXHB-GPYC7-YCKFJ-7FVDG >nul||cscript //nologo slmgr.vbs /ipk N2KJX-J94YW-TQVFB-DG9YT-724CC >nul||cscript //nologo slmgr.vbs /ipk 6NMRW-2C8FM-D24W7-TQWMY-CWH2D >nul||cscript //nologo slmgr.vbs /ipk WX4NM-KYWYW-QJJR4-XV3QB-6VM33 >nul||cscript //nologo slmgr.vbs /ipk VDYBN-27WPP-V4HQT-9VMD4-VMK7H >nul||goto notsupported
:skms
if %i% GTR 10 goto busy
if %i% EQU 1 set KMS=kms7.MSGuides.com
if %i% EQU 2 set KMS=kms8.MSGuides.com
if %i% EQU 3 set KMS=kms9.MSGuides.com
if %i% GTR 3 goto ato
cscript //nologo slmgr.vbs /skms %KMS%:1688 >nul
:ato
echo ============================================================================&echo.&echo.&cscript //nologo slmgr.vbs /ato | find /i "successfully" && (echo.&echo ============================================================================&echo.&echo #My official blog: MSGuides.com&echo.&echo #How it works: bit.ly/kms-server&echo.&echo #Please feel free to contact me at msguides.com@gmail.com if you have any questions or concerns.&echo.&echo #Please consider supporting this project: donate.msguides.com&echo #Your support is helping me keep my servers running 24/7!&echo.&echo ============================================================================&choice /n /c YN /m "Would you like to visit my blog [Y,N]?" & if errorlevel 2 exit) || (echo The connection to my KMS server failed! Trying to connect to another one... & echo Please wait... & echo. & echo. & set /a i+=1 & goto skms)
explorer "http://MSGuides.com"&goto halt
:notsupported
echo ============================================================================&echo.&echo Sorry, your version is not supported.&echo.&goto halt
:busy
echo ============================================================================&echo.&echo Sorry, the server is busy and can't respond to your request. Please try again.&echo.
:halt
pause >nul
```

# Windows8-8.1 #

## KÍCH HOẠT BẰNG TOOLS ##

- [Active AIO Tools V3.1.3](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_onmicrosoft_com/ETBqT5RRi4xEjUTNR_VaUsUBqsAgTjyDFD7BA-sVJ1XC4A?e=Q0vzhG)
**[Hoặc download từ KMS AIO Github](https://github.com/abbodi1406/KMS_VL_ALL_AIO)** file **[KMS]( https://bsthanh-my.sharepoint.com/:f:/g/personal/0914678254_bsthanh_onmicrosoft_com/ErBkofQz8FZLkC0q8Ywiaz4BmCYcC1Y2-1SbqNVshjfmyA?e=3u81dK)**
- **[MAS UPDATE](https://bsthanh-my.sharepoint.com/:f:/g/personal/0914678254_bsthanh_onmicrosoft_com/EheHriQtZjtIkSbJQ8QrqDEBtgd1f98p5bMeSNNXSlkCNw?e=pxjf5Y)**

## KÍCH HOẠT BẰNG CMD ##

Mở NotePad lên và copy đoạn mã bên dưới, bấm **Save As** đặt tên là **kichhoatwin8_81.cmd** sau đó chạy file này dưới quyền **Run Administrator**

```php
@echo off
title Activate Windows 8 / Windows 8.1 ALL versions for FREE - MSGuides.com&cls&echo =====================================================================================&echo #Project: Activating Microsoft software products for FREE without additional software&echo =====================================================================================&echo.&echo #Supported products:&echo - Windows 8 Core&echo - Windows 8 Core Single Language&echo - Windows 8 Professional&echo - Windows 8 Professional N&echo - Windows 8 Professional WMC&echo - Windows 8 Enterprise&echo - Windows 8 Enterprise N&echo - Windows 8.1 Core&echo - Windows 8.1 Core N&echo - Windows 8.1 Core Single Language&echo - Windows 8.1 Professional&echo - Windows 8.1 Professional N&echo - Windows 8.1 Professional WMC&echo - Windows 8.1 Enterprise&echo - Windows 8.1 Enterprise N&echo.&echo.&echo ============================================================================&echo Activating your Windows...&cscript //nologo slmgr.vbs /ckms >nul&cscript //nologo slmgr.vbs /upk >nul&cscript //nologo slmgr.vbs /cpky >nul&set i=1&wmic os | findstr /I "enterprise" >nul
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk MHF9N-XY6XB-WVXMC-BTDCT-MKKG7 >nul||cscript //nologo slmgr.vbs /ipk TT4HM-HN7YT-62K67-RGRQJ-JFFXW >nul||cscript //nologo slmgr.vbs /ipk 32JNW-9KQ84-P47T8-D8GGY-CWCK7 >nul||cscript //nologo slmgr.vbs /ipk JMNMF-RHW7P-DMY6X-RF3DR-X2BQT >nul&goto skms) else (cscript //nologo slmgr.vbs /ipk GCRJD-8NW9H-F2CDX-CCM8D-9D6T9 >nul||cscript //nologo slmgr.vbs /ipk HMCNV-VVBFX-7HMBH-CTY9B-B4FXY >nul||cscript //nologo slmgr.vbs /ipk NG4HW-VH26C-733KW-K6F98-J8CK4 >nul||cscript //nologo slmgr.vbs /ipk XCVCF-2NXM9-723PB-MHCB7-2RYQQ >nul||cscript //nologo slmgr.vbs /ipk GNBB8-YVD74-QJHX6-27H4K-8QHDG >nul||cscript //nologo slmgr.vbs /ipk M9Q9P-WNJJT-6PXPY-DWX8H-6XWKK >nul||cscript //nologo slmgr.vbs /ipk 7B9N3-D94CG-YTVHR-QBPX3-RJP64 >nul||cscript //nologo slmgr.vbs /ipk BB6NG-PQ82V-VRDPW-8XVD2-V8P66 >nul||cscript //nologo slmgr.vbs /ipk 789NJ-TQK6T-6XTH8-J39CJ-J8D3P >nul||goto notsupported)
:skms
if %i% GTR 10 goto busy
if %i% EQU 1 set KMS=kms7.MSGuides.com
if %i% EQU 2 set KMS=s8.uk.to
if %i% EQU 3 set KMS=s9.us.to
if %i% GTR 3 goto ato
cscript //nologo slmgr.vbs /skms %KMS%:1688 >nul
:ato
echo ============================================================================&echo.&echo.&cscript //nologo slmgr.vbs /ato | find /i "successfully" && (echo.&echo ============================================================================&echo.&echo #My official blog: MSGuides.com&echo.&echo #How it works: bit.ly/kms-server&echo.&echo #Please feel free to contact me at msguides.com@gmail.com if you have any questions or concerns.&echo.&echo #Please consider supporting this project: donate.msguides.com&echo #Your support is helping me keep my servers running 24/7!&echo.&echo ============================================================================&choice /n /c YN /m "Would you like to visit my blog [Y,N]?" & if errorlevel 2 exit) || (echo The connection to my KMS server failed! Trying to connect to another one... & echo Please wait... & echo. & echo. & set /a i+=1 & goto skms)
explorer "http://MSGuides.com"&goto halt
:notsupported
echo ============================================================================&echo.&echo Sorry, your version is not supported.&echo.
:busy
echo ============================================================================&echo.&echo Sorry, the server is busy and can't respond to your request. Please try again.&echo.
:halt
pause >nul
```

# Windows10 #

## KÍCH HOẠT BẰNG TOOLS ##

- [Active AIO Tools V3.1.3](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_onmicrosoft_com/ETBqT5RRi4xEjUTNR_VaUsUBqsAgTjyDFD7BA-sVJ1XC4A?e=Q0vzhG)
- [Windows loader](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_onmicrosoft_com/EQHo1e7zEKRIvWuBR0leGrUBI5TgEpw9JAUl639-ghRjrw?e=AS7sDZ) pass giải nén: congdongbatdongsan
- [Hoặc download từ KMS AIO Github](https://github.com/abbodi1406/KMS_VL_ALL_AIO)** file [KMS]( https://bsthanh-my.sharepoint.com/:f:/g/personal/0914678254_bsthanh_onmicrosoft_com/ErBkofQz8FZLkC0q8Ywiaz4BmCYcC1Y2-1SbqNVshjfmyA?e=3u81dK) 
- [Update W10 Digital License Activation Script]([https://1drv.ms/u/s!AkwSBX-xWiVhiUaSUP5VaBEpk6Vn?e=jRjvDB](https://bsthanh-my.sharepoint.com/:f:/g/personal/0914678254_bsthanh_onmicrosoft_com/EhrqZ8oy0R9AuqU4Se-8xfEBjfIaVFBZAplCibUrODNcGg?e=sivQij)

## KÍCH HOẠT BẰNG CMD ##

Mở NotePad lên và copy đoạn mã bên dưới, bấm **Save As** đặt tên là **kichhoatwin10.cmd** sau đó chạy file này dưới quyền **Run Administrator**

```php
@echo off
title Activate Windows 10 (ALL versions) for FREE - MSGuides.com&cls&echo =====================================================================================&echo #Project: Activating Microsoft software products for FREE without additional software&echo =====================================================================================&echo.&echo #Supported products:&echo - Windows 10 Home&echo - Windows 10 Professional&echo - Windows 10 Education&echo - Windows 10 Enterprise&echo.&echo.&echo ============================================================================&echo Activating your Windows...&cscript //nologo slmgr.vbs /ckms >nul&cscript //nologo slmgr.vbs /upk >nul&cscript //nologo slmgr.vbs /cpky >nul&set i=1&wmic os | findstr /I "enterprise" >nul
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk NPPR9-FWDCX-D2C8J-H872K-2YT43 >nul||cscript //nologo slmgr.vbs /ipk DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4 >nul||cscript //nologo slmgr.vbs /ipk YYVX9-NTFWV-6MDM3-9PT4T-4M68B >nul||cscript //nologo slmgr.vbs /ipk 44RPN-FTY23-9VTTB-MP9BX-T84FV >nul||cscript //nologo slmgr.vbs /ipk WNMTR-4C88C-JK8YV-HQ7T2-76DF9 >nul||cscript //nologo slmgr.vbs /ipk 2F77B-TNFGY-69QQF-B8YKP-D69TJ >nul||cscript //nologo slmgr.vbs /ipk DCPHK-NFMTC-H88MJ-PFHPY-QJ4BJ >nul||cscript //nologo slmgr.vbs /ipk QFFDN-GRT3P-VKWWX-X7T3R-8B639 >nul||cscript //nologo slmgr.vbs /ipk M7XTQ-FN8P6-TTKYV-9D4CC-J462D >nul||cscript //nologo slmgr.vbs /ipk 92NFX-8DJQP-P6BBQ-THF9C-7CG2H >nul&goto skms) else wmic os | findstr /I "home" >nul
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk TX9XD-98N7V-6WMQ6-BX7FG-H8Q99 >nul||cscript //nologo slmgr.vbs /ipk 3KHY7-WNT83-DGQKR-F7HPR-844BM >nul||cscript //nologo slmgr.vbs /ipk 7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH >nul||cscript //nologo slmgr.vbs /ipk PVMJN-6DFY6-9CCP6-7BKTT-D3WVR >nul&goto skms) else wmic os | findstr /I "education" >nul
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk NW6C2-QMPVW-D7KKK-3GKT6-VCFB2 >nul||cscript //nologo slmgr.vbs /ipk 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ >nul&goto skms) else wmic os | findstr /I "10 pro" >nul
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX >nul||cscript //nologo slmgr.vbs /ipk MH37W-N47XK-V7XM9-C7227-GCQG9 >nul||cscript //nologo slmgr.vbs /ipk NRG8B-VKK3Q-CXVCJ-9G2XF-6Q84J >nul||cscript //nologo slmgr.vbs /ipk 9FNHH-K3HBT-3W4TD-6383H-6XYWF >nul||cscript //nologo slmgr.vbs /ipk 6TP4R-GNPTD-KYYHQ-7B7DP-J447Y >nul||cscript //nologo slmgr.vbs /ipk YVWGF-BXNMC-HTQYQ-CPQ99-66QFC >nul&goto skms) else (goto notsupported)
:skms
if %i% GTR 10 goto busy
if %i% EQU 1 set KMS=kms7.MSGuides.com
if %i% EQU 2 set KMS=s8.uk.to
if %i% EQU 3 set KMS=s9.us.to
if %i% GTR 3 goto ato
cscript //nologo slmgr.vbs /skms %KMS%:1688 >nul
:ato
echo ============================================================================&echo.&echo.&cscript //nologo slmgr.vbs /ato | find /i "successfully" && (echo.&echo ============================================================================&echo.&echo #My official blog: MSGuides.com&echo.&echo #How it works: bit.ly/kms-server&echo.&echo #Please feel free to contact me at msguides.com@gmail.com if you have any questions or concerns.&echo.&echo #Please consider supporting this project: donate.msguides.com&echo #Your support is helping me keep my servers running 24/7!&echo.&echo ============================================================================&choice /n /c YN /m "Would you like to visit my blog [Y,N]?" & if errorlevel 2 exit) || (echo The connection to my KMS server failed! Trying to connect to another one... & echo Please wait... & echo. & echo. & set /a i+=1 & goto skms)
explorer "http://MSGuides.com"&goto halt
:notsupported
echo ============================================================================&echo.&echo Sorry, your version is not supported.&echo.&goto halt
:busy
echo ============================================================================&echo.&echo Sorry, the server is busy and can't respond to your request. Please try again.&echo.
:halt
pause >nul
```

**Hoặc:**

```php
@echo off title Activate Windows 11 (ALL versions) for FREE - MSGuides.com&cls&echo =====================================================================================&echo #Project: Activating Microsoft software products for FREE without additional software&echo =====================================================================================&echo.&echo #Supported products:&echo - Windows 11 Home&echo - Windows 11 Professional&echo - Windows 11 Education&echo - Windows 11 Enterprise&echo.&echo.&echo ============================================================================&echo Activating your Windows...&cscript //nologo slmgr.vbs /ckms >nul&cscript //nologo slmgr.vbs /upk >nul&cscript //nologo slmgr.vbs /cpky >nul&set i=1&wmic os | findstr /I "enterprise" >nul 
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk NPPR9-FWDCX-D2C8J-H872K-2YT43 >nul||cscript //nologo slmgr.vbs /ipk DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4 >nul||cscript //nologo slmgr.vbs /ipk YYVX9-NTFWV-6MDM3-9PT4T-4M68B >nul||cscript //nologo slmgr.vbs /ipk 44RPN-FTY23-9VTTB-MP9BX-T84FV >nul||cscript //nologo slmgr.vbs /ipk WNMTR-4C88C-JK8YV-HQ7T2-76DF9 >nul||cscript //nologo slmgr.vbs /ipk 2F77B-TNFGY-69QQF-B8YKP-D69TJ >nul||cscript //nologo slmgr.vbs /ipk DCPHK-NFMTC-H88MJ-PFHPY-QJ4BJ >nul||cscript //nologo slmgr.vbs /ipk QFFDN-GRT3P-VKWWX-X7T3R-8B639 >nul||cscript //nologo slmgr.vbs /ipk M7XTQ-FN8P6-TTKYV-9D4CC-J462D >nul||cscript //nologo slmgr.vbs /ipk 92NFX-8DJQP-P6BBQ-THF9C-7CG2H >nul&goto skms) else wmic os | findstr /I "home" >nul 
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk TX9XD-98N7V-6WMQ6-BX7FG-H8Q99 >nul||cscript //nologo slmgr.vbs /ipk 3KHY7-WNT83-DGQKR-F7HPR-844BM >nul||cscript //nologo slmgr.vbs /ipk 7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH >nul||cscript //nologo slmgr.vbs /ipk PVMJN-6DFY6-9CCP6-7BKTT-D3WVR >nul&goto skms) else wmic os | findstr /I "education" >nul 
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk NW6C2-QMPVW-D7KKK-3GKT6-VCFB2 >nul||cscript //nologo slmgr.vbs /ipk 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ >nul&goto skms) else wmic os | findstr /I "11 pro" >nul 
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX >nul||cscript //nologo slmgr.vbs /ipk MH37W-N47XK-V7XM9-C7227-GCQG9 >nul||cscript //nologo slmgr.vbs /ipk NRG8B-VKK3Q-CXVCJ-9G2XF-6Q84J >nul||cscript //nologo slmgr.vbs /ipk 9FNHH-K3HBT-3W4TD-6383H-6XYWF >nul||cscript //nologo slmgr.vbs /ipk 6TP4R-GNPTD-KYYHQ-7B7DP-J447Y >nul||cscript //nologo slmgr.vbs /ipk YVWGF-BXNMC-HTQYQ-CPQ99-66QFC >nul&goto skms) else (goto notsupported) 
:skms 
if %i% GTR 10 goto busy 
if %i% EQU 1 set KMS=kms7.MSGuides.com 
if %i% EQU 2 set KMS=s8.uk.to 
if %i% EQU 3 set KMS=s9.us.to 
if %i% GTR 3 goto ato 
cscript //nologo slmgr.vbs /skms %KMS%:1688 >nul 
:ato 
echo ============================================================================&echo.&echo.&cscript //nologo slmgr.vbs /ato | find /i "successfully" && (echo.&echo ============================================================================&echo.&echo #My official blog: MSGuides.com&echo.&echo #How it works: bit.ly/kms-server&echo.&echo #Please feel free to contact me at msguides.com@gmail.com if you have any questions or concerns.&echo.&echo #Please consider supporting this project: donate.msguides.com&echo #Your support is helping me keep my servers running 24/7!&echo.&echo ============================================================================&choice /n /c YN /m "Would you like to visit my blog [Y,N]?" & if errorlevel 2 exit) || (echo The connection to my KMS server failed! Trying to connect to another one... & echo Please wait... & echo. & echo. & set /a i+=1 & goto skms) 
explorer "http://MSGuides.com"&goto halt 
:notsupported 
echo ============================================================================&echo.&echo Sorry, your version is not supported.&echo.&goto halt 
:busy 
echo ============================================================================&echo.&echo Sorry, the server is busy and can't respond to your request. Please try again.&echo. 
:halt 
pause >nul
```

## XEM HẠN WINDOWS ##

Copy đoạn code sau:

```php
slmgr/xpr
```

Dán vào NotePad và Save As với tên HanWindows.cmd rồi Run nó dưới quyền Run Administrator nếu lên hình vậy là đã kích hoạt vĩnh viễn

![image](https://user-images.githubusercontent.com/103977676/202642602-3d2401ba-f9ff-47b2-8ce3-f9625a6f783b.png)

- Nếu không được vĩnh viễn tức là chỉ kích hoạt được 6 tháng, lúc này ta tạo gia hạn kích hoạt bằng **Activate AIO Tools v3.1.3**

![image](https://user-images.githubusercontent.com/103977676/202644709-e8f016c9-b755-4723-ac94-fffb44b72927.png)

- Hoặc gia hạn kích hoạt bằng **Online KMS Activation Script v6.0**

![image](https://user-images.githubusercontent.com/103977676/202645570-5d4c5903-a58a-41fe-80d2-e9811c470c68.png)

# Windows11 #

**Tất cả các Tools kích hoạt Windows 10 đều kích hoạt được Windows 11**

## KÍCH HOẠT BẰNG TOOLS ##

- [Active AIO Tools V3.1.3](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_onmicrosoft_com/ETBqT5RRi4xEjUTNR_VaUsUBqsAgTjyDFD7BA-sVJ1XC4A?e=Q0vzhG)
- [Windows loader](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_onmicrosoft_com/EQHo1e7zEKRIvWuBR0leGrUBI5TgEpw9JAUl639-ghRjrw?e=AS7sDZ) pass giải nén: congdongbatdongsan
- [Hoặc download từ KMS AIO Github](https://github.com/abbodi1406/KMS_VL_ALL_AIO) file [KMS]( https://bsthanh-my.sharepoint.com/:f:/g/personal/0914678254_bsthanh_onmicrosoft_com/ErBkofQz8FZLkC0q8Ywiaz4BmCYcC1Y2-1SbqNVshjfmyA?e=3u81dK) 
- [Update W10 Digital License Activation Script]([https://1drv.ms/u/s!AkwSBX-xWiVhiUaSUP5VaBEpk6Vn?e=jRjvDB](https://bsthanh-my.sharepoint.com/:f:/g/personal/0914678254_bsthanh_onmicrosoft_com/EhrqZ8oy0R9AuqU4Se-8xfEBjfIaVFBZAplCibUrODNcGg?e=sivQij)

## KÍCH HOẠT BẰNG CMD ##

Mở NotePad lên và copy đoạn mã bên dưới, bấm **Save As** đặt tên là **kichhoatwin11.cmd** sau đó chạy file này dưới quyền **Run Administrator**

```php
@echo off
title Activate Windows 10 (ALL versions) for FREE - MSGuides.com&cls&echo =====================================================================================&echo #Project: Activating Microsoft software products for FREE without additional software&echo =====================================================================================&echo.&echo #Supported products:&echo - Windows 10 Home&echo - Windows 10 Professional&echo - Windows 10 Education&echo - Windows 10 Enterprise&echo.&echo.&echo ============================================================================&echo Activating your Windows...&cscript //nologo slmgr.vbs /ckms >nul&cscript //nologo slmgr.vbs /upk >nul&cscript //nologo slmgr.vbs /cpky >nul&set i=1&wmic os | findstr /I "enterprise" >nul
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk NPPR9-FWDCX-D2C8J-H872K-2YT43 >nul||cscript //nologo slmgr.vbs /ipk DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4 >nul||cscript //nologo slmgr.vbs /ipk YYVX9-NTFWV-6MDM3-9PT4T-4M68B >nul||cscript //nologo slmgr.vbs /ipk 44RPN-FTY23-9VTTB-MP9BX-T84FV >nul||cscript //nologo slmgr.vbs /ipk WNMTR-4C88C-JK8YV-HQ7T2-76DF9 >nul||cscript //nologo slmgr.vbs /ipk 2F77B-TNFGY-69QQF-B8YKP-D69TJ >nul||cscript //nologo slmgr.vbs /ipk DCPHK-NFMTC-H88MJ-PFHPY-QJ4BJ >nul||cscript //nologo slmgr.vbs /ipk QFFDN-GRT3P-VKWWX-X7T3R-8B639 >nul||cscript //nologo slmgr.vbs /ipk M7XTQ-FN8P6-TTKYV-9D4CC-J462D >nul||cscript //nologo slmgr.vbs /ipk 92NFX-8DJQP-P6BBQ-THF9C-7CG2H >nul&goto skms) else wmic os | findstr /I "home" >nul
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk TX9XD-98N7V-6WMQ6-BX7FG-H8Q99 >nul||cscript //nologo slmgr.vbs /ipk 3KHY7-WNT83-DGQKR-F7HPR-844BM >nul||cscript //nologo slmgr.vbs /ipk 7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH >nul||cscript //nologo slmgr.vbs /ipk PVMJN-6DFY6-9CCP6-7BKTT-D3WVR >nul&goto skms) else wmic os | findstr /I "education" >nul
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk NW6C2-QMPVW-D7KKK-3GKT6-VCFB2 >nul||cscript //nologo slmgr.vbs /ipk 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ >nul&goto skms) else wmic os | findstr /I "10 pro" >nul
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX >nul||cscript //nologo slmgr.vbs /ipk MH37W-N47XK-V7XM9-C7227-GCQG9 >nul||cscript //nologo slmgr.vbs /ipk NRG8B-VKK3Q-CXVCJ-9G2XF-6Q84J >nul||cscript //nologo slmgr.vbs /ipk 9FNHH-K3HBT-3W4TD-6383H-6XYWF >nul||cscript //nologo slmgr.vbs /ipk 6TP4R-GNPTD-KYYHQ-7B7DP-J447Y >nul||cscript //nologo slmgr.vbs /ipk YVWGF-BXNMC-HTQYQ-CPQ99-66QFC >nul&goto skms) else (goto notsupported)
:skms
if %i% GTR 10 goto busy
if %i% EQU 1 set KMS=kms7.MSGuides.com
if %i% EQU 2 set KMS=s8.uk.to
if %i% EQU 3 set KMS=s9.us.to
if %i% GTR 3 goto ato
cscript //nologo slmgr.vbs /skms %KMS%:1688 >nul
:ato
echo ============================================================================&echo.&echo.&cscript //nologo slmgr.vbs /ato | find /i "successfully" && (echo.&echo ============================================================================&echo.&echo #My official blog: MSGuides.com&echo.&echo #How it works: bit.ly/kms-server&echo.&echo #Please feel free to contact me at msguides.com@gmail.com if you have any questions or concerns.&echo.&echo #Please consider supporting this project: donate.msguides.com&echo #Your support is helping me keep my servers running 24/7!&echo.&echo ============================================================================&choice /n /c YN /m "Would you like to visit my blog [Y,N]?" & if errorlevel 2 exit) || (echo The connection to my KMS server failed! Trying to connect to another one... & echo Please wait... & echo. & echo. & set /a i+=1 & goto skms)
explorer "http://MSGuides.com"&goto halt
:notsupported
echo ============================================================================&echo.&echo Sorry, your version is not supported.&echo.&goto halt
:busy
echo ============================================================================&echo.&echo Sorry, the server is busy and can't respond to your request. Please try again.&echo.
:halt
pause >nul
```

**Hoặc:**

```php
@echo off title Activate Windows 11 (ALL versions) for FREE - MSGuides.com&cls&echo =====================================================================================&echo #Project: Activating Microsoft software products for FREE without additional software&echo =====================================================================================&echo.&echo #Supported products:&echo - Windows 11 Home&echo - Windows 11 Professional&echo - Windows 11 Education&echo - Windows 11 Enterprise&echo.&echo.&echo ============================================================================&echo Activating your Windows...&cscript //nologo slmgr.vbs /ckms >nul&cscript //nologo slmgr.vbs /upk >nul&cscript //nologo slmgr.vbs /cpky >nul&set i=1&wmic os | findstr /I "enterprise" >nul 
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk NPPR9-FWDCX-D2C8J-H872K-2YT43 >nul||cscript //nologo slmgr.vbs /ipk DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4 >nul||cscript //nologo slmgr.vbs /ipk YYVX9-NTFWV-6MDM3-9PT4T-4M68B >nul||cscript //nologo slmgr.vbs /ipk 44RPN-FTY23-9VTTB-MP9BX-T84FV >nul||cscript //nologo slmgr.vbs /ipk WNMTR-4C88C-JK8YV-HQ7T2-76DF9 >nul||cscript //nologo slmgr.vbs /ipk 2F77B-TNFGY-69QQF-B8YKP-D69TJ >nul||cscript //nologo slmgr.vbs /ipk DCPHK-NFMTC-H88MJ-PFHPY-QJ4BJ >nul||cscript //nologo slmgr.vbs /ipk QFFDN-GRT3P-VKWWX-X7T3R-8B639 >nul||cscript //nologo slmgr.vbs /ipk M7XTQ-FN8P6-TTKYV-9D4CC-J462D >nul||cscript //nologo slmgr.vbs /ipk 92NFX-8DJQP-P6BBQ-THF9C-7CG2H >nul&goto skms) else wmic os | findstr /I "home" >nul 
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk TX9XD-98N7V-6WMQ6-BX7FG-H8Q99 >nul||cscript //nologo slmgr.vbs /ipk 3KHY7-WNT83-DGQKR-F7HPR-844BM >nul||cscript //nologo slmgr.vbs /ipk 7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH >nul||cscript //nologo slmgr.vbs /ipk PVMJN-6DFY6-9CCP6-7BKTT-D3WVR >nul&goto skms) else wmic os | findstr /I "education" >nul 
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk NW6C2-QMPVW-D7KKK-3GKT6-VCFB2 >nul||cscript //nologo slmgr.vbs /ipk 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ >nul&goto skms) else wmic os | findstr /I "11 pro" >nul 
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX >nul||cscript //nologo slmgr.vbs /ipk MH37W-N47XK-V7XM9-C7227-GCQG9 >nul||cscript //nologo slmgr.vbs /ipk NRG8B-VKK3Q-CXVCJ-9G2XF-6Q84J >nul||cscript //nologo slmgr.vbs /ipk 9FNHH-K3HBT-3W4TD-6383H-6XYWF >nul||cscript //nologo slmgr.vbs /ipk 6TP4R-GNPTD-KYYHQ-7B7DP-J447Y >nul||cscript //nologo slmgr.vbs /ipk YVWGF-BXNMC-HTQYQ-CPQ99-66QFC >nul&goto skms) else (goto notsupported) 
:skms 
if %i% GTR 10 goto busy 
if %i% EQU 1 set KMS=kms7.MSGuides.com 
if %i% EQU 2 set KMS=s8.uk.to 
if %i% EQU 3 set KMS=s9.us.to 
if %i% GTR 3 goto ato 
cscript //nologo slmgr.vbs /skms %KMS%:1688 >nul 
:ato 
echo ============================================================================&echo.&echo.&cscript //nologo slmgr.vbs /ato | find /i "successfully" && (echo.&echo ============================================================================&echo.&echo #My official blog: MSGuides.com&echo.&echo #How it works: bit.ly/kms-server&echo.&echo #Please feel free to contact me at msguides.com@gmail.com if you have any questions or concerns.&echo.&echo #Please consider supporting this project: donate.msguides.com&echo #Your support is helping me keep my servers running 24/7!&echo.&echo ============================================================================&choice /n /c YN /m "Would you like to visit my blog [Y,N]?" & if errorlevel 2 exit) || (echo The connection to my KMS server failed! Trying to connect to another one... & echo Please wait... & echo. & echo. & set /a i+=1 & goto skms) 
explorer "http://MSGuides.com"&goto halt 
:notsupported 
echo ============================================================================&echo.&echo Sorry, your version is not supported.&echo.&goto halt 
:busy 
echo ============================================================================&echo.&echo Sorry, the server is busy and can't respond to your request. Please try again.&echo. 
:halt 
pause >nul
```

## XEM HẠN WINDOWS ##

Copy đoạn code sau:

```php
slmgr/xpr
```

Dán vào NotePad và Save As với tên HanWindows.cmd rồi Run nó dưới quyền Run Administrator nếu lên hình vậy là đã kích hoạt vĩnh viễn

![image](https://user-images.githubusercontent.com/103977676/202642602-3d2401ba-f9ff-47b2-8ce3-f9625a6f783b.png)

- Nếu không được vĩnh viễn tức là chỉ kích hoạt được 6 tháng, lúc này ta tạo gia hạn kích hoạt bằng **Activate AIO Tools v3.1.3**

![image](https://user-images.githubusercontent.com/103977676/202644709-e8f016c9-b755-4723-ac94-fffb44b72927.png)

- Hoặc gia hạn kích hoạt bằng **Online KMS Activation Script v6.0**

![image](https://user-images.githubusercontent.com/103977676/202645570-5d4c5903-a58a-41fe-80d2-e9811c470c68.png)
