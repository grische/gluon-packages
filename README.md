# gluon-packages
custom ffmuc packages feed for gluon

State of the different packages:

- ffho-autoupdater-wifi-fallback
  - Implements switching to fallback mode if we are cut off from the mesh to autoupdate
  - Upstream: https://git.ffho.net/FreifunkHochstift/ffho-packages/src/master/ffho-autoupdater-wifi-fallback

- gluon-domain-migration-ffmuc
  - Migrates from multisite config to multidomain config

- tecff-ath9k-broken-wifi-workaround
  - tries to recover nodes that have problems with wifi connections
  - Upstream: https://github.com/tecff/gluon-packages/tree/master/tecff-ath9k-broken-wifi-workaround
 
- tecff-respondd-watchdog
  - starts gluon-respondd if it isn't running
  
DEPRECATED:
- gluon-config-mode-site-select
  - Implements multiple sites to separate the network
  - not used since appearing of [multidomain-feature](https://gluon.readthedocs.io/en/v2018.1.x/features/multidomain.html) added in gluon v2018.1

- gluon-ebtables-filter-arp-ffmuc
  - Filters arp requests to not be forwarded to the network
  - superseeded by [gluon-ebtables-limit-arp](https://gluon.readthedocs.io/en/v2018.1.x/package/gluon-ebtables-limit-arp.html) added in gluon v2018.1

- gluon-ebtables-filter-multicast-ffmuc
  - Filters multicast to not be forwarded to the network
  - superseeded by [gluon-ebtables-filter-multicast](https://gluon.readthedocs.io/en/v2018.1.x/package/gluon-ebtables-filter-multicast.html) added in gluon v2018.1
