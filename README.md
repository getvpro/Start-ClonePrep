# Start-ClonePrep
Golden image clone prep steps for Citrix golden images
This script performs following key functions:

***

* Clears any locally cached profiles net set in $CTXBUILDID name
* Checks for any pending reboots, and prompts to reboot if one is found
* Resets WEM cache
* Stops & disables windows update service
* Empties recycle bin
* Performs a graceful shutdown of the VM



