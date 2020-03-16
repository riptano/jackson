# Building
```
ant dist
```

# Publishing locally
```
ant -lib lib/ant/maven-ant-tasks-2.0.10.jar maven.local.release
```

# Publishing remotely
```
ant -lib lib/ant/maven-ant-tasks-2.0.10.jar -Duser=xyz -Dpassword=123 maven.remote.release
```
