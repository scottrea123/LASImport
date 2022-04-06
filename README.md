# LASImport
Addon for Civil3D to support point clouds.

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

  <runtime>        	
	  <gcAllowVeryLargeObjects enabled="true" />
  </runtime>

See: https://docs.microsoft.com/en-us/dotnet/framework/configure-apps/file-schema/runtime/gcallowverylargeobjects-element?redirectedfrom=MSDN

--------------------

To launch application in Civil3D, enter the command "LAS"

-------------------

Documentation currently not available.
