# Active-Windows-cmd
Kích hoạt Windows 7, 8, 10, 11

# Windows 7 #

Mở NotePad lên và copy đoạn mã bên dưới, bấm **Save As** đặt tên là **kichhoatwin7.cmd** sau đó chạy file này dưới quyên **Run Administrator**

```php
@echo off
title Activate Windows 7 Professional/Enterprise for FREE!&cls&echo ============================================================================&echo #Project: Activating Microsoft software products for FREE without software&echo ============================================================================&echo.&echo #Supported products:&echo - Windows 7 Professional&echo - Windows 7 Professional N&echo - Windows 7 Professional E&echo - Windows 7 Enterprise&echo - Windows 7 Enterprise N&echo - Windows 7 Enterprise E&echo.&echo.&echo ============================================================================&echo Activating your Windows...&cd /d %windir%\system32&cscript //nologo slmgr.vbs /upk >nul&cscript //nologo slmgr.vbs /cpky >nul&set i=1&wmic os | findstr /I "enterprise" >nul
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk 33PXH-7Y6KF-2VJC9-XBBR8-HVTHH >nul&cscript //nologo slmgr.vbs /ipk YDRBP-3D83W-TY26F-D46B2-XCKRJ >nul&cscript //nologo slmgr.vbs /ipk C29WB-22CC8-VJ326-GHFJW-H9DH4 >nul&goto server) else (cscript //nologo slmgr.vbs /ipk FJ82H-XT6CR-J8D7P-XQJJ2-GPDD4 >nul&cscript //nologo slmgr.vbs /ipk MRPKT-YTG23-K7D7T-X2JMM-QY7MG >nul&cscript //nologo slmgr.vbs /ipk W82YF-2Q76Y-63HXB-FGJG9-GF7QX >nul)
:server
if %i%==1 set KMS_Sev=kms7.MSGuides.com
if %i%==2 set KMS_Sev=kms8.MSGuides.com
if %i%==3 set KMS_Sev=kms9.MSGuides.com
if %i%==4 goto unsupported
cscript //nologo slmgr.vbs /skms %KMS_Sev%:1688 >nul&echo ============================================================================&echo.&echo.
cscript //nologo slmgr.vbs /ato | find /i "successfully" && (echo.&echo ============================================================================&echo.&echo #My official blog: MSGuides.com&echo.&echo #How it works: bit.ly/kms-server&echo.&echo #Please feel free to contact me at msguides.com@gmail.com if you have any questions or concerns.&echo.&echo #Please consider supporting this project: donate.msguides.com&echo #Your support is helping me keep my servers running everyday!&echo.&echo ============================================================================&choice /n /c YN /m "Would you like to visit my blog [Y,N]?" & if errorlevel 2 exit) || (echo The connection to my KMS server failed! Trying to connect to another one... & echo Please wait... & echo. & echo. & set /a i+=1 & goto server)
explorer "http://MSGuides.com"&goto halt
:unsupported
echo ============================================================================&echo.&echo Sorry! Your version is not supported.&echo.
:halt
pause >nul
```

# Windows 8/8.1 #

Mở NotePad lên và copy đoạn mã bên dưới, bấm **Save As** đặt tên là **kichhoatwin8_81.cmd** sau đó chạy file này dưới quyên **Run Administrator**

```php
@echo off
title Activate Windows 8 / Windows 8.1 ALL versions for FREE!&cls&echo ============================================================================&echo #Project: Activating Microsoft software products for FREE without software&echo ============================================================================&echo.&echo #Supported products:&echo - Windows 8 Core&echo - Windows 8 Core Single Language&echo - Windows 8 Professional&echo - Windows 8 Professional N&echo - Windows 8 Professional WMC&echo - Windows 8 Enterprise&echo - Windows 8 Enterprise N&echo - Windows 8.1 Core&echo - Windows 8.1 Core N&echo - Windows 8.1 Core Single Language&echo - Windows 8.1 Professional&echo - Windows 8.1 Professional N&echo - Windows 8.1 Professional WMC&echo - Windows 8.1 Enterprise&echo - Windows 8.1 Enterprise N&echo.&echo.&echo ============================================================================&echo Activating your Windows...&cscript //nologo slmgr.vbs /upk >nul&cscript //nologo slmgr.vbs /cpky >nul&wmic os | findstr /I "enterprise" >nul
if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk MHF9N-XY6XB-WVXMC-BTDCT-MKKG7 >nul&cscript //nologo slmgr.vbs /ipk TT4HM-HN7YT-62K67-RGRQJ-JFFXW >nul&cscript //nologo slmgr.vbs /ipk 32JNW-9KQ84-P47T8-D8GGY-CWCK7 >nul&cscript //nologo slmgr.vbs /ipk JMNMF-RHW7P-DMY6X-RF3DR-X2BQT >nul) else (cscript //nologo slmgr.vbs /ipk GCRJD-8NW9H-F2CDX-CCM8D-9D6T9 >nul&cscript //nologo slmgr.vbs /ipk HMCNV-VVBFX-7HMBH-CTY9B-B4FXY >nul&cscript //nologo slmgr.vbs /ipk NG4HW-VH26C-733KW-K6F98-J8CK4 >nul&cscript //nologo slmgr.vbs /ipk XCVCF-2NXM9-723PB-MHCB7-2RYQQ >nul&cscript //nologo slmgr.vbs /ipk BN3D2-R7TKB-3YPBD-8DRP2-27GG4 >nul&cscript //nologo slmgr.vbs /ipk 2WN2H-YGCQR-KFX6K-CD6TF-84YXQ >nul&cscript //nologo slmgr.vbs /ipk GNBB8-YVD74-QJHX6-27H4K-8QHDG >nul&cscript //nologo slmgr.vbs /ipk M9Q9P-WNJJT-6PXPY-DWX8H-6XWKK >nul&cscript //nologo slmgr.vbs /ipk 7B9N3-D94CG-YTVHR-QBPX3-RJP64 >nul&cscript //nologo slmgr.vbs /ipk BB6NG-PQ82V-VRDPW-8XVD2-V8P66 >nul&cscript //nologo slmgr.vbs /ipk 789NJ-TQK6T-6XTH8-J39CJ-J8D3P >nul)
set i=1
:server
if %i%==1 set KMS_Sev=kms7.MSGuides.com
if %i%==2 set KMS_Sev=kms8.MSGuides.com
if %i%==3 set KMS_Sev=kms9.MSGuides.com
if %i%==4 goto notsupported
cscript //nologo slmgr.vbs /skms %KMS_Sev% >nul&echo ============================================================================&echo.&echo.
cscript //nologo slmgr.vbs /ato | find /i "successfully" && (echo.&echo ============================================================================&echo.&echo #My official blog: MSGuides.com&echo.&echo #How it works: bit.ly/kms-server&echo.&echo #Please feel free to contact me at msguides.com@gmail.com if you have any questions or concerns.&echo.&echo #Please consider supporting this project: donate.msguides.com&echo #Your support is helping me keep my servers running everyday!&echo.&echo ============================================================================&choice /n /c YN /m "Would you like to visit my blog [Y,N]?" & if errorlevel 2 exit) || (echo The connection to my KMS server failed! Trying to connect to another one... & echo Please wait... & echo. & echo. & set /a i+=1 & goto server)
explorer "http://MSGuides.com"&goto halt
:notsupported
echo ============================================================================&echo.&echo Sorry! Your version is not supported.
:halt
pause
```


# Kích hoạt Windows, sạch, không virus!!!
 
Windows | cmd, file active | Video | Notes
-- | -- | -- | --
Windows 7|https://bit.ly/3rlEJ7o Password: congdongbatdongsan|https://www.youtube.com/watch?v=kROnb_TDYGA| [Key kích hoạt](https://bsthanh-my.sharepoint.com/:w:/g/personal/laptopxiaomi_bsthanh_tk/ER_FGAnorSZPusySh8nSVG4BLa2CikFTkRcvsgyKexSVEw?e=AhulFg)|
Windows 8 | https://bit.ly/3vljAf0 | https://www.youtube.com/watch?v=ptMDZ3f0Ilg| [Key kích hoạt](https://bsthanh-my.sharepoint.com/:w:/g/personal/laptopxiaomi_bsthanh_tk/EQ2KtidTrTFDj0cM-F2xjIQBTXkFUWK7EmrV7g1k12m3aA?e=tS6udi)|
Windows 10| https://bit.ly/3vg1F9b OR https://bit.ly/3vcO4zy OR https://bit.ly/3vljAf0| https://youtu.be/Deosrqp1Ojg OR https://www.youtube.com/watch?v=ptMDZ3f0Ilg| [Key kích hoạt](https://bsthanh-my.sharepoint.com/:w:/g/personal/laptopxiaomi_bsthanh_tk/EXlDc9qUX1xIuZlPgGtuKi4BQBWK_HrC2zbu5vqppDphgg?e=M79j6Y)|
Windows 11||| [Key kích hoạt](https://bsthanh-my.sharepoint.com/:w:/g/personal/laptopxiaomi_bsthanh_tk/EW084p7rK_xMh7l46J6YFh8BYx0pqOidnlPWbdAMuQyuTQ?e=g5Gxky)

Goodluck for you!!!

[Chia sẽ địa điểm trên Google map](https://goo.gl/maps/ZAzVMCgx4S4X4A55A)
