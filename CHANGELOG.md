# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Support for handlebars templates.
- Page borders `{ top: '1.9 cm', bottom: '1.9 cm', left: '1.9 cm', right: '1.9 cm' }`.
- Header and Footer template support.
- Support for Table of contents (TOCs). [#21](https://github.com/isneezy/pdf-generator-service/issues/18)
- `--export-tagged-pdf` chromium launc args to produce tagged PDFs, better for accessibility.

### Changed
- Start using edge repository for the docker image, so we can get the most recent chromium build.
- Start using docker multistage build to reduce image size.

## [0.1.0] - 2020-09-21

### Added
- This CHANGELOG file to hopefully tell the project story.
- Github actions for continuous integration (CI).
- Dockerfile & automated builds and releases.
- /generate - route to generate PDF files based on HTML input.