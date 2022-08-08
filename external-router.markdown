---
layout: wikipage
permalink: /external-router.html
---

# Using MuWire with an external I2P router

MuWire comes with its own embedded I2P router, but you can use an external router as well.  The external router does not need to run on the same machine as MuWire, so you can put the router for example on a home server and MuWire can connect to it from your desktop.

MuWire supports the Java I2P and I2Pd routers.

### Java I2P

You can get the Java I2P router from the [official website](https://geti2p.net).  After setting that up, you may need to change the network interface for the `I2CP` protocol.  By default that interface is `127.0.0.1` which means it will accept only local connections; if you plan to put the router on a home server you will need to change that.  You can do that usually at `http://127.0.0.1:7657/configi2cp`.

### I2Pd

You can get the I2Pd router from the [I2D website](https://i2pd.website).  The `I2CP` protocol is not enabled by default, so you need to edit your `i2pd.conf` file and add the following lines:

```
[i2cp]
enabled=true
address=0.0.0.0
port=7654
```

The `0.0.0.0` means the router will bind to all network interfaces.  You may want to change that to the LAN ip of the server, usually `192.168.x.y`.  You need to restart the I2Pd daemon after making these changes.

## Configuring MuWire

As of version 0.8.12 (currently available as [beta](/beta.html)) you can select an external I2P router host and port in the MuWire wizard or in the `Options`->`I2P`.  

