# svc-acl
PowerShell script that identifies Windows services with weak permissions.

Based on https://rohnspowershellblog.wordpress.com/2013/03/19/viewing-service-acls.

Currently, it loops through a user-defined list of Windows services and outputs the result in the format resulting from piping the script to ```select -ExpandProperty Access```.

Usage:

1. Create a text file containing a list of services you wish to enumerate.
2. Modify line 114 to specify the location of your text file.
3. Run script.
