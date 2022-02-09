# Apache server
- To install apache server
- ``` apt-get install apache2```
```bash
$ cd /var/www/html/
$ ls
<!-- Remove all the files  -->
$ rm -rf *

```
- Create you html file and save it
- Start the apache server 
```bash 
$ service apache2 start
```
- Check the status of apache server by 
```bash 
$ service apache2 status
```
- To see the ip adress of your server
```bash 
$ ifconfig
```
- To restart the apache server
```bash 
$ service apache2 restart
```
- To change the port number 
```bash 
$ nano /etc/apache2/ports.conf
```
