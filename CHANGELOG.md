#   Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).


##  [Unreleased]

_tbd_


##  [0.7] – 2017-09-02


### Added

-   Support for Red Hat Enterprise Linux (RHEL) 7.4
-   Show version and release date of i-doit
-   Clean up VHost directory just before the installation of i-doit
-   Be more friendly on a RHEL/CentOS system


### Changed

-   More checks for required binaries


### Fixed

-   Missing chronic on RHEL
-   Parse updates.xml properly for latest i-doit version
-   Fixed broken name of temporary directory


##  [0.6] – 2017-07-24


### Added

-   Get primary IP address on all supported operating systems
-   Install SOAP module for PHP
-   Enable Apache module mod_access_compat under SLES 12 SP2
-   Create the first backup automatically
-   Install "chronic" under SLES


##  [0.5] – 2017-07-13


### Added

-   Support for SLES 12 SP2
-   Scripts to backup and restore i-doit
-   Dedicated MariaDB user for i-doit
-   Require successful installation of i-doit before deploying scripts


##  [0.4] – 2017-07-12


### Added

-   Deploy cron jobs and an easy-to-use CLI tool for the i-doit controller


##  [0.3] – 2017-07-10


### Added

-   Support for Red Hat Enterprise Linux (RHEL) 7.3
-   Support for CentOS 7.3
-   Soft requirement to use a x86 64 bit OS
-   Question whether to reboot an Ubuntu OS
-   Warning to read the documentation
-   Warning not to edit the built-in configuration
-   Recommend Debian GNU/Linux 9 "Stretch"


##  [0.2] – 2017-07-07


### Added

-   Support for Ubuntu 16.10 and 17.04


##  0.1 – 2017-07-07

Initial release


[Unreleased]: https://github.com/bheisig/i-doit-scripts/compare/0.7...HEAD
[0.7]: https://github.com/bheisig/i-doit-scripts/compare/0.6...0.7
[0.6]: https://github.com/bheisig/i-doit-scripts/compare/0.5...0.6
[0.5]: https://github.com/bheisig/i-doit-scripts/compare/0.4...0.5
[0.4]: https://github.com/bheisig/i-doit-scripts/compare/0.3...0.4
[0.3]: https://github.com/bheisig/i-doit-scripts/compare/0.2...0.3
[0.2]: https://github.com/bheisig/i-doit-scripts/compare/0.1...0.2