# Simple Demonstration
## jQuery Verto JS

Simple demonstration of the jQuery Verto JS free source lib, making a video conference through a FreeSWITCH server.

### Setting up

Easier way for a Unix-based system.
Assuming that you have a `python` 2.7.X, run this
command line inside the repository directory:

```sh
python -m SimpleHTTPServer
```

Use your web browser to access the address and port told by
your `stdout`.

Without a server exposing those files, you'll have trouble
with user media permissions.

### Legal

This project should be only a running example. Easy but unofficial.
Also not a safe hub for downloading the Verto.

> Please note that every file in `verto` subfolder has a license
> header. These files were unchanged by me and this repository
> does not accept pull requests for such files.

For more complete demonstrations, including the most updated
Verto lib and the FreeSWITCH itself, check the official repo:
https://freeswitch.org/stash/projects/FS/repos/freeswitch/

Read the lib documentation too (from where I learn how to make
this whole example): https://evoluxbr.github.io/verto-docs/

More about the `mod_verto` responsible for Verto backend:
https://freeswitch.org/confluence/display/FREESWITCH/mod_verto

And more on the official client example for Verto, the Verto
Communicator application:
https://freeswitch.org/confluence/display/FREESWITCH/Verto+Communicator
