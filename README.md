uz-get
======

uz-get is a script that deals with searching and retrieving Unreal Tournament packages from redirect servers.

Usage: uz-get -dhirsu ?file?  
Options:  
-d --download URL Downloads and install a networkpackage  
-h --help This help text  
-i --install PACKAGE Searches and downloads a package  
-r --repair PACKAGE Checks for and installs missing dependencies  
-s --search PACKAGE Search for the package in the repository  
-u --update Update the filelist  
-f --fix-mismatch Check the UnrealTournament.log for version mismatches and missing files  

Requires uIni.pm and upkg.pm which can be found on my github.
