# javadebug

```
$ export CATALINA_OPTS="-Xrunjdwp:transport=dt_socket,server=y,suspend=y,address=15000 -verbose:class"
$ bin/oozied.sh run
$ jdb -attach localhost:15000
stop in org.apache.oozie.service.ShareLibService.init
cont
trace go methods <THREAD ID>
```
 
