## Kannel Setup

Disable mobile broadband connection (on ubuntu dekstop)

```
sudo apt-get install kannel
sudo usermod -a -G dialout kannel
sudo mkdir -p /var/lib/kannel/spool
sudo chown kannel -R /var/lib/kannel/
```

Uncomment START_SMSBOX=1 on /etc/default/kannel

Config [/etc/kannel/kannel.conf](kannel.conf)
