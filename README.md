# Unraid-Youtube-dl-Config

This is intended to be used with Unraid and the plugin Usererscripts to download youtube videos and keep them neatly organized for Plex.

## Installation Instructions

1. Download all the files here.
2. Copy the "Downloader" folder to somewhere on your server. (i.e mine is /mnt/user/Storage/Google Drive/Downloader/)
3. Copy the User.Scripts folder to /boot/config/plugins/Userscripts/
4. You'll need to configure where the Downloader folder is located in all of the .conf files. To do this, go into /Downloader/Music-dl/Music.conf and edit the lines under #Archive Settings. (every -dl folder has it's own .conf file)
5. You'll also need to edit the location of where you want these scripts to download your videos/music to. This is located in each .conf file under the #Download Location section.
6. If you want the file renaming to work, add the folders you want the script to monitor to "Folder_List.txt"
7. *Optional: If you have youtube videos that include a dash (-) you'll want to have the folder renamer act differently so it doesn't mess up the titles. Add the folders you want renamed with a dash into "Folder_List_Others.txt" so they get renamed correctly.*
