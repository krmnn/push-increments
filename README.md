# push-increments
03/2014 by Thomas Karmann <thomas@krmnn.de>

## Description
This script will synchronize multiple directories/files to a remote location
via rsync and mail a nicely formatted log with itemized changes to you.

For a simple mail relay configuration, see [Make a MacOS send mail over relay via built-in postfix](https://gist.github.com/krmnn/d96ff20c1f43eb517ce6db222368cd17).


## Running it

e.g. by crontab (edit via `crontab -e`), runs every 12 hours:
```
    0 */12 * * * /path/to/bin/push-increments /path/to/filelist
```

