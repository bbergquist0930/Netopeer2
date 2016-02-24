# Netopeer2 – The NETCONF Toolset

**Netopeer2** is a set of tools implementing network configuration tools based
on the NETCONF Protocol. This is the second generation of the toolset, originally
available as the [Netopeer project](https://github.com/CESNET/netopeer). Netopeer2
is based on the new generation of the NETCONF and YANG libraries -
[libyang](https://github.com/CESNET/libyang) and [libnetconf2](https://github.com/CESNET/libnetconf2).
The Netopeer server uses [sysrepo](https://github.com/sysrepo/sysrepo) as a NETCONF
datastore implementation.

**Netopeer2** is maintained and further developed by the [Tools for
Monitoring and Configuration](https://www.liberouter.org/) department of
[CESNET](http://www.ces.net/). Any feedback, testing or feature requests are welcome.
Please contact us via the [issue tracker](https://github.com/CESNET/Netopeer2/issues).

## Current State
- [x] **CLI** - simple command line interface to connect to a NETCONF server (device).
- [ ] **server** - NETCONF server with a modular datastore allowing interconnection and control of
      various applications.

The Netopeer2 toolset is still under development. While CLI is already usable, the server is pure
work in progress and we don't recommend to use it in this phase.
