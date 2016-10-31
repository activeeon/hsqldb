# HSQLDB

This repository is used to create an HSQLDB binary that includes patches which
have not yet been released.

There is currently only one patch difference related to silent option which is
not working:

https://sourceforge.net/p/hsqldb/bugs/1456/

Once the fix is included in an HSQLDB release, the Scheduling project can switch
back to an officially supported release version of HSQLDB.

## Building

You simply need to move to `build/` folder and execute the following command:

```
$ ./gradlew hsqldb
```

The last command will output a file named `hsqldb.jar` in `lib` folder.

