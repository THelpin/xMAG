****************************************
          Short presentation
****************************************


The xMAG package is an extension of the xAct Bundle  http://www.xAct.es/ (José M. Martin-Garcia, GPL 2002-2026). To work properly this package needs the following packages 
From the xAct bundle : xPerm, xTensor, Invar, SymManipulator, xPert, xTras. 
Independent package coming with xBrauer bundle : SymmetricFunctions, BrauerAlgebra. 
Note that SymmetricFunctions and BrauerAlgebra have to be installed as a Mathematica package not as an xAct package.



****************************************
          INSTALLATION NOTES 
****************************************


When uncompressed, the archive files give a number of files hanging
from a directory called xMAG-$BranchName/.
Rename this directory to xMAG/ and placed it at
(or linked from) one of the places Mathematica prepares for external
applications in the xAct directory. You can find the actual paths in your Mathematica
installation in the variables $BaseDirectory and $UserBaseDirectory.
You need the Applications/ subdirectory (or subfolder) of those
returned by those variables.

For Wolfram Language versions before 14.1 use Mathematica instead of
Wolfram in the following links.

Linux:

   - system-wide installation (requires root priviledges):

        /usr/share/Wolfram/Applications/xAct/

   - single-user installation:

        $HOME/.Wolfram/Applications/xAct/

Mac OS:

   - system-wide installation (requires root priviledges):

        /Library/Wolfram/Applications/xAct/

   - single-user installation:

        /Users/<user>/Library/Wolfram/Applications/xAct/

MSWindows:

   - system-wide installation:

	C:\Program Files\Wolfram Research\Wolfram\<version>\AddOns\Applications\xAct\

   - single-user installation:

	C:\Users\<user>\AppData\Roaming\Wolfram\Applications\xAct\

   Beware that in Windows these directories might be hidden!


Documentation files and examples (like DefCovD_xMAG.nb, Tutorial_Examples_xMAG.nb  etc) are placed in the xMAG/Documentation directory.

Then the packages can be loaded using unix style

        <<xAct/xMAG/xMAG.m

or Mathematica style

        <<xAct`xMAG`

If you have any problem, don't hesitate to contact me at

thomas.helpin@gmail.com

