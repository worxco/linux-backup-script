linux-backup-script
===================

Used to backup home folders, arbitrary folders, and mysql databases
You can control the number of copies kept for data and mysql separately.

This is managed via 2 different files. The 'backup' file is the executable.
The backup.config file is used to set the configuration used by the executable.

This script can handle making copies to S3 of mysql backups.

S3 requirements

'''
apt-get install python-pip
pip install awscli
'''
