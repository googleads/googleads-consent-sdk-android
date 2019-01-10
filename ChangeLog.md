Android Consent SDK Change Log
===============================

### Version 1.0.7
- Fixed an issue with `Locale` causing crashes on certain Samsung devices.

### Version 1.0.6
- Removed restriction on using Google rendered consent form with
the commonly used set of ad technology providers.

### Version 1.0.5
- Removed 12 ad technology provider limit for Google rendered consent form.

### Version 1.0.4
- Updated consent form to have transparent background.
- Fixed crash on older devices caused by static initialization.

### Version 1.0.3
- Updated consent information update requests to be made over secure
connections.
- Added compatibility for Java 7.

### Version 1.0.2
- Fixed issue where casting app icon to a bitmap crashes
when app uses an adaptive icon.
- Removed implicit permissions.
- Added ProGuard configuration rules.

### Version 1.0.1
- Fixed NPE when no ad networks are returned in consent update
response.

### Version 1.0.0
- Initial release.
