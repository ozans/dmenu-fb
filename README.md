# dmenu-fb
Simple dmenu-based file browser and executor

Very simple tool started with the idea of being able to switch between configuration 'profile's and therefore requires an initial folder to start from as a parameter.

How to run
----------
```
$ ./dmenu-fb <initialFolder>
```

Examples
--------
Use-case: profile switching
```
$ ./dmenu-fb ~/bin/iptables
```
Use-case: file browser
```
$ ./dmenu-fb ~/bin
```


Integration with sudo?
-----------------------
Use it in conjunction with dpass.
```
$ SUDO_ASKPASS=~/bin/dpass sudo -A ./dmenu-fb ~/bin/iptables
```

Contributing
------------
Pull requests, bug reports, and feature requests are extremely welcome.


