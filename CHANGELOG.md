cron Cookbook CHANGELOG
=======================
This file is used to list changes made in each version of the cron cookbook.

v1.3.7 (2014-04-10)
-------------------
### New feature
- **[COOK-4507](https://tickets.opscode.com/browse/COOK-4507)** - New version of cron cookbook removed ability to use @ fields.

v1.3.6 (2014-04-09)
-------------------
- [COOK-4337] fixing validations


v1.3.4 (2014-04-09)
-------------------
- Reverting [COOK-4337] - cron cookbook does no input validation


v1.3.2 (2014-03-27)
-------------------
- [COOK-4337] - cron cookbook does no input validation
- [COOK-4229] - Support the Gentoo package


v1.3.0 (2014-02-25)
-------------------
### New Feature
- **[COOK-4112](https://tickets.opscode.com/browse/COOK-4112)** - Solaris 11 support for cron

### Bug
- **[COOK-3813](https://tickets.opscode.com/browse/COOK-3813)** - Add metadata for recipes in the cron cookbook


v1.2.8
------
### Bug
- **[COOK-3452](https://tickets.opscode.com/browse/COOK-3452)** - Add support for raspbian platform

v1.2.6
------
### Improvement
- **[COOK-3005](https://tickets.opscode.com/browse/COOK-3005)** - Remove blankline in template

v1.2.4
------
- [COOK-3058]: simplify conditionals in cron recipe

v1.2.2
------
- [COOK1829] - `cron_d` LWRPtemplate should imply cron cookbook by default

v1.2.0
------
- [COOK-938] - don't default to upgrading cron and fix rhel6 package name
- [COOK-1622] - add LWRP for cron.d files

v1.0.4
------
- [COOK-1514] - Cron cookbook manages wrong service name on SuSE

v1.0.0
------
- [COOK-1124] - add RHEL platform support
