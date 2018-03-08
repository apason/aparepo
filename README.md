# aparepo
repository for gentoo linux

##installation##
Just create file under /etc/portage/repos.conf/aparepo.conf
with following content:

```
[aparepo]
prioority = 1000
location = /var/local/aparepo
#layman-type = git
sync-type = git
auto-sync = yes
sync-uri = git://github.com/apason/aparepo.git
```

Run `emerge --sync`

Feel free to change priority and auto-sync values
