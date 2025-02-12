# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## 2024-03-29 - 1.50.0

### Changed

- Move API client and authorization to a separate module

## 2024-02-13 - 1.49.2

### Changed

- Change event_lags metrics from Histogram to Gauge

## 2023-12-20 - 1.49.1

### Fixed

- Declare pagination_limit and rate_limit parameters in the trigger configuration

## 2023-12-18 - 1.49

### Fixed

- In case if there is no last message, empty string for ordering

## 2023-12-18 - 1.48

### Added

- Use latest message datetime during next execution

## 2023-11-23 - 1.47

### Added

- Collecting events lag metric

## 2023-11-22 - 1.46

### Changed

- Upgrade dependencies: Sekoia-automation-SDK 1.8.1
