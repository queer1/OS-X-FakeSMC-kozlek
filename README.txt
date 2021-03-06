Notes about this fork by RehabMan:

Note: This version forked from kozlek's branch at: https://www.assembla.com/code/fakesmc/git/nodes 

Download link for RehabMan builds:
https://bitbucket.org/RehabMan/os-x-fakesmc-kozlek/downloads

Older builds are archived here:
https://code.google.com/p/os-x-fake-smc-kozlek/downloads/list

A note about the contents of the download:
Debug/FakeSMC.kext - debug FakeSMC.kext + PlugIns (install for troubleshooting)
Release/FakeSMC.kext - release FakeSMC.kext + PlugIns (recommended install)

Debug/HWMonitor.app - debug version of kozlek's HWMonitor.app
Release/HWMonitor.app - release version of kozlek's HWMonitor.app (recommended)

SL/HWMonitor.app - release version of slice's HWMonitor.app, modified to
 work with kozlek's FakeSMC.kext.  Primarily for use on Snow Leopard, but
 will also work on ML or Lion.

To install:
- install FakeSMC.kext using Kext Wizard.
  (Note: if you had previously used slice's and have the various kexts 
   spread all over /S/L/E, be sure to remove them all)
- run HWMonitor.app and set it up to your preference.



README.TXT from original repo
----------------------------------------------------------------------------

FakeSMC is an open source SMC device driver/emulator (FakeSMC) by netkas (http://netkas.org/) with hardware monitoring plugins ported from OpenHardwareMonitor for Windows and hwmon sensors drivers from Linux.

NOTE: FakeSMC & Plugins starting from v915 provides additional sensors information to HWMonitor then running on Macs. By installing FakeSMC on real Mac you should consider to know what you are doing and how to recover your system back if something goes wrong.

All repositories:

Sourceforge, sources & downloads: https://sourceforge.net/projects/hwsensors/
BitBucket, sources & downloads: https://bitbucket.org/kozlek/hwsensors/overview
Assembla, sources: https://www.assembla.com/code/fakesmc/git/nodes
GitHub, sources: https://github.com/kozlek/HWSensors

HWSensors Project (c) 2014 netkas, slice, usr-sse2, kozlek, navi, THe KiNG, RehabMan 
and others. All rights reserved.

With special thanks to:
netkas for fakesmc
slice for plugins and help in developing the project
usr-sse2 for help in development and first FakeSMC plugins idea and realization 
Navi for investigation of numeric SMC values encoding/decoding and other useful stuff
droplets for testing
Michael Möller for OpenHardwareMonitor
The Real Deal & JrCs for French localization
RehabMan forced me using mutexes and other contributions to the project
Oliver Bolton for OBMenuBarWindow
Mozketo for LaunchAtLoginController
PHPdev32 for an idea to using NVRAM as storage for kext configuration
coercion for initial Haswell support
oswaldini @ www.osx86.org.pl for Polish translation
Matteo «Marchrius» Gaggiano for the enhanced about window with credits scroller and Italian translation
k3nny @ www.insanelymac.com for German translation
Bruce Allen for smartmontools <http://www.smartmontools.org>
Michael Robinson for Cocoa Categories <https://github.com/faceleg/Cocoa-Categories>
Stephane Sudre for Packages (packagesbuild)
Andy Matuschak  for Sparkle framework
Nouveau Project for nouveau linux driver (GeforceSensors base)
Advanced Micro Devices and all contributors for AMD Radeon linux driver (RadeonSensors base)
Joshua Nozzi for JLNFadingScrollView <https://github.com/jnozzi/JLNFadingScrollView>
Rheinfabrik for RFOverlayScrollView <https://github.com/rheinfabrik/RFOverlayScrollView>
Matteo Gaggiano for the enhanced about window with credits scroller
