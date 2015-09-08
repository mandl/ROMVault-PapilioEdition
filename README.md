ROMVault-PapilioEdition by FelixV and mandl
ROMVault source used with permission from GordonJ
========

Building on Windows
========
 Install Visual Studio 2012 (Pro or Express)
 Open the .sln file in Visual C#
 Build

Building on CentOS
========
 tbd

Building on Ubuntu 14.04 (and most likely other debian based distro's)
========
 Install mono and mono develop for Ubuntu (or your distro)
  http://www.monodevelop.com/download/linux/

 Install cmake
  sudo apt-get install cmake

 Install libftdi-dev
  sudo apt-get install libfdti-dev

 Build romgen and papilio_prog
  mkdir build;cd build
  cmake ../

TODO
========
 test building/running on linux on a per distro basis
 test building/running on windows after linux compatibility mods
 add the left side image to the UI again (got lost!)
 code cleanups
 port romgen3.01 to linux to enable linux version to support pacman variants (superglob, pacman plus, etc)
   (or just integrate romgen style functionality into the C# code)
 finish mapping/renaming images or come up with a better way to display screenshots
 
