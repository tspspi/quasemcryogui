# Graphical user interface for QUASEM cryogenic infrastructure

This is a very simple interface for the QUASEM cryogenic infrastructure.
It requires a running ```quakesrctrl``` control system instance attached
to the MQTT broker to fetch information and to perform control operations

![](https://raw.githubusercontent.com/tspspi/quasemcryogui/master/doc/screenshots/v0_0_5_001.png)

Note that during a single peak scan no operations are triggered and no
measurements are updated! This only happens in idle periods or in between
two peak scans!

