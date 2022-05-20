SSH into the remote server with an SSH client such as https://www.putty.org/

Host will be the IP of the server and port 22.

Open the file with nano editor and make any changes (use your arrow keys to navigate around): `nano /home/wikibase/LocalSettings.php`

To save your edits, press `Ctrl + X` then press `Y`. Press `N` if you don't wish to save them/

Restart the wiki so changes take effect: `systemctl restart wiki.service`
