# Change Log
All notable changes to the Azure Pipelines extension will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/). Versioning follows an internal Azure DevOps format that is not compatible with SemVer.

## 1.152.0
### Added
- Support for `stages` and other new schema

## 1.147.2
### Fixed
- Partial support for expressions

## 1.147.1
### Fixed
- Support aliases for task inputs

## 1.145.2
### Fixed
- Identify required task inputs

## 1.145.1
### Fixed
- updated to latest tasks in schema
- allow expressions in some properties, including "condition"

## 1.145.0
### Fixed
- link to correct GitHub repo in package.json
- several YAML correctness bugs

## 1.144.0
### Fixed
- LF vs CRLF line endings caused the validator to lose its place
- removed several invalid auto-complete suggestions
- enforce first property in some constructs

## 1.141.0 - 2018-09-05
### Added
- Initial release
- Syntax highlighting for Azure Pipelines files
- Intellisense for Azure Pipelines files
