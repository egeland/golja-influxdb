##2015-09-13 - Release 1.1.0
###Summary
- Add support for 0.9.3 influxdb new config parameters
- Fix graphite template bug
- Default install version 0.9.3 - (we can't use latest version due to how influxdb is packaged)

Special tnx to Pedro González Serrano - NITEMAN for the graphite and 0.9.3 config template fix

##2015-08-25 - Release 1.0.1
###Summary
Improved the documentation and the module description

##2015-08-25 - Release 1.0.0
###Summary
Major module rewrite to support influxdb 0.9.X. For more info please check the README.md

##2015-01-25 - Release 0.1.2
###Summary

- bugfix: specify the correct config file, because looks like the global settings
are defined in /opt/influxdb/shared/config.toml
- bugfix: added missing RedHat/CentOS params to make it work properly (TODO: add system spec tests)

##2015-01-25 - Release 0.1.1
###Summary

bugfix: correct package_source for RedHat osfamily

##2015-01-25 - Release 0.1.0
###Summary

First public release.
