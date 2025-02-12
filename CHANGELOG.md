# Changelog

[PyPI History][1]

[1]: https://pypi.org/project/demisto-py/#history

## 2.0.5
Remove unsupported user/password authentication option.

## 2.0.4
Fix missing dependency (tzlocal).

## 2.0.3
* Fix issue in `generic_request` where body was being ignored ([#20](https://github.com/demisto/demisto-py/issues/20)) .
* Add `content_type` and `accept` parameters to `generic_request`.
* Fix `datetime` object formatting to include timezone offset as specified in RFC 3339.

## 2.0.2
* Support for environment variables when configuring the client.
* Update `create_incident` with CustomFields and removed invalid `attachment` parameter.
* Add `incident_file_upload` method for uploading files to an incident.

## 2.0.1
Improved the changelog and documentation.

## 2.0.0
Initial release of new Swagger based API for Demisto Server 4.5.0 and up.

## 1.0.0
Deprecated: demisto-py 1.x is officially in maintenance-mode only and can be obtained at: https://github.com/demisto/demisto-py/releases .
