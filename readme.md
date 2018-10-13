Mosquitto TBF
=================

Time based Filter extension using mosquitto v1.4.15

Eclipse Mosquitto
=================

Mosquitto is an open source implementation of a server for version 3.1 and
3.1.1 of the MQTT protocol. It also includes a C and C++ client library, and
the `mosquitto_pub` and `mosquitto_sub` utilities for publishing and
subscribing.

### Video

System Verification

https://youtu.be/FYh58sWFABA

Performance Verification with existing mosquitto v1.4.15

https://youtu.be/bTzUoN61QBw If you want to see the results right away, watch 02:40

### Build Dependencies

* c-ares (libc-ares-dev on Debian based systems) - disable with `make WITH_SRV=no`
* libuuid (uuid-dev) - disable with `make WITH_UUID=no`
* libwebsockets (libwebsockets-dev) - enable with `make WITH_WEBSOCKETS=yes`
* openssl (libssl-dev on Debian based systems) - disable with `make WITH_TLS=no`
* xsltproc (xsltproc and docbook-xsl on Debian based systems) - only needed when building from git sources - disable with `make WITH_DOCS=no`

## Credits
Mosquitto was written by Roger Light roger@atchoo.org

Mosquitto TBF was written by Seho Park seh9306@gmail.com
