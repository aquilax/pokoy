pokoy
=====

pokoy is lightweight daemon for X that helps prevent RSI and other computer related stress. It locks the screen and forces you to take regular breaks. Pokoy doesn't have any dependencies except xcb and consumes less than 2 mb of memory. See man page for more information.


**Building and installation:**

```
$ make
# make install
```

**Examples:**
```
$ pokoy # start daemon
$ pokoy
    29:59
	04:59

$ pokoy -s
$ pokoy
    Daemon is sleeping.

$ pokoy -s # wake up
$ pokoy -n # start first break now
$ pokoy -k # kill daemon
```

**Screenshot:**
<p align="center">
  <img src="https://raw.githubusercontent.com/ttygde/pokoy/master/screenshot.png" alt="screenshot"/>
</p>
