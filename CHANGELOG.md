# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [Unreleased]

...

## [0.1.5] - 2019-07-12

### Fixed

- Fixed seed randomisation bug (caused by static initialization) when generating multiple copies of a dataset (e.g. generating Biochemistry twice within the same process)

## [0.1.4] - 2019-07-02

### Changed
- CI changes only (no changes to codebase)

## [0.1.3] - 2019-07-02

### Changed

- Patient birth dates now go from 1914 (Person.MinimumYearOfBirth) allowing for patients aged up to 100 years

[Unreleased]: https://github.com/HicServices/BadMedicine/compare/v0.1.5...develop
[0.1.5]: https://github.com/HicServices/BadMedicine/compare/v0.1.4...v0.1.5
[0.1.4]: https://github.com/HicServices/BadMedicine/compare/v0.1.3...v0.1.4
[0.1.3]: https://github.com/HicServices/BadMedicine/compare/0.0.1.2...v0.1.3