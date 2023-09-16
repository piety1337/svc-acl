# svc-acl
PowerShell script that enumerates Windows service ACLs for the purpose of identifying weak service permissions.

Based on https://rohnspowershellblog.wordpress.com/2013/03/19/viewing-service-acls.

It loops through a user-defined list of Windows services and outputs the result in the format resulting from piping the script to ```select -ExpandProperty Access```.

Usage:

1. Create a text file containing a list of services you wish to enumerate.
2. Modify line 117 to specify the location of your text file.
3. Run script.
