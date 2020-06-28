How to Run Windows 10 Faster?

Install a Fresh Windows 10 if Possible or refresh your current Windows 10.

1. Disable the Windows 10 update with the help of registry. as in photo .
2. Diable the Windows 10 update service from Computer Management -> Services & Application.


Now you need to run some scripts in Powershell. To disable & remove some other services that are not usefull you can modify the script as required.
Run the following commands in Powershell as Administrator:

1. First Update the PowerShell execution policy

set-executionpolicy unrestricted

2. Now run following commands

cd scripts

And
Run commands as in given photo(script)
 


