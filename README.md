# seafile-server-utils
Simple project to help install seafile-server

# How to create a script to start seafile when the server boots
We have an example of the script in the folder: ```/etc/init.d/seafile-server```

Copy the file to the same folder in the server machine and modify it following the seafile installation.

After you modify it, you will need to enable it as follows:

```
$ sudo chmod +x /etc/init.d/seafile-server
$ sudo update-rc.d seafile-server defaults
```

Reboot the server machine, the Seafile should be started automatically.

# References

Install seafile on a raspberry:

https://medium.com/swlh/building-a-file-server-on-a-raspberry-pi-with-seafile-d972bad14688

Seafile Community Setup on Linux

https://manual.seafile.com/deploy/
