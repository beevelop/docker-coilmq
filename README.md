[![Travis](https://shields.beevelop.com/travis/beevelop/docker-coilmq.svg?style=flat-square)](https://travis-ci.org/beevelop/docker-coilmq)
[![Pulls](https://shields.beevelop.com/docker/pulls/beevelop/coilmq.svg?style=flat-square)](https://links.beevelop.com/d-coilmq)
[![Layers](https://shields.beevelop.com/docker/image/layers/beevelop/coilmq/latest.svg?style=flat-square)](https://links.beevelop.com/d-coilmq)
[![Size](https://shields.beevelop.com/docker/image/size/beevelop/coilmq/latest.svg?style=flat-square)](https://links.beevelop.com/d-coilmq)
[![Release](https://shields.beevelop.com/github/release/beevelop/docker-coilmq.svg?style=flat-square)](https://github.com/beevelop/docker-coilmq/releases)
![Badges](https://shields.beevelop.com/badge/badges-7-brightgreen.svg?style=flat-square)
[![Beevelop](https://links.beevelop.com/honey-badge)](https://beevelop.com)

# [CoilMQ](https://github.com/hozn/coilmq/) for Docker :whale2:

> CoilMQ is a simple, configurable STOMP message broker (aka STOMP server) written in Python.

## Run
```
docker run -it -p 61613:61613 beevelop/coilmq
```

## Usage
```
Usage: coilmq [OPTIONS]

  Main entry point for running a socket server from the commandline.

  This method will read in options from the commandline and call the
  L{config.init_config} method to get everything setup.  Then, depending on
  whether deamon mode was specified or not,  the process may be forked (or
  not) and the server will be started.

Options:
  -c, --config FILE   Read configuration from FILE. (CLI options override
                      config file.)
  -b, --host ADDR     Listen on specified address (default 127.0.0.1)
  -p, --port PORT     Listen on specified port (default 61613)
  -l, --logfile FILE  Log to specified file (unless logging configured in
                      config file).
  --debug TEXT        Sets logging to debug (unless logging configured in
                      config file).
  -d, --daemon TEXT   Run server as a daemon (default False).
  -u, --uid UID       The user/UID to use for daemon process.
  -g, --gid GID       The group/GID to use for daemon process.
  --pidfile FILE      The PID file to use.
  --umask MASK        Umask (octal) to apply for daemonized process.
  --rundir DIR        The working directory to use for the daemonized process
                      (default /).
  --help              Show this message and exit.
```
