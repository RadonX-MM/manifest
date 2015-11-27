RadonX Marshmallow
==================
Elemental Simplicity, Radioactive Power.

What is RadonX?
---------------
RadonX is a CAF ROM for the OnePlus one based on AOSP and the AOSParadox project. The goal is 
to improve the heavy optimization already introduced by CAF in order to perfect AOSP. Many
features will also be added, but are second to performance.

Syncing
-------
Set up your Linux machine to build Android and install repo.

 $ repo init -u https://github.com/RadonX-MM/manifest -b mm-testing
 
 $ repo sync -j16
 
Building
--------
Build using the following commands
  
  $ . build/envsetup.sh
  
  $ lunch 7
  
  $ make otapackage -j(Number of Cores +2)
