<a name="4.1.1"></a>
## [4.1.1](https://github.com/brightcove/videojs-errors/compare/v4.1.0...v4.1.1) (2018-07-05)

### Chores

* generator v6 ([#122](https://github.com/brightcove/videojs-errors/issues/122)) ([846d151](https://github.com/brightcove/videojs-errors/commit/846d151))

<a name="4.1.0"></a>
# [4.1.0](https://github.com/brightcove/videojs-errors/compare/v4.0.0...v4.1.0) (2018-05-08)

### Features

* add standard VERSION property ([#120](https://github.com/brightcove/videojs-errors/issues/120)) ([c475d12](https://github.com/brightcove/videojs-errors/commit/c475d12))

<a name="4.0.0"></a>
# [4.0.0](https://github.com/brightcove/videojs-errors/compare/v3.1.0...v4.0.0) (2018-05-02)

### Features

* Add timeout getter/setter ([#114](https://github.com/brightcove/videojs-errors/issues/114)) ([cb45723](https://github.com/brightcove/videojs-errors/commit/cb45723))
* drop v5 support ([#119](https://github.com/brightcove/videojs-errors/issues/119)) ([f4440c1](https://github.com/brightcove/videojs-errors/commit/f4440c1))

### Bug Fixes

* make the plugin ready for videojs 7 ([#117](https://github.com/brightcove/videojs-errors/issues/117)) ([8d96f2a](https://github.com/brightcove/videojs-errors/commit/8d96f2a)), closes [#116](https://github.com/brightcove/videojs-errors/issues/116)
* Restart timeout monitor if playing when reinitialised ([#113](https://github.com/brightcove/videojs-errors/issues/113)) ([af868ed](https://github.com/brightcove/videojs-errors/commit/af868ed))

### Documentation

* **README:** Add usage npm/bundler usage ([#108](https://github.com/brightcove/videojs-errors/issues/108)) ([ec86764](https://github.com/brightcove/videojs-errors/commit/ec86764))
* **README:** fix typo ([ec724b7](https://github.com/brightcove/videojs-errors/commit/ec724b7))


### BREAKING CHANGES

* drop v5 support.

<a name="3.1.0"></a>
# [3.1.0](https://github.com/brightcove/videojs-errors/compare/v1.0.0...v3.1.0) (2017-12-13)

### Features

* add custom error for flashls crossdomain errors ([#111](https://github.com/brightcove/videojs-errors/issues/111)) ([9d20fbd](https://github.com/brightcove/videojs-errors/commit/9d20fbd))
* Add Czech translation ([#106](https://github.com/brightcove/videojs-errors/issues/106)) ([3cb9c1e](https://github.com/brightcove/videojs-errors/commit/3cb9c1e))
* Add new custom errors and allow defining custom errors at runtime ([#90](https://github.com/brightcove/videojs-errors/issues/90)) ([4bd0cd9](https://github.com/brightcove/videojs-errors/commit/4bd0cd9))
* Change codes of recently-added errors, allow type and code to be shared, and add `getAll()` method. ([#96](https://github.com/brightcove/videojs-errors/issues/96)) ([f39c0f6](https://github.com/brightcove/videojs-errors/commit/f39c0f6))

### Bug Fixes

* Fix tests for video.js 6 ([#77](https://github.com/brightcove/videojs-errors/issues/77)) ([0d71164](https://github.com/brightcove/videojs-errors/commit/0d71164))
* Resolve an issue where 'error' events triggered on the player during contrib-ads playback would not be recognized. ([#109](https://github.com/brightcove/videojs-errors/issues/109)) ([3b48430](https://github.com/brightcove/videojs-errors/commit/3b48430))
* show spinner if player has stalled ([#104](https://github.com/brightcove/videojs-errors/issues/104)) ([a89513f](https://github.com/brightcove/videojs-errors/commit/a89513f))

### Chores

* **package:** update browserify to version 13.3.0 ([#58](https://github.com/brightcove/videojs-errors/issues/58)) ([e61edb6](https://github.com/brightcove/videojs-errors/commit/e61edb6))
* **package:** update karma to version 1.4.1 ([#69](https://github.com/brightcove/videojs-errors/issues/69)) ([7cd5e45](https://github.com/brightcove/videojs-errors/commit/7cd5e45))
* **package:** update node-sass to version 4.5.0 ([#70](https://github.com/brightcove/videojs-errors/issues/70)) ([f7d7793](https://github.com/brightcove/videojs-errors/commit/f7d7793))
* **package:** update npm-run-all to version 3.1.2 ([#48](https://github.com/brightcove/videojs-errors/issues/48)) ([0b3f13d](https://github.com/brightcove/videojs-errors/commit/0b3f13d))
* **package:** update portscanner to version 2.1.1 ([#47](https://github.com/brightcove/videojs-errors/issues/47)) ([b83b979](https://github.com/brightcove/videojs-errors/commit/b83b979))
* **package:** update shelljs to version 0.7.6 ([#60](https://github.com/brightcove/videojs-errors/issues/60)) ([9b966f6](https://github.com/brightcove/videojs-errors/commit/9b966f6))
* Add translations for some new strings. ([#101](https://github.com/brightcove/videojs-errors/issues/101)) ([b3dc97a](https://github.com/brightcove/videojs-errors/commit/b3dc97a))
* Update tooling using generator v5 prerelease. ([#99](https://github.com/brightcove/videojs-errors/issues/99)) ([b0e53e5](https://github.com/brightcove/videojs-errors/commit/b0e53e5))
* update travis ([#71](https://github.com/brightcove/videojs-errors/issues/71)) ([86d7807](https://github.com/brightcove/videojs-errors/commit/86d7807))

### Code Refactoring

* Updates for Video.js 6.0 compatibility. ([48ed04a](https://github.com/brightcove/videojs-errors/commit/48ed04a))


### BREAKING CHANGES

* Removed Bower support.
* Changed the codes of recently-added errors; so, they will no avoid collisions more reliably with 1.x implementations.

<a name="3.0.3"></a>
## [3.0.3](https://github.com/brightcove/videojs-errors/compare/v3.0.2...v3.0.3) (2017-09-06)

### Features

* Add Czech translation ([#106](https://github.com/brightcove/videojs-errors/issues/106)) ([3cb9c1e](https://github.com/brightcove/videojs-errors/commit/3cb9c1e))

### Bug Fixes

* Resolve an issue where 'error' events triggered on the player during contrib-ads playback would not be recognized. ([#109](https://github.com/brightcove/videojs-errors/issues/109)) ([3b48430](https://github.com/brightcove/videojs-errors/commit/3b48430))

<a name="3.0.2"></a>
## [3.0.2](https://github.com/brightcove/videojs-errors/compare/v3.0.1...v3.0.2) (2017-06-08)

### Bug Fixes

* show spinner if player has stalled ([#104](https://github.com/brightcove/videojs-errors/issues/104)) ([a89513f](https://github.com/brightcove/videojs-errors/commit/a89513f))

<a name="3.0.1"></a>
## [3.0.1](https://github.com/brightcove/videojs-errors/compare/v3.0.0...v3.0.1) (2017-05-22)

### Chores

* Add translations for some new strings. ([#101](https://github.com/brightcove/videojs-errors/issues/101)) ([b3dc97a](https://github.com/brightcove/videojs-errors/commit/b3dc97a))

<a name="3.0.0"></a>
# [3.0.0](https://github.com/brightcove/videojs-errors/compare/v1.0.0...v3.0.0) (2017-05-19)

### Chores

* Update tooling using generator v5 prerelease. ([#99](https://github.com/brightcove/videojs-errors/issues/99)) ([b0e53e5](https://github.com/brightcove/videojs-errors/commit/b0e53e5))

### BREAKING CHANGES

* Removed Bower support.

## 2.0.2 (2017-05-15)
* Fixed some tooling issues, including missing `dist/lang` files.

## 2.0.1 (2017-05-15)
* Fixed mis-configured `package.json` fields.

## 2.0.0 (2017-05-15)
* @misteroneill Move off of Spellbook for now and add pkg.module. ([#95](https://github.com/brightcove/videojs-errors/pull/95))
* @misteroneill __BREAKING CHANGE__: Change codes of recently-added errors, allow type and code to be shared, and add `getAll()` method. ([#95](https://github.com/brightcove/videojs-errors/pull/95))

## 1.3.2 (2017-04-24)
* @forbesjo Added option to disable watching progress events ([#91](https://github.com/brightcove/videojs-errors/pull/91))

## 1.3.1 (2017-04-19)
* @misteroneill Fix size detection to account for players that have no configured dimensions ([#92](https://github.com/brightcove/videojs-errors/pull/92))

## 1.3.0 (2017-04-18)
* @misteroneill Add new custom errors and an `extend` method to customize errors at runtime ([#90](https://github.com/brightcove/videojs-errors/pull/90))

## 1.2.0 (2017-02-21)
* @gfviegas Add support for Portuguese ([#42](https://github.com/brightcove/videojs-errors/pull/42))
* @bc-paul Allow errors to be non-dismissible ([#54](https://github.com/brightcove/videojs-errors/pull/54))

## v1.1.4 (2017-02-09)
* @misteroneill Remove deprecation warning about using videojs.plugin (#72)
* @BrandonOCasey Update Travis build to run w/ Video.js 5 and 6 (#71)

## v1.1.3 (2017-01-27)
* @BrandonOCasey Updates for Video.js 6.0 compatibility. (#67)

## v1.1.2 (2016-12-07)
* @forbesjo Error if Flash tech is unusable (#50)

## v1.1.1 (2016-11-11)
* @mjneil Cleanup event bindings when reinitialized (#44)

## v1.1.0 (2016-09-08)
* @vdeshpande Add in a user-friendly message for disabled Flash in IE (#41)

## v1.0.5 (2016-08-10)
* @vdeshpande Close-button errors message accessible fix (#40)
* @mkody Fix typo in French translation (#39)

## v1.0.4 (2016-04-13)
* Added listening for `'adtimeupdate'` ([#36](https://github.com/brightcove/videojs-errors/pull/36))
* Added Arabic and Turkish ([#38](https://github.com/brightcove/videojs-errors/pull/38))

## v1.0.3 (2016-03-01)
* Add Italian, Russian and Chinese (traditional and simplified).
* Add English translations as a canonical template.

## v1.0.2 (2016-01-11)
* Bower :)

## v1.0.1 (2016-01-11)
* Updated to use `generator-videojs-plugin` conventions.

## v1.0.0 (2015-11-22)
* Updates for video.js 5.0.

## v0.1.8 (2015-05-05)
* Do not display errors when the player is paused or ended for timeouts.
* Fix a vdata exception when dispose is called.

## v0.1.6 (2014-09-10)
* Remove `dist/` from `.npmignore`.

## v0.1.5 (2014-09-03)
* More localization improvements.

## v0.1.4 (2014-08-27)
* Fix `dist/`.

## v0.1.3 (2014-08-27)
* Localization improvements.

## v0.1.2 (2014-08-19)
* Localization

## v0.1.1 (2014-06-13)
* Ended videos should not cause player timeouts on IE11/Win8rt.

## v0.1.0 (2014-06-05)
* Initial release.

