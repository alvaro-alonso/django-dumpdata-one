# Change log

## [0.8.4] - 2021-04-07
- check and test for Django 3.2

## [0.8.3] - 2020-07-17
### Fixed
- roll back to .values method to retrieve field values
- a simple hack to get file url

## [0.8.2] - 2020-07-01
### Added
- dump full file/image url `--full_url={field_name},{other_file_name}`
- limit number of records `--limit={number}`

### Changed
- rewrite way to retrieve a field value

## [0.8.1] - 2020-06-02
### Added
- dump all model fields with argument `--fields=*`

### Fixed
- multiple fields in order argument

## [0.8] - 2020-05-22

Initial public release