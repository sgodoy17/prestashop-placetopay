# Changelog

### Added
- Allowed set a Custom Connection URL to connect to payment service in PlacetoPay

### Fixed
- Fix bug in Windows System with Apache Server installed (Separator)
- Fix bug in English translations files

### Updated
- Update message trace on development and improve code typehint and vars name

## [3.1.0] - 2018-03-11

### Added
- Add makefile with docker
- Add validation in notification to signature
- Add extra security, to show setup is necesary send last 5 characteres of login to show data
- Add skipResult setup to skip last screen in payment process on payment
- Add Placetopay brand in PS >= 1.7 in payment options form
- Add validation to execute sonda process, from browser not is available, only CLI

### Fixed
- Fix bug in way to get URL base
- Fix bug when transaction not is approved not update reason and reaso…
- Fix bug updating description in payments rejected (error in bd)
- Fix bug in value assigned of stock reinject on update
- Fix errors when module is re-install, catch error generate by rename columns
- Fix error when module is executed but it is not installed yet (from sonda process)
- Fix bug in installation on PS 1.7.2.5, logo.png was change path
- Fix Skip class when some are not found in PS 1.7 loader

### Updated
- Update dependency redirection from 0.4.1 to 0.4.2
- Update dependencies guzzle from 6.2 to 6.3
- Update message trace on development
- Update translation changing Place to Pay -> PlacetoPay

### Created
- Create CONTRIBUTING.md
- Create LICENSE

## [3.0.2] - 2018-01-10

### Fixed
- Fix bug in notification process, column name error

## [3.0.1] - 2017-12-13

### Fixed
- Fix bug in utf8 translations in spanish in some installations in Prestashop < 1.7
 
## [3.0.0] - 2017-12-06

### Added
- Add compatibility with Prestashop >= 1.7

## [2.6.4] - 2017-12-01

### Fixed
- Fixed bug in Windows Server Systems