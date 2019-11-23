# securityonion_utilities
A small terminal based, menu driven utility to streamline management of the SecurityOnion system.

# Configuration
The following settings can be configured in the top of ***so_utils*** or in a seperate file named ***so_include***.

Variable | Purpose
-------- | -------
su_editor | The text editor you want to invoke.
retention | Allowance range for files to be flagged as available for pruning.
su_backupUser | Username used against your network backup host.
su_backupHost | Address of your network backup.
su_backupPath | Path on your network host to store backups.
su_backupArgs | (optional) Arguments to execute during rsync
|**NOTE**|If backuping up to a Synology NAS, you must specify ***--rsync-path=/usr/bin/rsync***


# Preview
![screenshot](https://i.imgur.com/bUxeE1s.png "screenshot version 13")