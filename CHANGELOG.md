# Changelog

[npm history][1]

[1]: https://www.npmjs.com/package/@google-cloud/kms?activeTab=versions

## v0.3.0

01-15-2019 10:50 PST

### Implementation Changes
- Add iam_policy proto ([#101](https://github.com/googleapis/nodejs-kms/pull/101))

### Dependencies
- fix(deps): update dependency google-gax to ^0.23.0 ([#105](https://github.com/googleapis/nodejs-kms/pull/105))
- fix(deps): update dependency google-gax to ^0.22.0 ([#73](https://github.com/googleapis/nodejs-kms/pull/73))
- chore(deps): update dependency @google-cloud/nodejs-repo-tools to v3 ([#71](https://github.com/googleapis/nodejs-kms/pull/71))
- chore(deps): update dependency through2 to v3 ([#67](https://github.com/googleapis/nodejs-kms/pull/67))
- chore(deps): update dependency eslint-plugin-node to v8 ([#59](https://github.com/googleapis/nodejs-kms/pull/59))
- chore(deps): update dependency eslint-plugin-prettier to v3 ([#44](https://github.com/googleapis/nodejs-kms/pull/44))

### Documentation
- build: check broken links in generated docs ([#102](https://github.com/googleapis/nodejs-kms/pull/102))
- fix(docs): remove unused IAM message types ([#103](https://github.com/googleapis/nodejs-kms/pull/103))
- docs: Changes 'dencrypt' to 'decrypt' ([#97](https://github.com/googleapis/nodejs-kms/pull/97))
- docs: add samples ([#88](https://github.com/googleapis/nodejs-kms/pull/88))
- docs: update readme badges ([#81](https://github.com/googleapis/nodejs-kms/pull/81))

### Internal / Testing Changes
- chore(build): inject yoshi automation key ([#96](https://github.com/googleapis/nodejs-kms/pull/96))
- chore: update nyc and eslint configs ([#95](https://github.com/googleapis/nodejs-kms/pull/95))
- chore: fix publish.sh permission +x ([#93](https://github.com/googleapis/nodejs-kms/pull/93))
- fix(build): fix Kokoro release script ([#92](https://github.com/googleapis/nodejs-kms/pull/92))
- build: add Kokoro configs for autorelease ([#91](https://github.com/googleapis/nodejs-kms/pull/91))
- chore: always nyc report before calling codecov ([#87](https://github.com/googleapis/nodejs-kms/pull/87))
- chore: nyc ignore build/test by default ([#86](https://github.com/googleapis/nodejs-kms/pull/86))
- chore: update the renovate config ([#84](https://github.com/googleapis/nodejs-kms/pull/84))
- chore: update license file ([#83](https://github.com/googleapis/nodejs-kms/pull/83))
- fix(build): fix system key decryption ([#79](https://github.com/googleapis/nodejs-kms/pull/79))
- chore: add a synth.metadata
- chore: update eslintignore config ([#72](https://github.com/googleapis/nodejs-kms/pull/72))
- chore: update lint rules ([#69](https://github.com/googleapis/nodejs-kms/pull/69))
- chore: drop contributors from multiple places ([#70](https://github.com/googleapis/nodejs-kms/pull/70))
- chore: use latest npm on Windows ([#68](https://github.com/googleapis/nodejs-kms/pull/68))
- chore: update CircleCI config ([#66](https://github.com/googleapis/nodejs-kms/pull/66))
- chore: include build in eslintignore ([#63](https://github.com/googleapis/nodejs-kms/pull/63))
- chore: update issue templates ([#58](https://github.com/googleapis/nodejs-kms/pull/58))
- chore: remove old issue template ([#56](https://github.com/googleapis/nodejs-kms/pull/56))
- build: run tests on node11 ([#55](https://github.com/googleapis/nodejs-kms/pull/55))
- chores(build): do not collect sponge.xml from windows builds ([#54](https://github.com/googleapis/nodejs-kms/pull/54))
- chores(build): run codecov on continuous builds ([#53](https://github.com/googleapis/nodejs-kms/pull/53))
- chore: update new issue template ([#52](https://github.com/googleapis/nodejs-kms/pull/52))
- build: fix codecov uploading on Kokoro ([#48](https://github.com/googleapis/nodejs-kms/pull/48))
- Update kokoro config ([#45](https://github.com/googleapis/nodejs-kms/pull/45))
- test: remove appveyor config ([#41](https://github.com/googleapis/nodejs-kms/pull/41))
- Enable prefer-const in the eslint config ([#38](https://github.com/googleapis/nodejs-kms/pull/38))

## v0.2.0

### New Features
- Add new features to the library ([#33](https://github.com/googleapis/nodejs-kms/pull/33))
  - CryptoKeyPurpose: ASSYMETRIC_SIGN, ASSYMETRIC_DECRYPT
  - CryptoKeyVersion
  - KeyOperationAttestation
  - various improved code documentation

### Dependencies
- fix(deps): update dependency google-gax to ^0.20.0 ([#34](https://github.com/googleapis/nodejs-kms/pull/34))
- chore(deps): update dependency nyc to v13 ([#25](https://github.com/googleapis/nodejs-kms/pull/25))
- fix(deps): update dependency google-gax to ^0.19.0 ([#22](https://github.com/googleapis/nodejs-kms/pull/22))

### Internal / Testing Changes
- Enable no-var in eslint ([#35](https://github.com/googleapis/nodejs-kms/pull/35))
- Update CI config ([#32](https://github.com/googleapis/nodejs-kms/pull/32))
- Retry npm install in CI ([#30](https://github.com/googleapis/nodejs-kms/pull/30))
- Update CI config ([#27](https://github.com/googleapis/nodejs-kms/pull/27))

