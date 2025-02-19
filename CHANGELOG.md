# [1.8.0](https://github.com/FJuette/ng2-smart-table/compare/v1.7.2...v1.8.0) (2021-04-12)



## [1.7.2](https://github.com/yggg/ng2-smart-table/compare/v1.7.1...v1.7.2) (2020-11-12)


### Bug Fixes

* use `selectedRowIndex` if specified when data changes ([#1221](https://github.com/yggg/ng2-smart-table/issues/1221)) ([3036b76](https://github.com/yggg/ng2-smart-table/commit/3036b76))



## [1.7.1](https://github.com/yggg/ng2-smart-table/compare/v1.7.0...v1.7.1) (2020-10-29)


### Features

* add hide column configuration property ([#1151](https://github.com/yggg/ng2-smart-table/issues/1151)) ([0d43219](https://github.com/yggg/ng2-smart-table/commit/0d43219))



# [1.7.0](https://github.com/yggg/ng2-smart-table/compare/v1.6.0...v1.7.0) (2020-10-08)


### Code Refactoring

* use original ng2-completer package ([#1211](https://github.com/yggg/ng2-smart-table/issues/1211)) ([59c3a78](https://github.com/yggg/ng2-smart-table/commit/59c3a78))


### Features

* add selectedRowIndex to settings and selectRow method ([#1210](https://github.com/yggg/ng2-smart-table/issues/1210)) ([0480215](https://github.com/yggg/ng2-smart-table/commit/0480215))
* upgrade to Angular 10 ([#1212](https://github.com/yggg/ng2-smart-table/issues/1212)) ([34b187f](https://github.com/yggg/ng2-smart-table/commit/34b187f))


### BREAKING CHANGES

`@akveo/ng2-completer` dependency replaced by `ng2-completer` as original package was fixed. Note on why we have to fork package could be found [here](#1140 (comment)). Please, uninstall `@akveo/ng2-completer` and install `ng2-completer`:
```
npm uninstall --save @akveo/ng2-completer
npm install --save ng2-completer
```



# [1.6.0](https://github.com/yggg/ng2-smart-table/compare/v1.5.0...v1.6.0) (2020-03-23)


### Features

* upgrade to Angular 9 ([#1140](https://github.com/yggg/ng2-smart-table/issues/1140)) ([8a4f0bb](https://github.com/yggg/ng2-smart-table/commit/8a4f0bb))


### BREAKING CHANGES

* `ng2-completer` dependency replaced by `@akveo/ng2-completer`. Read details in [#1140](https://github.com/yggg/ng2-smart-table/issues/1140). This is a temporary measure until the original ng2-completer fixed. We have no plans to support `@akveo/ng2-completer`.
* We no longer have a direct dependency on tslib. Instead it is now
listed a peerDependency. This matches Angular framework.



# [1.5.0](https://github.com/akveo/ng2-smart-table/compare/v1.4.0...v1.5.0) (2019-06-18)

Tables updated to Angular 8.

<a name="1.4.0"></a>
# [1.4.0](https://github.com/akveo/ng2-smart-table/compare/v1.3.5...v1.4.0) (2019-02-19)


### Bug Fixes

* deprecation warning with angular 7 ([#961](https://github.com/akveo/ng2-smart-table/issues/961)) ([c1558b1](https://github.com/akveo/ng2-smart-table/commit/c1558b1))
* **filter:** search on first input ([#883](https://github.com/akveo/ng2-smart-table/issues/883)) ([8d7283d](https://github.com/akveo/ng2-smart-table/commit/8d7283d))


### Features

* **filter:** add support for custom filters ([#825](https://github.com/akveo/ng2-smart-table/issues/825)) ([b4713d9](https://github.com/akveo/ng2-smart-table/commit/b4713d9)), closes [#632](https://github.com/akveo/ng2-smart-table/issues/632) [#569](https://github.com/akveo/ng2-smart-table/issues/569) [#447](https://github.com/akveo/ng2-smart-table/issues/447)



<a name="1.3.5"></a>
## [1.3.5](https://github.com/akveo/ng2-smart-table/compare/v1.3.4...v1.3.5) (2018-07-12)


### Bug Fixes

* **build:** compile to es5 ([d0c4608](https://github.com/akveo/ng2-smart-table/commit/d0c4608))



<a name="1.3.4"></a>
## [1.3.4](https://github.com/akveo/ng2-smart-table/compare/v1.3.3...v1.3.4) (2018-06-28)


### Bug Fixes

* **demo:** update polyfills for IE ([cf59d21](https://github.com/akveo/ng2-smart-table/commit/cf59d21))
* move ng2-completer to peerDependencies ([aa62510](https://github.com/akveo/ng2-smart-table/commit/aa62510))



<a name="1.3.3"></a>
## [1.3.3](https://github.com/akveo/ng2-smart-table/compare/v1.3.2...v1.3.3) (2018-06-13)


### Bug Fixes

* **build:** fix release scripts ([2a7bd0c](https://github.com/akveo/ng2-smart-table/commit/2a7bd0c))



<a name="1.3.2"></a>
## [1.3.2](https://github.com/akveo/ng2-smart-table/compare/v1.3.1...v1.3.2) (2018-06-12)


### Bug Fixes

* **build:** fix release metadata generation ([10111e2](https://github.com/akveo/ng2-smart-table/commit/10111e2))
* **filter:** fix ngModal deprecation warning ([e00c77f](https://github.com/akveo/ng2-smart-table/commit/e00c77f))



<a name="1.3.1"></a>
## [1.3.1](https://github.com/akveo/ng2-smart-table/compare/v1.3.0...v1.3.1) (2018-06-12)


### Bug Fixes

* fix gulp create metadata task ([#801](https://github.com/akveo/ng2-smart-table/issues/801)) ([96ad9d2](https://github.com/akveo/ng2-smart-table/commit/96ad9d2))



<a name="1.3.0"></a>
# [1.3.0](https://github.com/akveo/ng2-smart-table/compare/v1.2.2...v1.3.0) (2018-05-21)


### Features

* update to Angular 6 ([1d51de2](https://github.com/akveo/ng2-smart-table/commit/1d51de2))



<a name="1.2.1"></a>
# [1.2.1](https://github.com/akveo/ng2-smart-table/compare/v1.2.0...v1.2.1) (2017-05-25)


### Bug Fixes

* **table:** add the missed rxjs imports ([cc6a678](https://github.com/akveo/ng2-smart-table/commit/cc6a678))


### Features

* add rxjs rollup globals ([7ad6b98](https://github.com/akveo/ng2-smart-table/commit/7ad6b98))



<a name="1.2.0"></a>
# [1.2.0](https://github.com/akveo/ng2-smart-table/compare/v1.1.0...v1.2.0) (2017-05-25)


### Bug Fixes

* **readme:** fix broken license link ([f5496e0](https://github.com/akveo/ng2-smart-table/commit/f5496e0))
* **table:** custom action when action position: 'right' ([bc5f5b4](https://github.com/akveo/ng2-smart-table/commit/bc5f5b4))
* **table:** deprecated the search key ([#366](https://github.com/akveo/ng2-smart-table/issues/366)) ([e8cf1d9](https://github.com/akveo/ng2-smart-table/commit/e8cf1d9))
* **table:** fix a bug where source changes and pager doesn't get updated ([#329](https://github.com/akveo/ng2-smart-table/issues/329)) ([086cd1f](https://github.com/akveo/ng2-smart-table/commit/086cd1f))
* **table:** fix a bug where source changes and title sort configuration doesn't get updated ([#330](https://github.com/akveo/ng2-smart-table/issues/330)) ([89e4bec](https://github.com/akveo/ng2-smart-table/commit/89e4bec))
* **table:** fix a bug where source changes but filter doesn't get updated ([#331](https://github.com/akveo/ng2-smart-table/issues/331)) ([c48818f](https://github.com/akveo/ng2-smart-table/commit/c48818f))
* **table:** fix an issue where pager is vertical (fix [#343](https://github.com/akveo/ng2-smart-table/issues/343)) ([04c896e](https://github.com/akveo/ng2-smart-table/commit/04c896e))
* **table:** fix bug when source changes and it's type is Array ([#327](https://github.com/akveo/ng2-smart-table/issues/327)) ([b72c29f](https://github.com/akveo/ng2-smart-table/commit/b72c29f))
* **table:** hide actions when no actions ([27abbb5](https://github.com/akveo/ng2-smart-table/commit/27abbb5))
* **table:** make `source` input property properly annotated as DataSource in dependent components ([#332](https://github.com/akveo/ng2-smart-table/issues/332)) ([9be34fc](https://github.com/akveo/ng2-smart-table/commit/9be34fc))
* **table:** onComponentInit hook didn't called when OnInit didn't implemented ([067a346](https://github.com/akveo/ng2-smart-table/commit/067a346))
* **table:** only perform filter if search string is present ([#358](https://github.com/akveo/ng2-smart-table/issues/358)) ([3886007](https://github.com/akveo/ng2-smart-table/commit/3886007))
* **table:** performance improve ([#367](https://github.com/akveo/ng2-smart-table/issues/367)), (fix [#189](https://github.com/akveo/ng2-smart-table/issues/189), fix [#300](https://github.com/akveo/ng2-smart-table/issues/300)) ([69e883c](https://github.com/akveo/ng2-smart-table/commit/69e883c))
* **table:** remove unused dependecies for filter-types ([#334](https://github.com/akveo/ng2-smart-table/issues/334)) ([fd98bfc](https://github.com/akveo/ng2-smart-table/commit/fd98bfc))


### Features

* **custom-actions:** add the custom actions feature ([#338](https://github.com/akveo/ng2-smart-table/issues/338)) ([af8e00e](https://github.com/akveo/ng2-smart-table/commit/af8e00e))
* **docs:** add onComponentInitFunction description in docs ([2bb9bd8](https://github.com/akveo/ng2-smart-table/commit/2bb9bd8))
* **table:** add custom render component on init function hook ([e06fa09](https://github.com/akveo/ng2-smart-table/commit/e06fa09))
* **table:** add rowClassFunction ([#355](https://github.com/akveo/ng2-smart-table/issues/355)) ([845c8cf](https://github.com/akveo/ng2-smart-table/commit/845c8cf))



<a name="1.1.0"></a>
# 1.1.0 (2017-04-21)

### Bug fixes

* **docs:** update docs ([80b3b22](https://github.com/akveo/ng2-smart-table/commit/80b3b224868a0d716eeceb8239042a1f83ac3bb9)), ([#308](https://github.com/akveo/ng2-smart-table/pull/308))
* **docs:** update docs ([9920b3c](https://github.com/akveo/ng2-smart-table/commit/9920b3c14b09364c7c4e97344c89856557b3b8c1)), ([#309](https://github.com/akveo/ng2-smart-table/pull/309))
* **table:** performing an edit might result in an error when the data source is being updated by an Observable ([4221b4c](https://github.com/akveo/ng2-smart-table/commit/4221b4cfb13e965f41f62603ced85b9e0d5237d4)), ([#280](https://github.com/akveo/ng2-smart-table/pull/280)), closes ([#279](https://github.com/akveo/ng2-smart-table/issues/279))
* **docs:** fix the links ([68205eb](https://github.com/akveo/ng2-smart-table/commit/68205eb17d2d893995808a74fe1bd8d7b6cb1d37))
* **table:** change style deployment as external file for better flexibility ([4504fcf](https://github.com/akveo/ng2-smart-table/commit/4504fcf2a952505f5cfdf800dadf73b3369144e6)), closes ([#112](https://github.com/akveo/ng2-smart-table/issues/112)), ([#290](https://github.com/akveo/ng2-smart-table/issues/290))

### Features

* **table:** allow for default value to be set for new cells ([9065c52](https://github.com/akveo/ng2-smart-table/commit/9065c5249c8c9b6aca72a10429f78caa487f3e23)), ([#311](https://github.com/akveo/ng2-smart-table/pull/311))
* **table:** add column width property ([77be67e](https://github.com/akveo/ng2-smart-table/commit/77be67ee915b1ac4fbd781c145cdd3f0d67a5214)), ([#313](https://github.com/akveo/ng2-smart-table/pull/313)), closes ([#134](https://github.com/akveo/ng2-smart-table/issues/134)), ([#201](https://github.com/akveo/ng2-smart-table/issues/201))
* **table:** add an 'addable' option ([abc8a84](https://github.com/akveo/ng2-smart-table/commit/abc8a8420bc1db1fd31ebbb5cbf62f04139cfd49)), ([#307](https://github.com/akveo/ng2-smart-table/pull/307))

<a name="1.0.4"></a>
# 1.0.4 (2017-04-13)

### Bug fixes

* **build:** added mising rxjs imports ([24c3098](https://github.com/akveo/ng2-smart-table/commit/24c309807e758ce62011d8bf5b16b3e3793d8b22)), closes ([#304](https://github.com/akveo/ng2-smart-table/issues/304))

<a name="1.0.3"></a>
# 1.0.3 (2017-04-05)

### Bug fixes

* **build:** added mising rxjs imports ([86de89f](https://github.com/akveo/ng2-smart-table/commit/86de89fffccffa8002d16ad17754c1a07574adc5)), ([#283](https://github.com/akveo/ng2-smart-table/pull/283)), closes ([#229](https://github.com/akveo/ng2-smart-table/issues/229))


<a name="1.0.2"></a>
# 1.0.2 (2017-04-04)

### Bug fixes

* **build:** move ng2-completer and lodash from peerDependencies to dependencies

<a name="1.0.1"></a>
# 1.0.1 (2017-03-29)

### Bug fixes

* **build:** fix package.json

<a name="1.0.0"></a>
# 1.0.0 (2017-03-29)

### Features

* **demo:** @angular/cli integration
* **demo:** setup demo deploying to the github pages
* **demo:** setup e2e and unit testing
* **table:** update to angular 4.0.0
* **table:** integrate gulp for npm package bundling
* **table:** add a row hover event ([68b73ee](https://github.com/akveo/ng2-smart-table/commit/68b73eef0b4607cef522f201c3e67a230a5ee03e)), ([1ceca0d](https://github.com/akveo/ng2-smart-table/commit/1ceca0d6afa3be3ba5f2ef53447d9a75f360150a)), ([#253](https://github.com/akveo/ng2-smart-table/pull/253)), ([#262](https://github.com/akveo/ng2-smart-table/pull/262))
* **table:** add a deselect row ([2ab02b4](https://github.com/akveo/ng2-smart-table/commit/2ab02b4949c577da34153f7ad1870e7acaa399e6)), ([#94](https://github.com/akveo/ng2-smart-table/pull/94))
* **table:** add a getFilteredAndSorted function ([df3f343](https://github.com/akveo/ng2-smart-table/commit/df3f343caaff9aff1ecc6d8b94767e3466524068)), ([#249](https://github.com/akveo/ng2-smart-table/pull/249))

### Bug fixes

* **table:** ng2-completer failed with empty value ([b0e1797](https://github.com/akveo/ng2-smart-table/commit/b0e1797e9d22ca4a076e01120525f16628e3e6a6)), closes ([#164](https://github.com/akveo/ng2-smart-table/issues/164))
* **table:** add a check for existing filters ([8daa70f](https://github.com/akveo/ng2-smart-table/commit/8daa70f8434cfb4036cec07dc68208a3c3c51d00)), ([#40](https://github.com/akveo/ng2-smart-table/pull/40))
* **table:** fix the actions column positioning ([ebfbd54](https://github.com/akveo/ng2-smart-table/commit/ebfbd5424a227217484494fc48a5f2fb854a470d)), ([#245](https://github.com/akveo/ng2-smart-table/pull/245))

### Code Refactoring

* **table:** move the components to the modules
* **demo:** move some examples to new /examples route ([#213](https://github.com/akveo/ng2-smart-table/pull/213))

### Breaking Changes

* **table:** remove div container with the css styles from ng2-smart-table component
* **table:** remove the css classes from table container

<a name="0.6.0-0"></a>
# 0.6.0-0 (2017-03-02)

### Features

* **table:** configuring column filters ([#185](https://github.com/akveo/ng2-smart-table/pull/185))
* **table:** custom cell view component ([#193](https://github.com/akveo/ng2-smart-table/pull/193))
* **table:** update to angular 2.4.9

### Bug Fixes

* **demo:** fix url redirect to gh-pages ([8a54dea141](https://github.com/akveo/ng2-smart-table/commit/8a54dea141041d8db19f42430db46d2a2c2dcae8))

### Code Refactoring

* **table:** grouping components by section ([#172](https://github.com/akveo/ng2-smart-table/pull/172))

<a name="0.3.1"></a>
# 0.3.1 (2016-09-19)

### Features

* **table:** update to angular 2.0

### How to update

* Install 0.2.1 version
* Checkout README.md installation section for more details

<a name="0.2.1"></a>
# 0.2.1 (2016-08-29)

### Features

* **table:** update to angular rc.5

### How to update

* Install 0.2.1 version
* Checkout README.md installation section for more details on configuration for rc.5
