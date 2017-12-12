# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)


## Gaprindashvili RC

### Added
- Add translations [(#108)](https://github.com/ManageIQ/manageiq-providers-hawkular/pull/108)

### Fixed
- Fix RemoveDatasource operation notification [(#112)](https://github.com/ManageIQ/manageiq-providers-hawkular/pull/112)

## Gaprindashvili Beta2

### Fixed
- Middleware server reports fixed after introducing STI on MiddlewareServer [(#106)](https://github.com/ManageIQ/manageiq-providers-hawkular/pull/106)
- Re-add remove datasource operation [(#111)](https://github.com/ManageIQ/manageiq-providers-hawkular/pull/111)

## Gaprindashvili Beta1

### Added
- Add support for Messaging and Transactions conditions  [(#70)](https://github.com/ManageIQ/manageiq-providers-hawkular/pull/70)
- Add support to Datasource and Web Sessions conditions [(#68)](https://github.com/ManageIQ/manageiq-providers-hawkular/pull/68)
- Support for timeline events for MW Server and MW domain power operations [(#61)](https://github.com/ManageIQ/manageiq-providers-hawkular/pull/61)
- Adding JDR report model class with logic to generate reports [(#30)](https://github.com/ManageIQ/manageiq-providers-hawkular/pull/30)
- Adding link to the vm also for the servers running in the domain mode [(#31)](https://github.com/ManageIQ/manageiq-providers-hawkular/pull/31)

### Fixed
- Fixes event handling and generation of alternate machine in parser [(#59)](https://github.com/ManageIQ/manageiq-providers-hawkular/pull/59)
- Fixes VMs and MW servers not being cross-linked when GUIDs differ only because of dashes [(#37)](https://github.com/ManageIQ/manageiq-providers-hawkular/pull/37)
- Fix mutable flag in hawkinit scripts [(#47)](https://github.com/ManageIQ/manageiq-providers-hawkular/pull/47)
- Changing bracket syntax for method/attribute syntax in update_alerts [(#39)](https://github.com/ManageIQ/manageiq-providers-hawkular/pull/39)
- Client error name format unification [(#26)](https://github.com/ManageIQ/manageiq-providers-hawkular/pull/26)
