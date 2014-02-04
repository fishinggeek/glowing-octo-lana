glowing-octo-lana
=================

Simple project that verifies relative paths

Usage is very simple;
 RelativePath.exe "C:\my\starting\directory" "..\my\relative\path.txt"

 Output for found file;
 Current Directory is C:\my\starting\directory
 File Exists @ C:\my\starting\\my\relative\path.txt

 Output if File is not found;
 Current Directory is C:\my\starting\directory
 File Does Not Exist @ C:\my\starting\\my\relative\path.txt
