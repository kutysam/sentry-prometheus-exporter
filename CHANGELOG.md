# Changelog

## [v0.6.0](https://github.com/italux/sentry-prometheus-exporter/tree/v0.6.0) (2021-10-16)

[Full Changelog](https://github.com/italux/sentry-prometheus-exporter/compare/v0.5...v0.6.0)

**Implemented enhancements:**

- Password protection via HTTP basic authentication [\#34](https://github.com/italux/sentry-prometheus-exporter/pull/34) ([italux](https://github.com/italux))

## [v0.5](https://github.com/italux/sentry-prometheus-exporter/tree/v0.5) (2021-10-13)

[Full Changelog](https://github.com/italux/sentry-prometheus-exporter/compare/v0.4.1...v0.5)

**Implemented enhancements:**

- Client keys rate limit [\#32](https://github.com/italux/sentry-prometheus-exporter/pull/32) ([Set3007](https://github.com/Set3007))

**Fixed bugs:**

- ConnectionResetError: \[Errno 104\] Connection reset by peer [\#8](https://github.com/italux/sentry-prometheus-exporter/issues/8)

**Closed issues:**

- AttributeError: 'str' object has no attribute 'get' [\#16](https://github.com/italux/sentry-prometheus-exporter/issues/16)

## [v0.4.1](https://github.com/italux/sentry-prometheus-exporter/tree/v0.4.1) (2021-10-12)

[Full Changelog](https://github.com/italux/sentry-prometheus-exporter/compare/v0.4.0...v0.4.1)

**Closed issues:**

- incorrect sentry\_events\_total count [\#27](https://github.com/italux/sentry-prometheus-exporter/issues/27)

**Merged pull requests:**

- pip: bump flask from 2.0.1 to 2.0.2 [\#31](https://github.com/italux/sentry-prometheus-exporter/pull/31) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v0.4.0](https://github.com/italux/sentry-prometheus-exporter/tree/v0.4.0) (2021-10-10)

[Full Changelog](https://github.com/italux/sentry-prometheus-exporter/compare/v0.3.0...v0.4.0)

**Fixed bugs:**

- Exporter queries Sentry API too fast and crashes [\#21](https://github.com/italux/sentry-prometheus-exporter/issues/21)
- fix\(sentry\): incorrect sentry\_events\_total count [\#28](https://github.com/italux/sentry-prometheus-exporter/pull/28) ([NMFR](https://github.com/NMFR))

**Closed issues:**

- Not correctly managing project list pagination. [\#29](https://github.com/italux/sentry-prometheus-exporter/issues/29)

**Merged pull requests:**

- fix\(sentry\): projects pagination [\#30](https://github.com/italux/sentry-prometheus-exporter/pull/30) ([NMFR](https://github.com/NMFR))

## [v0.3.0](https://github.com/italux/sentry-prometheus-exporter/tree/v0.3.0) (2021-09-21)

[Full Changelog](https://github.com/italux/sentry-prometheus-exporter/compare/v0.2.2...v0.3.0)

**Fixed bugs:**

- Handle Sentry HTTP errors [\#22](https://github.com/italux/sentry-prometheus-exporter/pull/22) ([lululombard](https://github.com/lululombard))

**Closed issues:**

- Specify the project names that I want to get metrics. [\#14](https://github.com/italux/sentry-prometheus-exporter/issues/14)

**Merged pull requests:**

- pip: bump flask from 1.0.2 to 2.0.1 [\#26](https://github.com/italux/sentry-prometheus-exporter/pull/26) ([dependabot[bot]](https://github.com/apps/dependabot))
- pip: bump prometheus-client from 0.9.0 to 0.11.0 [\#25](https://github.com/italux/sentry-prometheus-exporter/pull/25) ([dependabot[bot]](https://github.com/apps/dependabot))
- pip: bump requests from 2.25.1 to 2.26.0 [\#24](https://github.com/italux/sentry-prometheus-exporter/pull/24) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v0.2.2](https://github.com/italux/sentry-prometheus-exporter/tree/v0.2.2) (2021-05-30)

[Full Changelog](https://github.com/italux/sentry-prometheus-exporter/compare/v0.2.1...v0.2.2)

**Merged pull requests:**

- Re-add deleted projects check [\#15](https://github.com/italux/sentry-prometheus-exporter/pull/15) ([bmistry12](https://github.com/bmistry12))
- YAML Lint Formatter [\#13](https://github.com/italux/sentry-prometheus-exporter/pull/13) ([italux](https://github.com/italux))

## [v0.2.1](https://github.com/italux/sentry-prometheus-exporter/tree/v0.2.1) (2021-03-27)

[Full Changelog](https://github.com/italux/sentry-prometheus-exporter/compare/v0.2...v0.2.1)

**Closed issues:**

- Allow for user configuration of required metrics [\#9](https://github.com/italux/sentry-prometheus-exporter/issues/9)

**Merged pull requests:**

- Black Code Formatter [\#12](https://github.com/italux/sentry-prometheus-exporter/pull/12) ([italux](https://github.com/italux))
- Add Github Actions Workflow [\#11](https://github.com/italux/sentry-prometheus-exporter/pull/11) ([italux](https://github.com/italux))

## [v0.2](https://github.com/italux/sentry-prometheus-exporter/tree/v0.2) (2021-03-24)

[Full Changelog](https://github.com/italux/sentry-prometheus-exporter/compare/v0.1.1...v0.2)

**Implemented enhancements:**

- Allow for user configuration of required metrics [\#10](https://github.com/italux/sentry-prometheus-exporter/pull/10) ([bmistry12](https://github.com/bmistry12))

## [v0.1.1](https://github.com/italux/sentry-prometheus-exporter/tree/v0.1.1) (2021-03-21)

[Full Changelog](https://github.com/italux/sentry-prometheus-exporter/compare/v0.1...v0.1.1)

**Merged pull requests:**

- Catering for fetches of non existent resources [\#7](https://github.com/italux/sentry-prometheus-exporter/pull/7) ([bmistry12](https://github.com/bmistry12))
- Add some configuration samples [\#6](https://github.com/italux/sentry-prometheus-exporter/pull/6) ([italux](https://github.com/italux))

## [v0.1](https://github.com/italux/sentry-prometheus-exporter/tree/v0.1) (2021-02-19)

[Full Changelog](https://github.com/italux/sentry-prometheus-exporter/compare/1bf7b07c407f60dc25b734b58383ba7f381eb865...v0.1)

**Merged pull requests:**

- Add some documentation [\#4](https://github.com/italux/sentry-prometheus-exporter/pull/4) ([italux](https://github.com/italux))
- Add docker support [\#3](https://github.com/italux/sentry-prometheus-exporter/pull/3) ([italux](https://github.com/italux))
- Sentry Prometheus Exporter v0.1 [\#2](https://github.com/italux/sentry-prometheus-exporter/pull/2) ([italux](https://github.com/italux))
- Simple Sentry API library [\#1](https://github.com/italux/sentry-prometheus-exporter/pull/1) ([italux](https://github.com/italux))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
