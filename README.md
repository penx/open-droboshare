open-droboshare
===============

A series of scripts and any required code/patches to recreate the functionality of a Droboshare* on ARMv5+ hardware or emulators.

*Droboshare is the now discontinued and unsupported NAS-adapter for Drobo generation 1 and 2.

The intention is that the initial version, once complete, will:
- Emulate a DroboShare inside QEMU 
- Create a bootable image for a Raspberry Pi (ARMv6)
- Correctly mount HFS+ journaled drives (something that the original Droboshare didn't, seemingly the cause of many issues).

The initial scripts are designed to work on both Mac OS X 10.8 and Ubuntu 12.

IMPORTANT: These scripts are mid-development and completely untested. At the moment I only have a single Drobo generation 2, which is currently in use, so the testing I can do is limited. If you'd like to offer your support, either by testing or updates to my scripts, please get in touch.

Possible future features:
 - Support newer non-NAS Drobo models (5D)
 - Support for other ARM based devices.. initially a cheap ARM device with gigabit ethernet.
 - Support for email alerts without having to be connected to Drobo Dashboard
 - Generic NAS features such as AFP or auto-sharing attached non-Drobo USB drives
