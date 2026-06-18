# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 1.0.0 - 2025-06-18

### Added

- Initial release of `@krizad/thai-financial-holiday-helper`
- `isHoliday(date)` — check if a date is a Thai financial institution holiday
- `isBusinessDay(date)` — check if a date is a business day (not weekend or holiday)
- `getHoliday(date)` — get holiday details for a specific date
- `getHolidays(year?, month?)` — list holidays with optional year/month filter
- `getNextHoliday(date?)` — find the next holiday from a given date
- `getHolidaysInRange(start, end)` — list holidays within a date range
- `addBusinessDays(date, days)` — add/subtract business days from a date
- `getBusinessDaysInRange(start, end)` — list all business days in a range
- TypeScript types: `BOTHoliday`, `DateInput`
- Holiday data synced from Bank of Thailand (ธปท.) API