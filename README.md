# CentOS-config
Repo for personal and educational purposes

I can access 'olles-recept' with smbclient just fine, but I am unable to put any files on that share.

I have tried disabling SELinux and I've attempted troubleshooting this for pretty much a whole day.

The CentOS server is running in a VM in Virtualbox. Host OS is Windows 10, but I also have another CentOS VM that is meant to act as a client.

Windows won't even let me access the share, even if I turn off the firewall. The CentOS client VM can access it, but is unable to write to it for some reason.

/dev/sdb1 is formatted as an EXT4 partition with GPT table and Linux Filesystem type.

Please provide assistance
