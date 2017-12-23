
# Auto Script, By IBNU FACHRIZAL (087773091160)
=================================================================================

# debian7.sh
```
wget https://raw.githubusercontent.com/cimuncang/SSH-SSL/master/debian7.sh && chmod +x ./debian7.sh && ./debian7.sh
```
# OPENVPN
```
wget -O openvpn.sh https://raw.githubusercontent.com/cimuncang/SSH-SSL/master/openvpn.sh && chmod +x openvpn.sh && ./openvpn.sh
```
# TERIMA KASIH YA ALLAH SWT ATAS SEMUANYA
=================================================================================

DELETEUSER OTOMATIS

```
wget https://raw.githubusercontent.com/cimuncang/SSH-SSL/master/config/deleteuserexpire.sh
```

```
wget https://raw.githubusercontent.com/cimuncang/SSH-SSL/master/config/userban.sh
```

# crontab -e
```
59 23 * * * sudo bash ~/deleteuserexpire.sh > /dev/null 2>&1
* 3 * * * sudo bash ~/userban.sh > /dev/null 2>&1
```


SSH SSL
```
https://tkjpedia.com/install-stunnel-ssh-ssl-untuk-kpn-revolution/
```
