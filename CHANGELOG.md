## [11.1.1](https://github.com/geostyler/geostyler/compare/v11.1.0...v11.1.1) (2023-01-16)


### Bugfixes

* apply suggestions from code review ([b8486e8](https://github.com/geostyler/geostyler/commit/b8486e818f3e28905909c30cfbd2a3e6844af275))
* make RuleGeneratorUtil less prone to errors ([d55fd15](https://github.com/geostyler/geostyler/commit/d55fd157f6ba5d4412bac16e17affeb9bb4abac6))

## [11.1.0](https://github.com/geostyler/geostyler/compare/v11.0.0...v11.1.0) (2023-01-11)


### Features

* add offset fields to IconEditor ([ab6af25](https://github.com/geostyler/geostyler/commit/ab6af25b44f0e50d2d4c410ebfe08fe04aee298b))
* add offset fields to WellKnownNameEditor ([590d1e0](https://github.com/geostyler/geostyler/commit/590d1e09f0d1286e072c71a60b9c59a04c51bf99))
* add perpendicular offset field to LineEditor ([adadc54](https://github.com/geostyler/geostyler/commit/adadc541c65a2e151d91aa9e9933fa2f6673c4f5))
* expand FilterTree by default ([0e88d75](https://github.com/geostyler/geostyler/commit/0e88d75df8151196cd0e452fbc8df277c23b6f44))


### Bugfixes

* adapt path and defaultValue for editors ([cb74226](https://github.com/geostyler/geostyler/commit/cb74226d95310f44f55918e06a6a9491523a6280))
* remove internal state handling for CardStyle ([58635a1](https://github.com/geostyler/geostyler/commit/58635a148dc235b0b6da5af6c4b7042856a43b17))

## [11.0.0](https://github.com/geostyler/geostyler/compare/v10.3.1...v11.0.0) (2022-12-13)


### ⚠ BREAKING CHANGES

* This forces a major release for a previously wrongly
formatted commit message (commit sha 30e19de16a6310dcd79bf4e4292b33bf80004c0d)
that lead to the unintended release of version 10.3.1, which includes a
breaking change. The code of this release will be identical with the code of
version 10.3.1.

### Breaking changes

* force major release ([ecfb2a0](https://github.com/geostyler/geostyler/commit/ecfb2a0cdb61f3cf5767a12ab73c8da79efd88a5))

## [10.3.1](https://github.com/geostyler/geostyler/compare/v10.3.0...v10.3.1) (2022-12-13)


### ⚠ BREAKING CHANGES

* The components DragDroppable, DropIndicator, Removable as well as
DndUtil and the useDragDrop hook were removed. Component RemovableItem
was moved from src/Components/Removable/RemovableItem/RemovableItem.tsx
one level up to src/Components/RemovableItem/RemovableItem.tsx. The
newly introduced ref forwarding for SymbolizerCard and RuleCard were
removed.

* replace react-dnd with dnd-kit ([30e19de](https://github.com/geostyler/geostyler/commit/30e19de16a6310dcd79bf4e4292b33bf80004c0d))

## [10.3.0](https://github.com/geostyler/geostyler/compare/v10.2.0...v10.3.0) (2022-12-07)


### Features

* add Drag and Drop for rules and symbolizers to CardStyle ([33dbbbb](https://github.com/geostyler/geostyler/commit/33dbbbbef4854f90c1f9f8e2670a032c1f431407))


### Bugfixes

* translating 3 todos in fr ([#1997](https://github.com/geostyler/geostyler/issues/1997)) ([5e490f3](https://github.com/geostyler/geostyler/commit/5e490f380c15c741e4673098c42d157a86ce9edc))

## [10.2.0](https://github.com/geostyler/geostyler/compare/v10.1.0...v10.2.0) (2022-11-24)


### Features

* add uploadButtonProps to DataLoader ([7c4976c](https://github.com/geostyler/geostyler/commit/7c4976c5a7cdcc7afcdd579d9b6a54dbc3a919d6))
* adds srsName field to the WfsParserInput ([0c2a1c1](https://github.com/geostyler/geostyler/commit/0c2a1c1b9cc58d239a08f0ec86aeca957f23a61a))


### Bugfixes

* add check for empty extent to PreviewMap ([e8a881c](https://github.com/geostyler/geostyler/commit/e8a881c4b383a1fad7fee9440473659921b5ee64))
* add ColorRampCombo to index exports ([9e0b985](https://github.com/geostyler/geostyler/commit/9e0b9853384a1eb7b4b650bb4f1e5fbb8c98498f))
* fix onValueChange for between comparions ([f38330b](https://github.com/geostyler/geostyler/commit/f38330b2c9c40bbcf6357575d26380a94571a6c2))
* fix style of ColorRampCombo ([d36790a](https://github.com/geostyler/geostyler/commit/d36790af0cc765ad158dcf0cd416254fd551f00b))
* use UploadButtonProps ([4fbd55f](https://github.com/geostyler/geostyler/commit/4fbd55fc190eb0763078e96ea03cdf99bbcb0852))

## [10.1.0](https://github.com/geostyler/geostyler/compare/v10.0.0...v10.1.0) (2022-11-17)


### Features

* add clear button to color field ([#1945](https://github.com/geostyler/geostyler/issues/1945)) ([1dcd404](https://github.com/geostyler/geostyler/commit/1dcd4041f64ce4990fc7336ea9b4590705d27a06))


### Dependencies

* update version to 10.0.0 ([791a7a7](https://github.com/geostyler/geostyler/commit/791a7a7d813641badd733e561ec6ca0d24fab681))


### Changes in configuration

* update releaserc ([62199d1](https://github.com/geostyler/geostyler/commit/62199d1aca5ad92b7c2d8773174b146ea727da46))
* use strict mode for tsconfig ([#1955](https://github.com/geostyler/geostyler/issues/1955)) ([c5c8201](https://github.com/geostyler/geostyler/commit/c5c8201577f278335484edebfc77c93aa6bced1c))


### Bugfixes

* add check for string before using .toLowerCase() in TextFilterField ([fea7117](https://github.com/geostyler/geostyler/commit/fea71179d212b662c502ce970bbaec98cb50fa02))
* extend version range to allow ol >=6 ([abbcc98](https://github.com/geostyler/geostyler/commit/abbcc98d7fe8c98aae62a1a6fbcc832b5d67e896))
* fix onStyleChange for async readStyle ([9416ddd](https://github.com/geostyler/geostyler/commit/9416ddd9481009b1695d73d4243a6ca1a0dc5385))
* introduce useRef for timeout ([1ed49f4](https://github.com/geostyler/geostyler/commit/1ed49f4fde38db4b50dcdb757ab9fcaebcda77eb))

## [10.0.0](https://github.com/geostyler/geostyler/compare/v9.0.1...v10.0.0) (2022-11-15)


### Features

* introduces FieldUtil ([d592d99](https://github.com/geostyler/geostyler/commit/d592d997b4afb81f954113eb35a54dc7805b0a5d))
* introduces UnsupportedPropertiesContext ([1fc6be5](https://github.com/geostyler/geostyler/commit/1fc6be53a2e1b5b76d1d3fc0134995fc61591851))


### Changes in configuration

* fix copy/paste left-over in .releaserc ([a115028](https://github.com/geostyler/geostyler/commit/a115028ba8f4b776840c22e28044a6ec06f0a736))
* introduce husky ([46f8c7d](https://github.com/geostyler/geostyler/commit/46f8c7d80dddf31137645361155e26df16d9ea22))
* introduce semanti release ([d3820a7](https://github.com/geostyler/geostyler/commit/d3820a7d983c27d156426e4039049bbed5121177))


### Bugfixes

* add missing CardLayout to index.ts ([11299e0](https://github.com/geostyler/geostyler/commit/11299e0ab7c52568603a135929b27daa000fa660))
* close curly braces on template attributes ([84fc4d1](https://github.com/geostyler/geostyler/commit/84fc4d16944b6f3ff3b497892d342a369a24aa2d))
* fix the width of some input fields ([e3de4cf](https://github.com/geostyler/geostyler/commit/e3de4cffa5dcfd1ce6ce7cc8cfe13b24fb95dc27))
* fixes label in FillEditor ([cbc757e](https://github.com/geostyler/geostyler/commit/cbc757e250d6b3178f905dd976d5ed8330c47034))
* fixes uploadbutton loading icon ([a4cc6ed](https://github.com/geostyler/geostyler/commit/a4cc6ed808ad92ace1d6395a79ae5f9e9900fbe7))
* remove unused import in example ([8856067](https://github.com/geostyler/geostyler/commit/88560678ccb62bd5e27e0f560cb00920f593eff1))
* undo propName adaption ([483c032](https://github.com/geostyler/geostyler/commit/483c0323f64838de48d04c92af3f25d80fcf5688))
* zoom to data if provided ([a6d4440](https://github.com/geostyler/geostyler/commit/a6d4440754caf76d8d03bc0805113e07e1b2ee8b))


### Breaking changes

* add nullToUndefined to onChange listener ([43757e2](https://github.com/geostyler/geostyler/commit/43757e2652f5e00568eb76bdb5377497533831e2))
* applies translations to FilterEditor ([f2286e8](https://github.com/geostyler/geostyler/commit/f2286e80647bf29d17d89c8f65e2bb614e923506))
* package updates ([#1951](https://github.com/geostyler/geostyler/issues/1951)) ([6c3b917](https://github.com/geostyler/geostyler/commit/6c3b91724e9354fe1bcbbec84a3cdb8b8d39e643))
* update geostyler-wfs-parser ([acc20e9](https://github.com/geostyler/geostyler/commit/acc20e9c680a2c7b1bee501bb3d44ce75d8d2dfe))
