# LASImport v2.0
Addon for Civil3D to support point clouds.

LAS & LAZ file formats are accepted.

To launch application in Civil3D, enter the command "LAS"

-----------------------

Features:

Load LAS & LAZ files (version 1.2 tested, others YMMV)

Bulk Point Cloud boundary import (rectangular bounds)

Convex Hull creation (tight boundary around cloud)

OpenGL 3D and Plan views

Civil3D DTM sample & overlay

COGO point creation

2D polyline elevation sampling

DTM elevation audit

Alignment sectioning at interval

Measurement tool

-----------------------

![image](https://user-images.githubusercontent.com/97759630/162006863-2498db21-96b2-4395-aaf3-ca7ca337d8d6.png)

![image](https://user-images.githubusercontent.com/97759630/162006907-a316d148-527e-45c7-aec8-0c144811540b.png)

![image](https://user-images.githubusercontent.com/97759630/162006944-11a50789-d99e-4578-9a6c-2827d9b6f68e.png)

-----------------------

Uses the following libraries:

  LoycCore: https://github.com/qwertie/LoycCore
  
  OpenTK: https://github.com/opentk/opentk
  
  LASZIP.net: https://github.com/shintadono/laszip.net
  
  SQLite.net: https://github.com/praeclarum/sqlite-net
  
 --------------------

To Install:

Download bundle

Install using AutoLoad described here: https://stackoverflow.com/questions/46282189/autocad-2018-autoload-dll

To support very large point clouds in memory, enable VeryLargeObjects support in the acad.exe.config file:

![image](https://user-images.githubusercontent.com/97759630/162004361-5e405aaf-3a76-4783-952e-27ec3106ce08.png)

See: https://docs.microsoft.com/en-us/dotnet/framework/configure-apps/file-schema/runtime/gcallowverylargeobjects-element?redirectedfrom=MSDN

--------------------

Documentation currently not available.

--------------------

This software is distributed WITHOUT ANY WARRANTY and without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
