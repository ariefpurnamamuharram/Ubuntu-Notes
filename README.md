# Ubuntu-Notes
Where I write useful terminal commands in Ubuntu.

---

- Get CPU model name information.<br>
  `cat /proc/cpuinfo | grep "model name"`

- Get RAM information.<br>
  `free -h`
  
- Get Ubuntu version.<br> 
  `lsb_release -a`
  
- Get PHP version.<br> 
  `php -version`
  
- Get NginX version.<br> 
  `nginx -V`
  
- Get MySQL version.<br> 
  `mysql -V`

- Check opening ports<br>
  `sudo ss -ltnp`

- Change file or folder ownership.<br>
  `sudo chown username:username folderpath`

- Change group ownership of the directory into www-data.<br>
  `sudo chgrp -R www-data folderpath`

- Change permission (read, write, execute) of directory. <br>
  `sudo chmod -R ug+rwx folderpath`
  
---

_by Arief Purnama Muharram_<br>
_last update on 2021 Jul 17_
