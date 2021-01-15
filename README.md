# wazo-plugind-netdata
```
## not working anymore wazo plugind-cli can't use main branch of a git repository
apt install wazo-plugind-cli
wazo-plugind-cli -c 'install git https://github.com/benasse/wazo-plugind-netdata.git'
```
## asterisk statistics
Some logics of the netdata prometheus plugin are not configurable.

It is for the moment necessary to use a patched version of `go.d.plugin`

More information available here: [#531](https://github.com/netdata/go.d.plugin/issues/531)
