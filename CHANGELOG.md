# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="1.4.0"></a>
# [1.4.0](https://github.com/smooth-code/loadable-components/compare/v1.3.0...v1.4.0) (2018-04-18)


### Bug Fixes

* set correct loading state if component is already loaded. (#64) ([9b0cae2](https://github.com/smooth-code/loadable-components/commit/9b0cae2))


### Features

* support React.createContext API (#65) ([289ad67](https://github.com/smooth-code/loadable-components/commit/289ad67))



<a name="1.3.0"></a>
# [1.3.0](https://github.com/smooth-code/loadable-components/compare/v1.2.0...v1.3.0) (2018-04-06)


### Bug Fixes

* circular structure in error object (#60) ([96333ca](https://github.com/smooth-code/loadable-components/commit/96333ca))
* React 16.3 compatibility ([abd7963](https://github.com/smooth-code/loadable-components/commit/abd7963)), closes [#57](https://github.com/smooth-code/loadable-components/issues/57)


### Features

* attach static properties on load ([d383fab](https://github.com/smooth-code/loadable-components/commit/d383fab)), closes [#58](https://github.com/smooth-code/loadable-components/issues/58)



<a name="1.2.0"></a>
# [1.2.0](https://github.com/smooth-code/loadable-components/compare/v1.1.1...v1.2.0) (2018-03-25)


### Features

* add Hot Reload support ([c79085e](https://github.com/smooth-code/loadable-components/commit/c79085e))



<a name="1.1.1"></a>
## [1.1.1](https://github.com/smooth-code/loadable-components/compare/v1.1.0...v1.1.1) (2018-02-06)


### Bug Fixes

* **snapshot:** fix snap usage ([3445bea](https://github.com/smooth-code/loadable-components/commit/3445bea)), closes [#40](https://github.com/smooth-code/loadable-components/issues/40)



<a name="1.1.0"></a>
# [1.1.0](https://github.com/smooth-code/loadable-components/compare/v1.0.2...v1.1.0) (2018-02-04)


### Features

* ship a single js file ([99e08c0](https://github.com/smooth-code/loadable-components/commit/99e08c0))



<a name="1.0.2"></a>
## [1.0.2](https://github.com/smooth-code/loadable-components/compare/v1.0.1...v1.0.2) (2018-02-04)


### Bug Fixes

* state could have no children ([a47c410](https://github.com/smooth-code/loadable-components/commit/a47c410)), closes [#36](https://github.com/smooth-code/loadable-components/issues/36)



<a name="1.0.1"></a>
## [1.0.1](https://github.com/smooth-code/loadable-components/compare/v1.0.0...v1.0.1) (2018-02-03)


### Bug Fixes

* fix loadComponents without valid state ([35f81a6](https://github.com/smooth-code/loadable-components/commit/35f81a6)), closes [#34](https://github.com/smooth-code/loadable-components/issues/34)



<a name="1.0.0"></a>
# [1.0.0](https://github.com/smooth-code/loadable-components/compare/v0.4.0...v1.0.0) (2018-02-02)


### Features

* stable version 1 ([601bd34](https://github.com/smooth-code/loadable-components/commit/601bd34))


### BREAKING CHANGES

* loadable-components/babel is now required if you do server side rendering.
* ErrorComponent now receive `ownProps` instead of `props`.
