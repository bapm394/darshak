# Darshak

Darshak is an application serving **two primary usage** -

* detecting any suspicious activity of being tracked via cellular network for example Silent SMS
* to assess security capabilities of your current cellular provider **in realtime**
 
It has following key features supporting GSM and 3G cellular networks -
* detects and alerts when you receive silent SMS
* invokes after every incoming/outgoing telephony call and SMS event
* displays whether authentication has been performed by the operator
over-the-air and used RAND number
* displays ciphering algorithms used by your operator for GSM ( A5/1,
A5/2, A5/3 ) and 3G networks (UEA0 or UEA1)

For detail information, read our recent [Blackhat USA 2014 slides](https://www.isti.tu-berlin.de/fileadmin/fg214/ravi/Darshak-bh14.pdf
)


## Device and OS version supported

1) Samsung Galaxy S3 (GT I9300)

Android 4.1.2  (If you running other version, please install stock
firmware from [Samsung](http://www.sammobile.com/firmwares/
)). 

However we would recommend to install this stock version - https://owncloud.sec.t-labs.tu-berlin.de/owncloud/public.php?service=files&t=883795a7de19d3e9bf20edd6e8f5988c. 

Easiest way to flash stock version is to use Odin tool (https://owncloud.sec.t-labs.tu-berlin.de/owncloud/public.php?service=files&t=080c003b906788e1d3691d3c9128b103).


## How to install

* the Samsung S3 needs to be rooted to run this application. Use [Framroot](http://forum.xda-developers.com/apps/framaroot/root-framaroot-one-click-apk-to-root-t2130276
) or you can flash device with CF-Auto-Root (https://owncloud.sec.t-labs.tu-berlin.de/owncloud/public.php?service=files&t=714f3a8030c92f5ab6aa5a4178372360) using Odin.
It will install SuperSu binary too.

* download [the apk from here] (https://github.com/darshakframework/darshak/blob/master/apk/Darshak.apk
). Or from Playstore (https://play.google.com/store/apps/details?id=com.darshak)

* install [SuperSU](https://play.google.com/store/apps/details?id=eu.chainfire.supersu&hl=de) and give access permission to the Darshak Application.

* Open the application and you are ready to monitor :).

## Data Upload

Currently Darshak stores essential data about GSM and 3G networks in the local
database file.  Soon upload functionality will be available to upload database file from the app to central repository.

To help us improve and add features and build IMSI catcher detector profile, we request you to export database files manualy from the device and mail to darshak@sec.t-labs.tu-berlin.de.
Off course, we make this data avaialbe online for further research in mobile networks.
Disclaimer: This file does not contain your private information such as IMSI, phone number, incoming/outgoing call numbers etc.

## Thanks

* Andreas Schildbach for his essential code part.
* https://github.com/Chainfire/libsuperuser/

* http://iconmonstr.com

* http://android-holo-colors.com/
 
* Tobias Engel for his awesome https://github.com/2b-as/xgoldmon


## Bugs

Please report bugs at darshak@sec.t-labs.tu-berlin.de, thank you.
The code is released under GPL V3. The code is dirty ;) and under development. Feel free to contribute/fork and any suggestions are most welcome.

- Swapnil Udar (@swapnil_udar), Aalto University, Helsinki, Finland
- Ravishankar Borgaonkar (@raviborgaonkar), SecT, TU Berlin, Germany 
