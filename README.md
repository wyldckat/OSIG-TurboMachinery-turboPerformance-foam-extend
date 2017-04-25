OSIG-TurboMachinery-turboPerformance-foam-extend
================================================

This git repository was created Bruno Santos (wyldckat@github), based on the original files that are available here: svn://svn.code.sf.net/p/openfoam-extend/svn/trunk/Breeder_1.6/OSIG/TurboMachinery

It has been created after being contacted about this thread: https://www.cfd-online.com/Forums/openfoam-installation/140824-sig-turboperformance-library-looking-updates-beyond-1-6-ext-1-5-dev.html

The official wiki page for this library is this one: http://openfoamwiki.net/index.php/Sig_Turbomachinery_Library_turboPerformance

The original source code from the SVN repository mentioned above is designed to work with "OpenFOAM-extend" 1.6-ext (now known as foam-extend) and is also present in the branch `fe30` at this git repository, which is known to also build with foam-extend 3.0 and 3.1.

This git repository aims to unofficially extend the ability to build this library with the more recent versions of foam-extend 4.0 and newer. The main objective is to adapt the source code and tutorials to each of the currently unsupported foam-extend versions, such as 4.0. Therefore, please keep in mind that the respective tutorials are not fully tested with each foam-extend version.


Documentation
=============

See the official wiki page for this library: http://openfoamwiki.net/index.php/Sig_Turbomachinery_Library_turboPerformance

In the folder `tutorials` you should find some examples on how to use this library.


Disclaimer and License
======================

Original files came from here:

  * svn://svn.code.sf.net/p/openfoam-extend/svn/trunk/Breeder_1.6/OSIG/TurboMachinery/src/turboPerformance
  * svn://svn.code.sf.net/p/openfoam-extend/svn/trunk/Breeder_1.6/OSIG/TurboMachinery/tutorials

This is bound to the same license as foam-extend, namely GNU Public License v3. Quoting from foam-extend's license statement:

    foam-extend is free software: you can redistribute it and/or modify it
    under the terms of the GNU General Public License as published by the
    Free Software Foundation, either version 3 of the License, or (at your
    option) any later version.

    foam-extend is distributed in the hope that it will be useful, but
    WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
    General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with foam-extend.  If not, see <http://www.gnu.org/licenses/>.


How to get+build OSIG-TurboMachinery-turboPerformance-foam-extend from this repository
======================================================================================

foam-extend 3.0 and 3.1
-----------------------

For getting and building from git:
```
git clone git://github.com/wyldckat/OSIG-TurboMachinery-turboPerformance-foam-extend.git
cd OSIG-TurboMachinery-turboPerformance-foam-extend
git checkout fe30
wmake libso
```

For getting and building from zip:
```
wget "https://github.com/wyldckat/OSIG-TurboMachinery-turboPerformance-foam-extend/archive/fe30.zip" -O OSIG-TurboMachinery-turboPerformance-foam-extend.zip
cd OSIG-TurboMachinery-turboPerformance-foam-extend-fe30
chmod +x Allw* example/All*
wmake libso
```


foam-extend 4.0
---------------

For getting and building from git:
```
git clone git://github.com/wyldckat/OSIG-TurboMachinery-turboPerformance-foam-extend.git
cd OSIG-TurboMachinery-turboPerformance-foam-extend
git checkout fe40
wmake libso
```

For getting and building from zip:
```
wget "https://github.com/wyldckat/OSIG-TurboMachinery-turboPerformance-foam-extend/archive/fe40.zip" -O OSIG-TurboMachinery-turboPerformance-foam-extend.zip
cd OSIG-TurboMachinery-turboPerformance-foam-extend-fe40
chmod +x Allw* example/All*
wmake libso
```
