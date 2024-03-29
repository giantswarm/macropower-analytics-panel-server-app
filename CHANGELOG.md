# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.6.3] - 2023-10-12

### Removed

- Remove Kyverno Policy Exceptions and fix security issues instead.

## [0.6.2] - 2023-10-02

### Changed

- Add condition for PSP installation in helm chart.

## [0.6.1] - 2023-06-27

### Fixed

- Fix Kyverno Policy Exceptions namespace.

## [0.6.0] - 2023-06-27

### Added

- Add push to `capz-app-collection` to circleci.
- Add Kyverno Policy Exceptions.

## [0.5.0] - 2023-06-15

### Removed

- Remove pull secret.

## [0.4.6] - 2023-06-02

### Changed

- Add team label.
- 
### Removed

- Stop pushing to `openstack-app-collection`.

## [0.4.5] - 2023-03-02

### Added

- Add additional annotations on all `ingress` objects to support DNS record creation via `external-dns`

## [0.4.4] - 2023-01-10

### Changed

- Push to `gcp-app-collection`

## [0.4.3] - 2022-11-08

### Changed

- Push to `capa-app-collection`, `cloud-director-app-collection` and `vsphere-app-collection`.

## [0.4.2] - 2022-06-13

### Changed

- Push to `openstack-app-collection`.

## [0.4.1] - 2021-09-03

### Fixed

- Fix Ingress api version.

## [0.4.0] - 2021-09-02

### Changed

- Move `ServiceMonitor.spec.metricRelabelings` out to config to avoid enforcing
  PII redacting onto all chart users.

## [0.3.0] - 2021-08-19

### Added

- Add support for overriding server args through Helm values.

## [0.2.1] - 2021-08-19

### Fixed

- Add missing labeling schema to service monitor.

## [0.2.0] - 2021-08-12

### Added

- Add Ingress auth using Grafana authentication.
- Add ServiceMonitor for Prometheus scrape to take place.

### Changed

- Restrict ingress to /write

## [0.1.1] - 2021-07-29

### Changed

- Regress ingress to v1beta1.

## [0.1.0] - 2021-07-29

### Added

- Add initial app version.

[Unreleased]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.6.3...HEAD
[0.6.3]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.6.2...v0.6.3
[0.6.2]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.6.1...v0.6.2
[0.6.1]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.6.0...v0.6.1
[0.6.0]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.5.0...v0.6.0
[0.5.0]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.4.6...v0.5.0
[0.4.6]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.4.5...v0.4.6
[0.4.5]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.4.4...v0.4.5
[0.4.4]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.4.3...v0.4.4
[0.4.3]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.4.2...v0.4.3
[0.4.2]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.4.1...v0.4.2
[0.4.1]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.4.0...v0.4.1
[0.4.0]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.2.1...v0.3.0
[0.2.1]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.1.1...v0.2.0
[0.1.1]: https://github.com/giantswarm/macropower-analytics-panel-server-app/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/giantswarm/macropower-analytics-panel-server-app/releases/tag/v0.1.0
