# pong
(not the video game)

This is a simple CLI ping tool. It's primary feature is the ability to play a console beep on a succesful ping or on an unsuccesful ping. This can be especially helpful if you're waiting for a system to go up / down and want an audible alert once it has started / stopped pinging.

Functionality will continue to be added as time permits.

### How to use pong
You probably want to place the pong binary somewhere in your $PATH so you can use it easily from the command line.

```
Options:
    -b        Play a console beep when a ping is succesful.
    -B        Reverse of -b. Play a console beep when a ping is not succesful.
    -D        Print timestamp at the start of each line.
```
### Examples
Ping a device, displaying timestamps, and play the console beep noise when a ping is succesful.
```
pong -D -b 192.168.0.1
```
