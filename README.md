# BYOBU_DropBoxStatus
DropBox status script to show on the BYOBU monitor line

This simple script displays the status of your DropBox on the BYOBU monitor lines.

#Setup
Simply copy the 30_dropbox file to your BYOBU script folder "typically ~/.byobu/bin".

This will show a word "Dbox" on your BYOBU status line, and updates it every 30 seconds.
To change the updating frequency, just change the number at the beginning of the filename.

#Indicator Meanings
- Dbox (red color) = DropBox is not running
- Dbox (green color) = Dropbox is running and Synced
- DbUP (green color) = Dropbox is Syncing by Uploading files
- DbDN (green color) = Dropbox is Syncing by Downloading files
