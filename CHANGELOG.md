# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [3.2.3](https://github.com/lingui/js-lingui/compare/v3.2.2...v3.2.3) (2020-11-22)


### Bug Fixes

* export TransRenderProps from @lingui/react ([#877](https://github.com/lingui/js-lingui/issues/877)) ([3db9d6b](https://github.com/lingui/js-lingui/commit/3db9d6b0bfe9edae99523cd706de6826f67184ad))
* omit i18n prop in withI18n typescript interface ([#879](https://github.com/lingui/js-lingui/issues/879)) ([5927d42](https://github.com/lingui/js-lingui/commit/5927d42b256d1adfb26ed03367e521bfc8f1e2e6))





## [3.2.2](https://github.com/lingui/js-lingui/compare/v3.2.1...v3.2.2) (2020-11-20)


### Bug Fixes

* fallbackLocales overriden if parent found ([a53e12f](https://github.com/lingui/js-lingui/commit/a53e12f19cebeb6412debc9dace0b4a45aa17624))
* locale not present in catalogs warn ([6f598e8](https://github.com/lingui/js-lingui/commit/6f598e81bb3278722b995d69daad3f5cdc492284))
* parse template strings in t and defineMessage macros ([#862](https://github.com/lingui/js-lingui/issues/862)) ([024a7e6](https://github.com/lingui/js-lingui/commit/024a7e61e8d76efc2b4a8dd3bb4e0a3932945496))





# [3.2.0](https://github.com/lingui/js-lingui/compare/v3.1.0...v3.2.0) (2020-11-12)


### Bug Fixes

* absolute rootDir on Windows ([#853](https://github.com/lingui/js-lingui/issues/853)) ([f4eabf9](https://github.com/lingui/js-lingui/commit/f4eabf9fdfa04d23009dda00717344e161f1f8f7))
* MessageDescriptor values type ([#848](https://github.com/lingui/js-lingui/issues/848)) ([9712d94](https://github.com/lingui/js-lingui/commit/9712d94d043c8d40cbc5d017474b5938eb02f8d6))
* t macro as function not extracting ([#846](https://github.com/lingui/js-lingui/issues/846)) ([d819bfc](https://github.com/lingui/js-lingui/commit/d819bfc74707a8766bfe1b1a3d43edce97f8f265))


### Features

* extract multiple comments per translation ID ([#854](https://github.com/lingui/js-lingui/issues/854)) ([c849c9c](https://github.com/lingui/js-lingui/commit/c849c9c024832aa7b07e5f837791e287c3aebe29))





# [3.1.0](https://github.com/lingui/js-lingui/compare/v3.0.3...v3.1.0) (2020-11-10)


### Bug Fixes

* accept catalog paths without ending slash ([#812](https://github.com/lingui/js-lingui/issues/812)) ([5d39586](https://github.com/lingui/js-lingui/commit/5d3958638913d5f6b6d318bf21ce4f3019a69e88))
* add type for t macro as function ([#821](https://github.com/lingui/js-lingui/issues/821)) ([7f09c2d](https://github.com/lingui/js-lingui/commit/7f09c2d4ddd88d885a5df23e1b0c267f937abaaf))
* cache ([c57be58](https://github.com/lingui/js-lingui/commit/c57be58f8e8eb17240241f444f79d699d73540bd))
* ensure render of I18nProvider in async scenarios ([#839](https://github.com/lingui/js-lingui/issues/839)) ([cd2816a](https://github.com/lingui/js-lingui/commit/cd2816a3d847042029c9b29dfb420f2ff5ae02cc))
* fix exit code on compile --strict errors ([#825](https://github.com/lingui/js-lingui/issues/825)) ([69a80e2](https://github.com/lingui/js-lingui/commit/69a80e2b0b5061c657e63835355207be199db692))
* improved performance of formatters ([#818](https://github.com/lingui/js-lingui/issues/818)) ([22667ad](https://github.com/lingui/js-lingui/commit/22667adba5b07cc94abacff8e8b5f5b19202576c))
* mandatory ext on @lingui/loader ([#831](https://github.com/lingui/js-lingui/issues/831)) ([8979aaf](https://github.com/lingui/js-lingui/commit/8979aaf81e5f839a8406d3ac7516205113944c39))
* show error when plurals aren't loaded ([#824](https://github.com/lingui/js-lingui/issues/824)) ([296b6a1](https://github.com/lingui/js-lingui/commit/296b6a1a1f332064f040cc987c4359411d307258))


### Features

* accept t as function ([c0c08ba](https://github.com/lingui/js-lingui/commit/c0c08bab0f16d526d1f69734d6d0e5e1a89edd68))
* add cli option to extract only a specific locale ([#816](https://github.com/lingui/js-lingui/issues/816)) ([49f45b2](https://github.com/lingui/js-lingui/commit/49f45b24a58f79e1f6de9c279b0c033d593d7854))
* enable pseudolocalization from pseudolocale folder ([#836](https://github.com/lingui/js-lingui/issues/836)) ([f1e0078](https://github.com/lingui/js-lingui/commit/f1e0078b9892cd7a95a6ad8105f1a3b41bc3b88b))
* lookup lingui command suggestions in package.json ([#823](https://github.com/lingui/js-lingui/issues/823)) ([d58dc09](https://github.com/lingui/js-lingui/commit/d58dc09554cb7054a3463b9f1b53297338322d66))
* use fallback locales from cldr ([#820](https://github.com/lingui/js-lingui/issues/820)) ([2d9e124](https://github.com/lingui/js-lingui/commit/2d9e124b91f1ba7a65e9f997a3ba952679c6c23a))


### Reverts

* Revert "chore: improved commit-lint" ([75fcf65](https://github.com/lingui/js-lingui/commit/75fcf65d509ef0e628332fabdc17864beacdadc3))





# Change Log

<a name="3.0.3"></a>
## [3.0.3](https://github.com/lingui/js-lingui/compare/v3.0.2..v3.0.3) (2020-11-01)

### Bug Fixes

* Handle multiple paths in catalogs.include ([#803](https://github.com/lingui/js-lingui/pull/803)).

<a name="3.0.2"></a>
## [3.0.2](https://github.com/lingui/js-lingui/compare/v3.0.1..v3.0.2) (2020-11-01)

### Bug Fixes

* Minor fixes in @lingui/macro and @lingui/react types

<a name="3.0.1"></a>
## [3.0.1](https://github.com/lingui/js-lingui/compare/v3.0.0..v3.0.1) (2020-11-01)

### Bug Fixes

* Fix catalog include paths on Windows ([#802](https://github.com/lingui/js-lingui/pull/802)).
* Fix type of Trans component ([#801](https://github.com/lingui/js-lingui/pull/801)).
* Accept React 17 as a peer dependency ([#789](https://github.com/lingui/js-lingui/pull/789)).
* Allow null overrides for render and component props ([#799](https://github.com/lingui/js-lingui/pull/799)).
  Thanks to [Declan Haigh](https://github.com/dhaigh)

<a name="3.0.0"></a>
## [3.0.0](https://github.com/lingui/js-lingui/compare/v2.9.1..v3.0.0) (2020-11-01)

See [migration guide](https://lingui.js.org/releases/migration-3.html) for a full changelog.

<a name="2.9.1"></a>
## [2.9.1](https://github.com/lingui/js-lingui/compare/v2.9.0..v2.9.1) (2020-01-18)

### Bug Fixes

* Fix import of typescript package ([#611](https://github.com/lingui/js-lingui/pull/611)).
  Thanks to [Anton Korzunov](https://github.com/theKashey)
* Fix flow types of withI18n ([#605](https://github.com/lingui/js-lingui/pull/605)).
  Thanks to [Kamil Tunkiewicz](https://github.com/ktunkiewicz)

<a name="2.9.0"></a>
## [2.9.0](https://github.com/lingui/js-lingui/compare/v2.8.3...v2.9.0) (2019-12-02)

### New Features

* Add optional sort by origin/filename ([#563](https://github.com/lingui/js-lingui/issues/563)).
  Thanks to [Kenneth Skovhus](https://github.com/skovhus)
* Lazily split messages by value tags ([#593](https://github.com/lingui/js-lingui/issues/593)).
  Thanks to [Danny Sellers](https://github.com/dannysellers)
* Optional line numbers for lingui format ([#587](https://github.com/lingui/js-lingui/issues/587)).
  Thanks to [Martti Roitto](https://github.com/MarttiR)
* Moved typescript dependency to peer ([#589](https://github.com/lingui/js-lingui/issues/589)).
  Thanks to [Daniel K.](https://github.com/FredyC)

### Bug Fixes

* Compile strict skips pseudo locale ([#584](https://github.com/lingui/js-lingui/issues/584)).
  Thanks to [Daniel Chabr](https://github.com/danielchabr)

<a name="2.8.3"></a>
## [2.8.3](https://github.com/lingui/js-lingui/compare/v2.8.2...v2.8.3) (2019-05-22)

### Bug Fixes

* Loader: Fix type error when no loader config is provided
* Macro: `babel-plugin-macros` are peer dependency and must be installed manually

<a name="2.8.2"></a>
## [2.8.2](https://github.com/lingui/js-lingui/compare/v2.8.0...v2.8.2) (2019-05-22)

### Bug Fixes

* CLI: Don't warn about conflicting default message if it's empty ([#502](https://github.com/lingui/js-lingui/pull/502/)).
  Thanks to [Filip Žmuk](https://github.com/filipcro).
* Conf: Pass config path to getConfig explicitly instead reading it from process.argv ([#509](https://github.com/lingui/js-lingui/pull/509/)).
  Thanks to [Brandon Croft](https://github.com/brandonc).

<a name="2.8.0"></a>
## [2.8.0](https://github.com/lingui/js-lingui/compare/v2.7.4...v2.8.0) (2019-05-17)

### New Features

* Conf: Allow loading specific configuration file using --config argument ([#501](https://github.com/lingui/js-lingui/pull/501/)).
  Thanks to [Brandon Croft](https://github.com/brandonc).

### Bug Fixes
* Macro: Fix escaped backticks in template string ([#477](https://github.com/lingui/js-lingui/pull/477/)).
  Thanks to [Saxon Landers](https://github.com/ackwell).

<a name="2.7.4"></a>
## [2.7.4](https://github.com/lingui/js-lingui/compare/v2.7.3...v2.7.4) (2019-02-19)

### Bug Fixes

* Conf: Allow `extends` and `rootMode` babel config options ([#454](https://github.com/lingui/js-lingui/pull/454/)).
  Thanks to [Adam Thomas](https://github.com/adamscybot).
* React: Fix flow typing with Flow 0.92 ([#448](https://github.com/lingui/js-lingui/pull/448/)).
  Thanks to [Florian Rival](https://github.com/4ian).

<a name="2.7.3"></a>
## [2.7.3](https://github.com/lingui/js-lingui/compare/v2.7.2...v2.7.3) (2019-01-28)

- Export `@lingui/core/dev` subpackage.

### Bug Fixes

* CLI: Log original info with Babel compatibility info ([#401](https://github.com/lingui/js-lingui/issues/401)).
  Thanks to [Sam Gluck](https://github.com/sdgluck).
* CLI: Allow pseudolocales which don't start with a known language ([#411](https://github.com/lingui/js-lingui/issues/411)).
  Thanks to [Eric Plumb](https://github.com/professorplumb).
* CLI: Made pseudolocales to take into account variable names ([#419](https://github.com/lingui/js-lingui/issues/419)).
  Thanks to [Cornel Stefanache](https://github.com/cstefanache).
* CLI: Fix edge case bug in plural pseudolocalization ([#428](https://github.com/lingui/js-lingui/issues/428)).
  Thanks to [Eric Plumb](https://github.com/professorplumb).
* CLI: Fix yarn detection with nps ([#441](https://github.com/lingui/js-lingui/issues/441)).
  Thanks to [MU AOHUA](https://github.com/AOHUA).
  

<a name="2.7.2"></a>
## [2.7.2](https://github.com/lingui/js-lingui/compare/v2.7.1...v2.7.2) (2018-11-14)

### Bug Fixes

* CLI: show more accurate follow-up commands (e.g. show `use (yarn compile) ...` instead of `use (lingui compile) ...` when CLI is invoked using `yarn extract`)
* CLI: add missing export (regression introduced by [#381](https://github.com/lingui/js-lingui/pull/381))

<a name="2.7.1"></a>
## [2.7.1](https://github.com/lingui/js-lingui/compare/v2.7.0...v2.7.1) (2018-11-12)

### Bug Fixes

* CLI: remove "macros" from the list of babel plugins ([#360](https://github.com/lingui/js-lingui/pull/360)).
  Thanks to [Jérôme Steunou](https://github.com/JSteunou).
* Macro: fix ICU message for nested selects ([#365](https://github.com/lingui/js-lingui/pull/365)).
  Thanks to [Maxim Zemskov](https://github.com/Nodge).
* CLI: allow leading space in i18n description comments ([#366](https://github.com/lingui/js-lingui/pull/366)).
  Thanks to [Maxim Zemskov](https://github.com/Nodge).
* Disable Google Clojure Compiler rewritePolyfills behavior ([#374](https://github.com/lingui/js-lingui/pull/374)).
  Thanks to [Ivan Khilko](https://github.com/ikhilko).
* Show hint for missing babel-core package ([#381](https://github.com/lingui/js-lingui/pull/381)).
* Fix message extracting when Trans component is missing ([#389](https://github.com/lingui/js-lingui/pull/389)).

<a name="2.7.0"></a>
## [2.7.0](https://github.com/lingui/js-lingui/compare/v2.6.1...v2.7.0) (2018-09-10)

🔥 Babel Macros 🎣 are finally released! After few weeks of fiddling with API, i18n macros
are finally out without a breaking release. This is the first part of 
[RFC-001](https://lingui.js.org/rfc/001_macros_message_descriptors.html), final form
be delivered in next release.

**Important:** Macros are completely optional and Babel plugins will work until v3.
It's not mandatory to migrate to macro, but recommended.

### New Features

* New package [`@lingui/macro`](https://www.npmjs.com/package/@lingui/macro) published ([#318](https://github.com/lingui/js-lingui/issues/318)).
  Big thanks to [Matt Labrum](https://github.com/mlabrum) for initial implementation.
* [Pseudolocalization](https://lingui.js.org/tutorials/cli.html#pseudolocalization)
  ([#309](https://github.com/lingui/js-lingui/issues/309)).
  Thanks to [Martin Cerny](https://github.com/MartinCerny-awin).
* Extract description of messages ([#197](https://github.com/lingui/js-lingui/issues/197)).
* Add `i18n.date` and `i18n.number` methods ([#299](https://github.com/lingui/js-lingui/issues/299)).

### Bug Fixes

* CLI: how help for unrecognized commands ([#308](https://github.com/lingui/js-lingui/issues/308)).
  Thanks to [An Nguyen](https://github.com/dephiros).
* Fix Flow types ([#306](https://github.com/lingui/js-lingui/issues/306)).


<a name="2.6.1"></a>
## [2.6.1](https://github.com/lingui/js-lingui/compare/v2.6.0...v2.6.1) (2018-09-03)

### Bug Fixes

* `@lingui/cli` - Remove opencollective dependency

<a name="2.6.0"></a>
## [2.6.0](https://github.com/lingui/js-lingui/compare/v2.5.0...v2.6.0) (2018-08-31)

### New Features

* Configuration - add [`extractBabelOptions`](https://lingui.js.org/ref/conf.html#extractbabeloptions)
  ([#287](https://github.com/lingui/js-lingui/issues/287)). Thanks to [Daniel K.](https://github.com/FredyC).
* `lingui extract` - add [`--namespace`](https://lingui.js.org/ref/cli.html#cmdoption-compile-namespace)
   option and [`compileNamespace`](https://lingui.js.org/ref/conf.html#compilenamespace)
   config ([#295](https://github.com/lingui/js-lingui/issues/295)). Thanks to [An Nguyen](https://github.com/dephiros).

### Bug Fixes

* Update peer-dependency on babel-core ([#286](https://github.com/lingui/js-lingui/issues/286)).
* Output multiple origins on separate line in PO format ([#290](https://github.com/lingui/js-lingui/issues/290)).
* Keep headers in PO format ([#294](https://github.com/lingui/js-lingui/issues/294)).
  Thanks to [Daniel K.](https://github.com/FredyC).
* `lingui extract` - set default BABEL_ENV (required by `react-app` preset) ([#300](https://github.com/lingui/js-lingui/issues/300)).
* Fix `@lingui/loader` compatibility with Webpack 4 ([#297](https://github.com/lingui/js-lingui/issues/297)).
* Fix [`I18n`](https://lingui.js.org/ref/react.html#i18n) render prop component to not
  unmount children component between renders ([#302](https://github.com/lingui/js-lingui/issues/302)).

<a name="2.5.0"></a>
## [2.5.0](https://github.com/lingui/js-lingui/compare/v2.4.2...v2.5.0) (2018-08-24)

### New Features

* Disable eslint for compiled catalogs ([#279](https://github.com/lingui/js-lingui/issues/279)). Thanks to [Benoît Grélard](https://github.com/artisologic).
* Add [`I18n`](https://lingui.js.org/ref/react.html#i18n) render prop component ([#282](https://github.com/lingui/js-lingui/issues/282))

### Bug Fixes

* Handle message compile errors in development ([#283](https://github.com/lingui/js-lingui/issues/283))

<a name="2.4.2"></a>
## [2.4.2](https://github.com/lingui/js-lingui/compare/v2.4.1...v2.4.2) (2018-08-19)

### Bug Fixes

* `lingui init` - add missing command ([#270](https://github.com/lingui/js-lingui/issues/270))

<a name="2.4.1"></a>
## [2.4.1](https://github.com/lingui/js-lingui/compare/v2.4.0...v2.4.1) (2018-08-10)

### Bug Fixes

* `lingui extract` - fix path separator on Windows ([#262](https://github.com/lingui/js-lingui/issues/262))
* `lingui extract` - fix extracting from typescript files ([#260](https://github.com/lingui/js-lingui/issues/260))

<a name="2.4.0"></a>
## [2.4.0](https://github.com/lingui/js-lingui/compare/v2.3.0...v2.4.0) (2018-08-09)

Better support for custom file formats and initial support for Create React App.

### New Features

* New message catalog format: [Gettext PO file](https://lingui.github.io/js-lingui/ref/conf.html#po)
  ([#256](https://github.com/lingui/js-lingui/issues/256))
* New [`lingui init`](https://lingui.github.io/js-lingui/ref/cli.html#init) command
  which detects project type and install all required packages ([#253](https://github.com/lingui/js-lingui/pull/253))
* Allow customize messages for missing translations ([#255](https://github.com/lingui/js-lingui/issues/255))
* `lingui extract` detects `create-react-app` projects and extracts messages using
  `rect-app` babel preset

### Bug Fixes

* `lingui add-locale` accepts any valid BCP-47 locale ([#182](https://github.com/lingui/js-lingui/issues/182))
* Flow types are correctly exported for all packages ([#250](https://github.com/lingui/js-lingui/issues/250))

<a name="2.3.0"></a>
## [2.3.0](https://github.com/lingui/js-lingui/compare/v2.2.0...v2.3.0) (2018-07-23)

Long-awaited backlog grooming.

### New Features

* Add support for locales (aka cultures) ([#170](https://github.com/lingui/js-lingui/pull/170)). Thanks to [Cristi Ingineru](https://github.com/cristiingineru).
* Allow React elements to be used as message variables ([#183](https://github.com/lingui/js-lingui/issues/183))
* Support both Babel 6.x and 7.x ([#171](https://github.com/lingui/js-lingui/issues/171), [#232](https://github.com/lingui/js-lingui/issues/232), [#238](https://github.com/lingui/js-lingui/issues/238))
* `withI18n` hoists statics of wrapped component ([#166](https://github.com/lingui/js-lingui/issues/166))
* `Date` and `i18n.date` accepts date as a string ([#155](https://github.com/lingui/js-lingui/issues/155))
* `lingui extract` shows progress ([#180](https://github.com/lingui/js-lingui/issues/180))
* `lingui extract` throws an error when encountering different defaults for the same message ([#200](https://github.com/lingui/js-lingui/issues/200))
* `lingui compile` shows useful error when message has syntax errors ([#191](https://github.com/lingui/js-lingui/issues/191))

### Bug Fixes

* Fix internal catalog names to avoid collisions. Internal catalogs are named `<original_filename>.json`, eg: `App.js.json` ([#244](https://github.com/lingui/js-lingui/issues/244))

### Docs

* [React Native Tutorial](https://lingui.github.io/js-lingui/tutorials/react-native.html) ([#243](https://github.com/lingui/js-lingui/pull/243)). Thanks to [Vojtech Novak](https://github.com/vonovak).
* Add draft of [Testing Guide](https://lingui.github.io/js-lingui/guides/testing.html)
* Add section with [external resources](https://lingui.github.io/js-lingui/misc/talks-about-i18n.html)
* Several fixes by [Vincent Ricard](https://github.com/ghostd) ([#242](https://github.com/lingui/js-lingui/pull/242))

<a name="2.2.0"></a>
## [2.2.0](https://github.com/lingui/js-lingui/compare/v2.1.2...v2.2.0) (2018-07-04)

Release dedicated to **command line interface**. 

### New Features

* Load jsLingui configuration from separate file ([#209](https://github.com/lingui/js-lingui/pull/209)). Thanks to [Vincent Ricard](https://github.com/ghostd).
* Add [--overwrite](https://lingui.github.io/js-lingui/ref/lingui-cli.html#cmdoption-extract-overwrite)
  option which forces overwrite of translations in minimal `format` for `sourceLocale` from source code. ([#199](https://github.com/lingui/js-lingui/issues/199))
* Order messages in catalogs alphabetically by message ID ([#230](https://github.com/lingui/js-lingui/issues/230)). Thanks to [David Reeß](https://github.com/queicherius).
* Add TypeScript extractor ([#228](https://github.com/lingui/js-lingui/pull/228)). Thanks to [Jeow Li Huan](https://github.com/huan086).
* Pass extra Babel options to extractor ([#226](https://github.com/lingui/js-lingui/pull/226)). Thanks to [Jan Willem Henckel](https://github.com/djfarly).

### Bug Fixes

* Mark all messages in file as obsolete when file is completely removed ([#235](https://github.com/lingui/js-lingui/pull/235))
* Support locales with hyphens in cli compile ([#231](https://github.com/lingui/js-lingui/issues/231)). Thanks to [Leonardo Dino](https://github.com/leonardodino).
* Extract with format minimal does not set defaults ([#222](https://github.com/lingui/js-lingui/issues/222))
* Use generated message as a default one in sourceLocale catalog ([#212](https://github.com/lingui/js-lingui/issues/212))
