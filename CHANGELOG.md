# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [1.0.5] - 2017-11-13
### Changed
- Use `Time` over `Date` class for auto-generating the year.


## [1.0.3] - 2017-11-11
### Changed
- Fix issue where `Sign` wasn't able to locate license templates.
- Update specs.


## [1.0.2] - 2017-11-03
### Changed
- Sign will check if a license file exists before creating/overwriting.
- Alias for options and flags.


## [1.0.1] - 2017-11-02
### Changed
- Fix issue where some licenses weren't being fetched.
- Overall refactor of code to improve code readability.


## [1.0.0] - 2017-11-02
### Added
- More licenses.
### Changed
- Update README.


## [0.6.0] - 2017-11-02
### Added
- Licenses assemble! Look at the entire list with `sign --list`.


## [0.5.0] - 2017-11-01
### Added
- Runner is able to fetch and generate a license.
- Runner saves generated licenses into current project directory.
- Option to display version number.
- Tests for `Sign::Fetcher`.
- Tests for `Sign::Generator`.
### Changed
- Add tests for `Sign::Runner#create_license`.


## [0.2.0] - 2017-10-28
### Added
- Cli prompt in `runner.rb`.
- Return help information using `--help`.
- Tests for cli initialization and help information.
- Create `TestHelper` module to capture stdout and stderr.
### Changed
- Rename project `lc -> sign`.


## [0.1.0] - 2017-10-25
- Create initial project structure.
