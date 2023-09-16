# svc-acl
PowerShell script that identifies Windows services with weak permissions.

Based on https://rohnspowershellblog.wordpress.com/2013/03/19/viewing-service-acls - modified for more automation.

Currently, it loops through a user-defined list of Windows services and outputs the result in the format resulting from piping the script to ```select -ExpandProperty Access```.
