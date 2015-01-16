uz-get
======

uz-get is a script that deals with searching and retrieving Unreal Tournament packages from redirect servers.

Usage: uz-get -dhirsuc ?file?  
Options:  
-d --download URL Downloads and install a networkpackage  
-h --help This help text  
-i --install PACKAGE Searches and downloads a package  
-r --repair PACKAGE Checks for and installs missing dependencies  
-s --search PACKAGE Search for the package in the repository  
-u --update Update the filelist  
-f --fix-mismatch Check the UnrealTournament.log for version mismatches and missing files  
-c --clear-cache Clear the cache, move files to their respective directories
   
Requires uIni.pm and upkg.pm which can be found on my github.

Settings
Settings can be configured in uz-get.ini, this file should be in the default System directory (either ~/.loki/ut/System on linux or C:/UnrealTournament/System on Windows), the same directory as uz-get or specified in the script.

The following settings are used:
utdirs[0 .. #] = directories related to UT, should contain the default subdirectories for Maps etc. Specify as many as you want, utdirs[0] should be the default directory.
pathToUcc = full path to ucc / ucc.exe
pathToLog = full path where the UnrealTournament log file is stored
storeId = id of the directory to store files in, matches with utdirs[#]
