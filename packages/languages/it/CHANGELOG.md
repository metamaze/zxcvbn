# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 4.0.0 (2023-04-12)

- feat!: makes language packages tree shakeable (#176) ([3be6ae2](https://github.com/zxcvbn-ts/zxcvbn/commit/3be6ae2ae3f4ff7ade756df50c60274cbc2b0e20)), closes [#176](https://github.com/zxcvbn-ts/zxcvbn/issues/176) [#175](https://github.com/zxcvbn-ts/zxcvbn/issues/175)

### Features

- **language:** add Italian translation ([2d6a322](https://github.com/zxcvbn-ts/zxcvbn/commit/2d6a322e51717f223c1e33181bc461b3b31903d5))
- **languages:** update dictionaries ([7f67d3a](https://github.com/zxcvbn-ts/zxcvbn/commit/7f67d3a71ef3b1136fc965c21d9febbfa3e74193))
- **languages:** update italian translations following proofreading ([#105](https://github.com/zxcvbn-ts/zxcvbn/issues/105)) ([5dc5407](https://github.com/zxcvbn-ts/zxcvbn/commit/5dc54075c87ad317ba95ebef7cb7414a0e2db112))

### Reverts

- Revert "Publish" ([e266524](https://github.com/zxcvbn-ts/zxcvbn/commit/e266524f4fd25684ae9dded81593e7e04a1eef97))

### BREAKING CHANGES

- Language packages no longer has a default export.

Instead of importing language packages with
`import package from '@zxcvbn-ts/language-en'`

You will now have to import it either like this
`import { dictionary, translation } from '@zxcvbn-ts/language-en'`

or like this
`import * as package from '@zxcvbn-ts/language-en'`

The reason for the change is so that you can tree shake the
dictionary and translations.

# 3.0.0 (2023-04-12)

- feat!: makes language packages tree shakeable (#176) ([3be6ae2](https://github.com/zxcvbn-ts/zxcvbn/commit/3be6ae2ae3f4ff7ade756df50c60274cbc2b0e20)), closes [#176](https://github.com/zxcvbn-ts/zxcvbn/issues/176) [#175](https://github.com/zxcvbn-ts/zxcvbn/issues/175)

### Features

- **language:** add Italian translation ([2d6a322](https://github.com/zxcvbn-ts/zxcvbn/commit/2d6a322e51717f223c1e33181bc461b3b31903d5))
- **languages:** update dictionaries ([7f67d3a](https://github.com/zxcvbn-ts/zxcvbn/commit/7f67d3a71ef3b1136fc965c21d9febbfa3e74193))
- **languages:** update italian translations following proofreading ([#105](https://github.com/zxcvbn-ts/zxcvbn/issues/105)) ([5dc5407](https://github.com/zxcvbn-ts/zxcvbn/commit/5dc54075c87ad317ba95ebef7cb7414a0e2db112))

### Reverts

- Revert "Publish" ([e266524](https://github.com/zxcvbn-ts/zxcvbn/commit/e266524f4fd25684ae9dded81593e7e04a1eef97))

### BREAKING CHANGES

- Language packages no longer has a default export.

Instead of importing language packages with
`import package from '@zxcvbn-ts/language-en'`

You will now have to import it either like this
`import { dictionary, translation } from '@zxcvbn-ts/language-en'`

or like this
`import * as package from '@zxcvbn-ts/language-en'`

The reason for the change is so that you can tree shake the
dictionary and translations.

# [2.1.0](https://github.com/zxcvbn-ts/zxcvbn/compare/@zxcvbn-ts/language-it@2.0.1...@zxcvbn-ts/language-it@2.1.0) (2022-09-12)

### Features

- **languages:** update dictionaries ([7f67d3a](https://github.com/zxcvbn-ts/zxcvbn/commit/7f67d3a71ef3b1136fc965c21d9febbfa3e74193))

# 2.0.0 (2022-02-10)

### Features

- **language:** add Italian translation ([2d6a322](https://github.com/zxcvbn-ts/zxcvbn/commit/2d6a322e51717f223c1e33181bc461b3b31903d5))

# 1.2.0 (2022-0-18)

### Features

- **language:** add Italian language pack ([#82](https://github.com/zxcvbn-ts/zxcvbn/issues/98)) ([e6ef77f](https://github.com/zxcvbn-ts/zxcvbn/commit/2d6a322e51717f223c1e33181bc461b3b31903d5))
