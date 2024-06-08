# Office-2021-Activation

C:\Windows\system32>cd /d %ProgramFiles(x86)%\Microsoft Office\Office16
The system cannot find the path specified.

C:\Windows\system32>cd /d %ProgramFiles%\Microsoft Office\Office16

C:\Program Files\Microsoft Office\Office16>for /f %x in ('dir /b ..\root\Licenses16\ProPlus2021VL_KMS*.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"

C:\Program Files\Microsoft Office\Office16>cscript ospp.vbs /inslic:"..\root\Licenses16\ProPlus2021VL_KMS_Client_AE-ppd.xrm-ms"
Microsoft (R) Windows Script Host Version 5.812
Copyright (C) Microsoft Corporation. All rights reserved.

---Processing--------------------------
---------------------------------------
Installing Office license: ..\root\licenses16\proplus2021vl_kms_client_ae-ppd.xrm-ms
Office license installed successfully.
---------------------------------------
---Exiting-----------------------------

C:\Program Files\Microsoft Office\Office16>cscript ospp.vbs /inslic:"..\root\Licenses16\ProPlus2021VL_KMS_Client_AE-ul-oob.xrm-ms"
Microsoft (R) Windows Script Host Version 5.812
Copyright (C) Microsoft Corporation. All rights reserved.

---Processing--------------------------
---------------------------------------
Installing Office license: ..\root\licenses16\proplus2021vl_kms_client_ae-ul-oob.xrm-ms
Office license installed successfully.
---------------------------------------
---Exiting-----------------------------

C:\Program Files\Microsoft Office\Office16>cscript ospp.vbs /inslic:"..\root\Licenses16\ProPlus2021VL_KMS_Client_AE-ul.xrm-ms"
Microsoft (R) Windows Script Host Version 5.812
Copyright (C) Microsoft Corporation. All rights reserved.

---Processing--------------------------
---------------------------------------
Installing Office license: ..\root\licenses16\proplus2021vl_kms_client_ae-ul.xrm-ms
Office license installed successfully.
---------------------------------------
---Exiting-----------------------------

C:\Program Files\Microsoft Office\Office16>cscript ospp.vbs /setprt:1688
Microsoft (R) Windows Script Host Version 5.812
Copyright (C) Microsoft Corporation. All rights reserved.

---Processing--------------------------
---------------------------------------
Successfully applied setting.
---------------------------------------
---Exiting-----------------------------

C:\Program Files\Microsoft Office\Office16>cscript ospp.vbs /unpkey:6F7TH >nul

C:\Program Files\Microsoft Office\Office16>cscript ospp.vbs /inpkey:FXYTK-NJJ8C-GB6DW-3DYQT-6F7TH
Microsoft (R) Windows Script Host Version 5.812
Copyright (C) Microsoft Corporation. All rights reserved.

---Processing--------------------------
---------------------------------------
<Product key installation successful>
---------------------------------------
---Exiting-----------------------------

C:\Program Files\Microsoft Office\Office16>cscript ospp.vbs /sethst:107.175.77.7
Microsoft (R) Windows Script Host Version 5.812
Copyright (C) Microsoft Corporation. All rights reserved.

---Processing--------------------------
---------------------------------------
Successfully applied setting.
---------------------------------------
---Exiting-----------------------------

C:\Program Files\Microsoft Office\Office16>cscript ospp.vbs /act
Microsoft (R) Windows Script Host Version 5.812
Copyright (C) Microsoft Corporation. All rights reserved.

---Processing--------------------------
---------------------------------------
Installed product key detected - attempting to activate the following product:
SKU ID: cd18ecc0-466a-45d4-8d2e-8c4fa48ae591
LICENSE NAME: Office 21, Office21ProPlus2021R_Grace edition
LICENSE DESCRIPTION: Office 21, RETAIL(Grace) channel
Last 5 characters of installed product key: PG343
ERROR CODE: 0xC004F017
ERROR DESCRIPTION: The Software Licensing Service reported that the license is not installed.
---------------------------------------
Installed product key detected - attempting to activate the following product:
SKU ID: fbdb3e18-a8ef-4fb3-9183-dffd60bd0984
LICENSE NAME: Office 21, Office21ProPlus2021VL_KMS_Client_AE edition
LICENSE DESCRIPTION: Office 21, VOLUME_KMSCLIENT channel
Last 5 characters of installed product key: 6F7TH
<Product activation successful>
---------------------------------------
---------------------------------------
---Exiting-----------------------------

C:\Program Files\Microsoft Office\Office16>
