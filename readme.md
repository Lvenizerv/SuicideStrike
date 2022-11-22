## CrowdStrike Killer

This is a very quick and yucky solution to kill CrowdStrike.
It does this by registering a service, which deletes keys for CrowdStrike and then reboots into normal mode.

For some reason bcdedit doesn't work as services so I made it manually grab keys and delete them when turning back to normal mode.

!! Do not run the service in normal mode, as this will cause detection !!

The script provided will automatically install the file and do the process.
.. will upload files when im back
