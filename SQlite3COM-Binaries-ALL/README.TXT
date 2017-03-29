You need to download and install also newObjects ActiveX Pack1:
http://www.newobjects.com/axpack1
Note that from August 2006 SQLite3 COM will be packed with the 
new version of AXPack1.

This package contains the SQLite3 COM DLL for:
- 32 bit Windows desktops/laptops
- Pocket PC 2003 and later
- Smartphone 2003 and later
- General Windows CE.NET 4.2 and later devices.
The DLL has no UI parts and the general CE.NET versions of the DLL
can be safely used on any device running Windows CE.NET 4.2 or later.
However the PocketPC and Smarpthone versions are optimized for the
respective devices and in future they may include some helpful features
specific to those devices. Therefore it is recommended to distribute with
your applications the specific versions when possible and acceptable.

The versions of the DLL for older Windows CE versions will be included with
the next version of newObjects ActiveX Pack1 from August 2006.

How to use:
register the DLL manually:
  - on desktops use regsvr32 utility
  - on devices use regsvrce utility
  Alternatively you can register the DLL with newObjects
Micro Script Host which is distributted with ActiveX Pack1.
To do so start nwmicrohost.exe and choose "Register COM DLL"
from the Tools menu (on both devices and desktops).

If you want to include SQLite3 COM with your application(s),
include it in your package and do not forget that it is COM DLL
and must be registered - make the necessary adjustments.

newObjects [ ] 2006