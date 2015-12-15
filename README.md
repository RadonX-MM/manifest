RadonX Marshmallow
==================
Elemental Simplicity, Radioactive Power.

What is RadonX?
---------------
RadonX is a CAF ROM for the OnePlus one based on OmniROM. The goal is 
to optimize and improve the ROM by merging in CAF and using the standard SaberMod optimizations. Many
features will also be added, but are second to performance.

Syncing
-------
Set up your Linux machine to build Android and install repo.

 $ repo init -u https://github.com/RadonX-MM/manifest -b mm-omni
 
 $ repo sync -j16
 
Building
--------
Build using the following commands
  
  $ . build/envsetup.sh
  
  $ lunch
  
  $ make otapackage -j(Number of Cores +2)
