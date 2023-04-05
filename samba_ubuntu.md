# install samba:

```
sudo apt-get update -y
sudo apt-get upgrade -y
sudo apt install samba -y
```
configuration:

```
# sudo nano /etc/samba/smb.conf
```

## add following configuration:
```
[share]
    comment = Shared Floder
    path = /root/share
    browsable = yes
    guest ok = no
    read only = no
```

# restart service:
```
sudo service smbd restart
```

# set samba user:
```
sudo smbpasswd -a root    # must be user who already exists
```

# open port

```
sudo ufw allow samba
```
# check ufw

```
sudo ufw status
```
access:

```
\\localhost\share
```

# completely remove samba:
```
apt-get autoremove samba samba-common -y
apt-get remove --purge samba -y
```