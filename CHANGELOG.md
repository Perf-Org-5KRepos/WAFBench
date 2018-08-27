# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project does adhere to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] - 2018-08-01
### Added
- [wb.c](./wb/wb.c) Add a feature of sending requests ordered by timestamp

### Removed
- [wb.c](./wb/wb.c) Remove useless comments

### Fixed
- [wb.c](./wb/wb.c) Fix compiling warning
- [wb.c](./wb/wb.c) Fix typo
- [wb.c](./wb/wb.c) Fix crash bug of unspecified log
- [wb.c](./wb/wb.c) Fix carsh bug of sending huge packets


## [1.0.0] - 2018-07-16
### Added
- [README.md](./README.md) describes WAF Bench tool suits probject.
- [CHANGELOG.md](./CHANGELOG.md) to track changes.
- [wb](./wb/README.md), a superset of [ab](https://github.com/CloudFundoo/ApacheBench-ab) to make benchmarking WAF more easily.
- `./sample` to show demos of WAF Bench tool suits. Currently, it only has examples for wb.

### Changed
- Revise the Makefile for apr and wb to support wb new feature.