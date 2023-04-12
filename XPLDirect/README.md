How to upload Firmware to the Core Flight Tech. B737 NAV Panel?

-Close all applications and be sure X-Plane 11 is not running at the background. 

The Nav. you have is configurated to run via XPLDirect with X-Plane 11 Zibo737. Update the firmware by following the steps;
1) Download the "Uploader" (https://github.com/coreflighttech/Uploader)
2) Download the Firmwares (CPT.. or F/O..)
3) Close all applications 
4) Connect Nav Panel. via USB and be sure only NAV. Panel is connected.
5) Extract Uploader
6) Move the Firmware file(CPT or F/O into Uploader)
7) Run Xloader.exe
8) Click the file selection button
9) Select the Firmware File
10) Select the device as EFIS/NAV/COMM/ATC/ADF V1
11) Select the Com Port which is the Nav. connected
12) Click the Upload button.
    If Xloader still says “Uploading” after 2 min.;
      12.1) Disconnect the USB cable and then connect it
      12.2) Select the device as EFIS/NAV/COMM/ATC/ADF V2
      12.3) Check the Com Port is the USB port connected to Nav.
      12.4) Click the Upload button
13) Check "Uploaded..." bottom of the Xloader.exe

Important Note: While uploading, never cut the communication of the NAV.Panel. Otherwise, there is no way to recovery if damaged.

[STABLE] XPL_CPT_NAV_RADIO_v2.hex    

[STABLE] XPL_FO_NAV_RADIO.hex

https://coreflighttech.com/product/b737-nav-radio-module-2/

Any feedback, please leave an e-mail to info@coreflighttech.com
