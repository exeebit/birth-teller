# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [0.2.1] - 2025-08-24

### Removed

- Removed unused dependencies

---

## [0.2.0] - 2025-08-21

### Added

- Optional short flags for CLI: `-n`, `-d`, `-m`, `-y`
- Improved date validation to support leap years
- Zodiac Sign
  
### Fixed

- CLI issue

### Removed

- Extra unnecessary info (hour, minute seconds)

---

## [0.1.0] - 2025-08-20

### Added

- Initial release of **Birth Teller Machine (BTM)**
- Calculate age in years, weeks, and days
- Determine the day of the week you were born
- Zodiac sign calculation
- Command-line interface (CLI) using `argparse`
- Support for full month names, 3-letter abbreviations, and numeric months
