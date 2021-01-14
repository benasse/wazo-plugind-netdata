# wazo-plugind-netdata
```
## not working anymore wazo plugind-cli can't use main branch of a git repository
apt install wazo-plugind-cli
wazo-plugind-cli -c 'install git https://github.com/benasse/wazo-plugind-netdata.git'
```
## asterisk stats via prometheus exporter

For astersik statistics to be displayed correctly in netdata, at the moment it is
required a patched version of netdata go plugins.
