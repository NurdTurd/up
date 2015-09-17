up (OSX Version)
==

A simple command line tool for uploading a file that outputs the location of the uploaded file.

**This is a slightly modified version. The original creator of this project is [@simplyianm](https://github.com/simplyianm). I say slightly modified because this versions quiets the output of `scp` and uses `pbcopy` to copy to the clipboard the link that the scripts prints out when it finishes.**

Installation
-------------

First, copy the `up` file to `/usr/local/bin`.

Then, create a file called `~/.up-config` with the following contents:

```
user@remote:remote/folder/,http://remote.url/folder/
```

See `.up-config.sample` for details.

License
-------

MIT License.

