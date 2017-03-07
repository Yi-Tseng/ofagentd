ofagentd
====

OF-DPA ofagent daemon.


## Install
Put ofagentd into /etc/init.d/
```
mv ofagentd /etc/init.d/ofagentd
```

Change ofagent file mode
```
chmod 755 /etc/init.d/ofagentd
```

Update rc
```
update-rc.d ofagentd defaults
```

Create config file dir
```
mkdir -p /etc/ofagentapp/
cp config.sample /etc/ofagentapp/config
```


## Start/Stop
Start ofagent
```
/etc/init.d/ofagentd start
```

Stop ofagent
```
/etc/init.d/ofagentd stop
```

