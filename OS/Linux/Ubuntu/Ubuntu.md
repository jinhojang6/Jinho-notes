## Poppular Linux commands
```
- https://www.ubuntupit.com/best-linux-commands-to-run-in-the-terminal/
- https://www.howtogeek.com/412055/37-important-linux-commands-you-should-know/
```

<br />

## Check OS version
```
cat /etc/os-release
lsb_release -a
hostnamectl
```

<br />


## Change password
```
sudo passwd {username}
```
- https://www.cyberciti.biz/faq/change-a-user-password-in-ubuntu-linux-using-passwd/

<br />

## Delete all files in the current directory
```
rm *
rm -r * (including subdirectories and files inside them)
```

<br />

## Run a .sh file
```
chmod +x /path/to/yourscript.sh
/path/to/yourscript.sh
```

<br/>


## The number of CPU cores
```
cat /proc/cpuinfo | grep processor | wc -l
```

<br/>

## Check RAM
```
free -h
```

<br/>

## Check storage
```
df -h
```

<br/>

## RDP
Install XRDP
```
sudo apt-get install xrdp
sudo apt-get install lubuntu-desktop
```
and open 3389 port
