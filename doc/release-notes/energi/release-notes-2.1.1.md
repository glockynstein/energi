Energi Core version 2.1.1 Release Notes
=======================================

Energi Core version 2.1.1 is now available from:

  https://energi.world/downloads

Please report bugs using the issue tracker at github:

  https://github.com/energicryptocurrency/energi/issues


How to Upgrade
--------------

If you are running an older version, shut it down. Wait until it has completely
shut down (which might take a few minutes for older versions), then depending on
your operation system:

* for Window run the installer
* for macos run the installer
* for Linux unpack to a separate folder and run from there

**NOTE**: version of Energi Core prior to v2.1.0 must not be used


v2.1.1 changelog
----------------

Major changes:

* CHANGED: to ignore pre-2.1.0 nodes
* NEW: liststakeinputs RPC command

Minor changes:

* CHANGED: removed -litemode
* CHANGED: to ignore MN cache on desktop wallet startup
    - Workaround for known issue due to start/stop sequences
* CHANGED: updated spork defaults
* CHANGED: added PoS-era checkpoints
* FIXED: reservebalance to override -reservebalance switch
* FIXED: reverted regression causing Unicode paths to fail on Windows
