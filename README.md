# Synaccess netBooter driver for Hamilton Venus

This is a driver I wrote for controlling the [Synaccess netBooter
NP-02B](https://www.synaccess-net.com/np-02b) switched PDU (Power Distribution
Unit) from the Hamilton Venus liquid handler software.

I wrote the driver as a quick-and-dirty way of switching a V&P mixer on and off
from our [Hamilton STAR](https://www.hamiltoncompany.com/automated-liquid-handling/platforms/microlab-star)
liquid handler, in support a bead assay automation project.

The driver is written in the proprietary Hamilton HSL language, which is a
cross between watered-down C and VBA.  The documentation for HSL is sparse, so
I had to figure a lot out by reading existing HSL code and by trial-and-error.