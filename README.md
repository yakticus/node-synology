node-synology
=============

Nodejs compiled to on a Synology NAS with an ARM processor

1. Copy node-v0.10.26/armv5tel/node into /opt/share
2. Add /opt/share/node/bin to your PATH

Note: I tried to determine runtime dependencies but ldd wasn't available on my NAS and couldn't find where to get it!
