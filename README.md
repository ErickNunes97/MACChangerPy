# MACChangerPy
It's a small project for MAC address change, for ethical hacking purposes, don't use it for bad purposes, any infringement will be your responsibility.

**"With great powers comes great responsabilities!!!"**

![Spider-man](https://www.magicalquote.com/wp-content/uploads/2019/02/With-great-power-comes-great-responsibility.jpg)


## Mode of use:
With this command, you will see all parameters of utilization in this program.

```
python3 main.py --help                                  
```
### Options:
```
  -h, --help show this help message and exit
  -i INTERFACE, --interface=INTERFACE Interface to change its MAC address
  -m NEW_MAC, --mac=NEW_MAC New MAC address
                                      
```                                      
#### Example:

use the command su to be a superuser, after this, use this command:
```
su

python3 main.py -i eth0 -m 00:00:00:00:00:00
```

## Updates

#### _v0.1_

  The "ifconfig" command is deprecated, changed the command to "ip" for more compatibility with other distros.
