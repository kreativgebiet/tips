## How to update rsync on your Mac

Before even thinking about updating you need to know, that Mac is shipping with a really outdated version of rsync. I just got the message of having version 2.7.1 installed on my OS X Yosemite.

If you are not using homebrew, please refer to [this tutorial](https://selfsuperinit.com/2014/01/04/an-updated-rsync-3-1-0-for-mavericks/)

### Updating homebrew

```
$ brew update
```

### Installing/updating rsync

```
$ brew tap homebrew/dupes
$ brew install rsync
```

Be sure to restart zsh and have fun with the fresh updated rsync.
