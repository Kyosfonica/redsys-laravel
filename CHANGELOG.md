# Changelog

All Notable changes to `Redsys` will be documented in this file
## 1.2 (2017-09-02)

### Added
- Update to Laravel 5.5 auto package discovery 

### Deprecated
- Nothing

### Fixed
- Nothing

## 1.1.3 (2017-06-29)

### Added
- Updated Tpv.php, added new methods: setPan, setExpiryDate and setCVV2 

### Deprecated
- Nothing

### Fixed
- Nothing

## 1.1.2 (2017-01-27)

### Added
- Updated Tpv.php - Changed the function mcrypt_encrypt to openssl_encrypt, with the new updated of PHP 7.1 the function mcrypt_encrypt is deprecated.

### Deprecated
- Nothing

### Fixed
- Nothing

## 1.1.1 (2016-10-27)

### Added
- Updated Tpv.php added new methods for pay for reference

### Deprecated
- Nothing

### Fixed
- Nothing

## 1.1 (2016-10-20)

### Added
- Updated to Larevel 5.2/5.3

### Deprecated
- Nothing

### Fixed
- Nothing

## 1.0.5 (2016-06-11)

### Added
- Updated class Tpv.php [added new option in setAttributesSubmit]

### Deprecated
- Nothing

### Fixed
- Nothing

## 1.0.4 (2016-02-25)

### Added
- Updated class Tpv.php

	- New method: getParameters
	- Text: T = Pago con Tarjeta + iupay , R = Pago por Transferencia, D = Domiciliacion, C = Sólo Tarjeta (mostrará sólo el formulario para datos de tarjeta)] por defecto es T

### Deprecated
- Nothing

### Fixed
- Nothing

## 1.0.3 (2015-11-26)

### Added
- In config.php new parameter (key)
- New method for convert correctly price.
 
### Deprecated
- Nothing

### Fixed
- Nothing

### Removed
- In Tpv.php removed injection by default the config.

### Security
- Nothing

## 1.0.0 (2015-11-15)

### Added
- First version, support sha256.

### Deprecated
- Nothing

### Fixed
- Nothing

### Removed
- Nothing

### Security
- Nothing
