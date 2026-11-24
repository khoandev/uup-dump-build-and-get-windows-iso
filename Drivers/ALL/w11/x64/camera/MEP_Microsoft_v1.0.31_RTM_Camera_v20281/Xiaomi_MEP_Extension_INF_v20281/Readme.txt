===========================================
SunplusIT NB camera MEP extension INF
===========================================
Install:
Run install.bat by administrator
or
Open command window by administrator.
Type "pnputil /add-driver SpitExMEP.inf /install" in command window.
or
Right click on SpitExMEP.inf, then select "Install".

Uninstall:
1. Open Device Manager. Right click on camera device, select "Properties".
2. In the Properties dialog, select "Details" page.
3. Fine "Extendeds Infs" in the "Property" list box, there is a "oemxx.inf" in the Value box.
4. Open command window by administrator.
5. Type "pnputil /delete-driver oemxx.inf /uninstall" in command window.


Revision History:
===========================================
Version 2.0.28.1 (2023/09/19)
---------------------------------------------------------------
- First release.