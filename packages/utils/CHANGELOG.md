## [3.0.12](https://github.com/libp2p/js-libp2p-utils/compare/v3.0.11...v3.0.12) (2023-06-15)


### Trivial Changes

* Update .github/workflows/semantic-pull-request.yml [skip ci] ([2c91adc](https://github.com/libp2p/js-libp2p-utils/commit/2c91adc7e17fadd9f96c0fc222fb5557df037459))
* Update .github/workflows/stale.yml [skip ci] ([e5fbee9](https://github.com/libp2p/js-libp2p-utils/commit/e5fbee99f549ad708dd375516356c5b20915cf87))


### Dependencies

* **dev:** bump aegir from 38.1.8 to 39.0.10 ([#100](https://github.com/libp2p/js-libp2p-utils/issues/100)) ([da6547c](https://github.com/libp2p/js-libp2p-utils/commit/da6547cdd073ba1a4225be5a419c6776c4ebe6f1))

### Dependencies

* The following workspace dependencies were updated
  * devDependencies
    * @libp2p/peer-id-factory bumped from ^3.0.10 to ^4.0.0

### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^1.0.1 to ^1.0.2
  * devDependencies
    * @libp2p/logger bumped from ^4.0.1 to ^4.0.2
    * @libp2p/peer-id-factory bumped from ^4.0.0 to ^4.0.1

### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^1.0.2 to ^1.1.0
    * @libp2p/peer-collections bumped from ^5.1.1 to ^5.1.2
  * devDependencies
    * @libp2p/logger bumped from ^4.0.2 to ^4.0.3
    * @libp2p/peer-id-factory bumped from ^4.0.1 to ^4.0.2

## [5.3.1](https://github.com/libp2p/js-libp2p/compare/utils-v5.3.0...utils-v5.3.1) (2024-04-15)


### Bug Fixes

* ensure abort listeners are removed from queue jobs ([#2482](https://github.com/libp2p/js-libp2p/issues/2482)) ([f45dc5d](https://github.com/libp2p/js-libp2p/commit/f45dc5dc6f297c0df21262b644160653e83137a3))

## [5.3.0](https://github.com/libp2p/js-libp2p/compare/utils-v5.2.8...utils-v5.3.0) (2024-04-12)


### Features

* add queue success and failure events ([#2481](https://github.com/libp2p/js-libp2p/issues/2481)) ([b17824a](https://github.com/libp2p/js-libp2p/commit/b17824a1d54ef83f32fc658cd7b7a623f809874c))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^1.1.6 to ^1.2.0
    * @libp2p/logger bumped from ^4.0.9 to ^4.0.10
  * devDependencies
    * @libp2p/peer-id-factory bumped from ^4.0.9 to ^4.0.10

## [5.2.8](https://github.com/libp2p/js-libp2p/compare/utils-v5.2.7...utils-v5.2.8) (2024-04-05)


### Bug Fixes

* add @libp2p/record module to monorepo ([#2466](https://github.com/libp2p/js-libp2p/issues/2466)) ([3ffecc5](https://github.com/libp2p/js-libp2p/commit/3ffecc5bfe806a678c1b0228ff830f1811630718))


### Documentation

* update typos in Address Manager and comments ([#2468](https://github.com/libp2p/js-libp2p/issues/2468)) ([a2b41f7](https://github.com/libp2p/js-libp2p/commit/a2b41f7939806dfb9583a6d43ddd8764fc861baf))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^1.1.5 to ^1.1.6
    * @libp2p/logger bumped from ^4.0.8 to ^4.0.9
  * devDependencies
    * @libp2p/peer-id-factory bumped from ^4.0.8 to ^4.0.9

## [5.2.7](https://github.com/libp2p/js-libp2p/compare/utils-v5.2.6...utils-v5.2.7) (2024-03-28)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^1.1.4 to ^1.1.5
    * @libp2p/logger bumped from ^4.0.7 to ^4.0.8
  * devDependencies
    * @libp2p/peer-id-factory bumped from ^4.0.7 to ^4.0.8

## [5.2.6](https://github.com/libp2p/js-libp2p/compare/utils-v5.2.5...utils-v5.2.6) (2024-02-27)


### Documentation

* add doc-check to all modules ([#2419](https://github.com/libp2p/js-libp2p/issues/2419)) ([6cdb243](https://github.com/libp2p/js-libp2p/commit/6cdb24362de9991e749f76b16fcd4c130e8106a0))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^1.1.3 to ^1.1.4
    * @libp2p/logger bumped from ^4.0.6 to ^4.0.7
  * devDependencies
    * @libp2p/peer-id-factory bumped from ^4.0.6 to ^4.0.7

## [5.2.5](https://github.com/libp2p/js-libp2p/compare/utils-v5.2.4...utils-v5.2.5) (2024-02-07)


### Bug Fixes

* give send data a chance to complete before closing stream ([#2399](https://github.com/libp2p/js-libp2p/issues/2399)) ([0c7bbbb](https://github.com/libp2p/js-libp2p/commit/0c7bbbb077d7961570d3cfb42fe431da6de57ede))

## [5.2.4](https://github.com/libp2p/js-libp2p/compare/utils-v5.2.3...utils-v5.2.4) (2024-02-07)


### Bug Fixes

* abort slow sending streams ([#2395](https://github.com/libp2p/js-libp2p/issues/2395)) ([2370d1c](https://github.com/libp2p/js-libp2p/commit/2370d1c3940fe3b0f2b6021800a2398f708f31d1))
* update patch versions of deps ([#2397](https://github.com/libp2p/js-libp2p/issues/2397)) ([0321812](https://github.com/libp2p/js-libp2p/commit/0321812e731515558f35ae2d53242035a343a21a))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^1.1.2 to ^1.1.3
    * @libp2p/logger bumped from ^4.0.5 to ^4.0.6
  * devDependencies
    * @libp2p/peer-id-factory bumped from ^4.0.5 to ^4.0.6

## [5.2.3](https://github.com/libp2p/js-libp2p/compare/utils-v5.2.2...utils-v5.2.3) (2024-01-24)


### Bug Fixes

* add local definition of isPrivateIp ([#2362](https://github.com/libp2p/js-libp2p/issues/2362)) ([f27138c](https://github.com/libp2p/js-libp2p/commit/f27138ca1f552c4ad3e5d325fef626ba6783f0fd))
* allow typing job options in peer queue ([#2372](https://github.com/libp2p/js-libp2p/issues/2372)) ([74fb567](https://github.com/libp2p/js-libp2p/commit/74fb5671dc5184182a2d6c9c4e7d33f43e43d7b6))

## [5.2.2](https://github.com/libp2p/js-libp2p/compare/utils-v5.2.1...utils-v5.2.2) (2024-01-16)


### Bug Fixes

* align dependency versions and update project config ([#2357](https://github.com/libp2p/js-libp2p/issues/2357)) ([8bbd436](https://github.com/libp2p/js-libp2p/commit/8bbd43628343f995804eea3102d0571ddcebc5c4))
* mark all packages side-effect free ([#2360](https://github.com/libp2p/js-libp2p/issues/2360)) ([3c96210](https://github.com/libp2p/js-libp2p/commit/3c96210cf6343b21199996918bae3a0f60220046))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^1.1.1 to ^1.1.2
    * @libp2p/logger bumped from ^4.0.4 to ^4.0.5
  * devDependencies
    * @libp2p/peer-id-factory bumped from ^4.0.4 to ^4.0.5

## [5.2.1](https://github.com/libp2p/js-libp2p/compare/utils-v5.2.0...utils-v5.2.1) (2024-01-12)


### Bug Fixes

* replace rate-limiter ([#2356](https://github.com/libp2p/js-libp2p/issues/2356)) ([ddaa59a](https://github.com/libp2p/js-libp2p/commit/ddaa59a600c031fe1f41ba2097ebfcfd74eff598))


### Dependencies

* The following workspace dependencies were updated
  * devDependencies
    * @libp2p/peer-id-factory bumped from ^4.0.3 to ^4.0.4

## [5.2.0](https://github.com/libp2p/js-libp2p/compare/utils-v5.1.1...utils-v5.2.0) (2024-01-06)


### Features

* add tracked list to utils ([#2338](https://github.com/libp2p/js-libp2p/issues/2338)) ([581574d](https://github.com/libp2p/js-libp2p/commit/581574d6d6d94e2d44530f1c959fd1fcededf095))


### Bug Fixes

* remove extra deps ([#2340](https://github.com/libp2p/js-libp2p/issues/2340)) ([53e83ee](https://github.com/libp2p/js-libp2p/commit/53e83eea50410391ec9cff4cd8097210b93894ff))
* replace p-queue with less restrictive queue ([#2339](https://github.com/libp2p/js-libp2p/issues/2339)) ([528d737](https://github.com/libp2p/js-libp2p/commit/528d73781f416ea97af044bb49d9701f97c9eeec))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^1.1.0 to ^1.1.1
    * @libp2p/logger bumped from ^4.0.3 to ^4.0.4
  * devDependencies
    * @libp2p/peer-id-factory bumped from ^4.0.2 to ^4.0.3

## [5.1.0](https://github.com/libp2p/js-libp2p/compare/utils-v5.0.3...utils-v5.1.0) (2023-12-19)


### Features

* allow joining jobs in peer queues ([#2316](https://github.com/libp2p/js-libp2p/issues/2316)) ([9eff7ef](https://github.com/libp2p/js-libp2p/commit/9eff7eff0ea6f54bc6c24a8bc4736ba0e2807c8b))


### Bug Fixes

* remove results map on job queue clear ([#2320](https://github.com/libp2p/js-libp2p/issues/2320)) ([230afea](https://github.com/libp2p/js-libp2p/commit/230afea4b2919486bd8d61d9f0923a7761a6d2a0))

## [5.0.1](https://github.com/libp2p/js-libp2p/compare/utils-v5.0.0...utils-v5.0.1) (2023-11-30)


### Bug Fixes

* restore lost commits ([#2268](https://github.com/libp2p/js-libp2p/issues/2268)) ([5775f1d](https://github.com/libp2p/js-libp2p/commit/5775f1df4f5561500e622dc0788fdacbc74e2755))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^1.0.0 to ^1.0.1
  * devDependencies
    * @libp2p/logger bumped from ^4.0.0 to ^4.0.1
    * @libp2p/peer-id-factory bumped from ^3.0.9 to ^3.0.10

## [5.0.0](https://www.github.com/libp2p/js-libp2p/compare/utils-v4.0.7...utils-v5.0.0) (2023-11-28)


### ⚠ BREAKING CHANGES

* the `minSendBytes` option has been removed from Mplex since the transport can now decide how to optimise sending data
* imports from `libp2p/circuit-relay` should be updated to `@libp2p/circuit-relay-v2`

### Features

* allow stream muxers and connection encrypters to yield lists ([#2256](https://www.github.com/libp2p/js-libp2p/issues/2256)) ([4a474d5](https://www.github.com/libp2p/js-libp2p/commit/4a474d54d3299e0ac30fa143b57436b3cf45e426))


### Bug Fixes

* close maconn stream after reading/writing ([#2236](https://www.github.com/libp2p/js-libp2p/issues/2236)) ([9c67c5b](https://www.github.com/libp2p/js-libp2p/commit/9c67c5b3d0ab63c7a1a62f363ae732b300ef6b87))
* use logging component everywhere ([#2228](https://www.github.com/libp2p/js-libp2p/issues/2228)) ([e5dfde0](https://www.github.com/libp2p/js-libp2p/commit/e5dfde0883191c93903ca552433f177d48adf0b3))
* use optimistic protocol negotation ([#2253](https://www.github.com/libp2p/js-libp2p/issues/2253)) ([0b4a2ee](https://www.github.com/libp2p/js-libp2p/commit/0b4a2ee7983b4dc9dc0a7b705a202a4c550e7017))


### Code Refactoring

* extract circuit relay v2 to separate module ([#2222](https://www.github.com/libp2p/js-libp2p/issues/2222)) ([24afba3](https://www.github.com/libp2p/js-libp2p/commit/24afba30004fb7f24af1f0180229bb164340f00b))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^0.1.6 to ^1.0.0
  * devDependencies
    * @libp2p/logger bumped from ^3.1.0 to ^4.0.0
    * @libp2p/peer-id-factory bumped from ^3.0.8 to ^3.0.9

### [4.0.7](https://www.github.com/libp2p/js-libp2p/compare/utils-v4.0.6...utils-v4.0.7) (2023-11-07)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^0.1.5 to ^0.1.6
    * @libp2p/logger bumped from ^3.0.5 to ^3.1.0

### [4.0.6](https://www.github.com/libp2p/js-libp2p/compare/utils-v4.0.5...utils-v4.0.6) (2023-11-03)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^0.1.4 to ^0.1.5
    * @libp2p/logger bumped from ^3.0.4 to ^3.0.5

### [4.0.5](https://www.github.com/libp2p/js-libp2p/compare/utils-v4.0.4...utils-v4.0.5) (2023-10-25)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^0.1.3 to ^0.1.4
    * @libp2p/logger bumped from ^3.0.3 to ^3.0.4

### [4.0.4](https://www.github.com/libp2p/js-libp2p/compare/utils-v4.0.3...utils-v4.0.4) (2023-10-06)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^0.1.2 to ^0.1.3
    * @libp2p/logger bumped from ^3.0.2 to ^3.0.3

### [4.0.3](https://www.github.com/libp2p/js-libp2p/compare/utils-v4.0.2...utils-v4.0.3) (2023-09-10)


### Bug Fixes

* **libp2p:** sort addresses to dial as public, then relay ([#2031](https://www.github.com/libp2p/js-libp2p/issues/2031)) ([5294f14](https://www.github.com/libp2p/js-libp2p/commit/5294f14caa314bb150554afff3a7ff45d2bf17ba))

### [4.0.2](https://www.github.com/libp2p/js-libp2p/compare/utils-v4.0.1...utils-v4.0.2) (2023-08-14)


### Bug Fixes

* **@libp2p/utils:** switch to @chainsafe/is-ip ([#1957](https://www.github.com/libp2p/js-libp2p/issues/1957)) ([18567b7](https://www.github.com/libp2p/js-libp2p/commit/18567b7cfcca605b2d586cef9275554099959bc8)), closes [#1926](https://www.github.com/libp2p/js-libp2p/issues/1926)
* update project config ([9c0353c](https://www.github.com/libp2p/js-libp2p/commit/9c0353cf5a1e13196ca0e7764f87e36478518f69))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^0.1.1 to ^0.1.2
    * @libp2p/logger bumped from ^3.0.1 to ^3.0.2

### [4.0.1](https://www.github.com/libp2p/js-libp2p/compare/utils-v4.0.0...utils-v4.0.1) (2023-08-05)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^0.1.0 to ^0.1.1
    * @libp2p/logger bumped from ^3.0.0 to ^3.0.1

## [4.0.0](https://www.github.com/libp2p/js-libp2p/compare/utils-v3.0.12...utils-v4.0.0) (2023-07-31)


### ⚠ BREAKING CHANGES

* the `.close`, `closeRead` and `closeWrite` methods on the `Stream` interface are now asynchronous
* `stream.stat.*` and `conn.stat.*` properties are now accessed via `stream.*` and `conn.*`
* consolidate interface modules (#1833)

### Features

* merge stat properties into stream/connection objects ([#1856](https://www.github.com/libp2p/js-libp2p/issues/1856)) ([e9cafd3](https://www.github.com/libp2p/js-libp2p/commit/e9cafd3d8ab0f8e0655ff44e04aa41fccc912b51)), closes [#1849](https://www.github.com/libp2p/js-libp2p/issues/1849)


### Bug Fixes

* close streams gracefully ([#1864](https://www.github.com/libp2p/js-libp2p/issues/1864)) ([b36ec7f](https://www.github.com/libp2p/js-libp2p/commit/b36ec7f24e477af21cec31effc086a6c611bf271)), closes [#1793](https://www.github.com/libp2p/js-libp2p/issues/1793) [#656](https://www.github.com/libp2p/js-libp2p/issues/656)
* consolidate interface modules ([#1833](https://www.github.com/libp2p/js-libp2p/issues/1833)) ([4255b1e](https://www.github.com/libp2p/js-libp2p/commit/4255b1e2485d31e00c33efa029b6426246ea23e3))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ~0.0.1 to ^0.1.0
    * @libp2p/logger bumped from ^2.0.0 to ^3.0.0

## [3.0.11](https://github.com/libp2p/js-libp2p-utils/compare/v3.0.10...v3.0.11) (2023-04-24)


### Dependencies

* bump @libp2p/interface-peer-store from 1.2.9 to 2.0.0 ([#91](https://github.com/libp2p/js-libp2p-utils/issues/91)) ([c7569d7](https://github.com/libp2p/js-libp2p-utils/commit/c7569d77a56d5fc3a5323c89ba93230206c35d2b))

## [3.0.10](https://github.com/libp2p/js-libp2p-utils/compare/v3.0.9...v3.0.10) (2023-04-18)


### Dependencies

* bump it-stream-types from 1.0.5 to 2.0.1 ([#89](https://github.com/libp2p/js-libp2p-utils/issues/89)) ([0de4a85](https://github.com/libp2p/js-libp2p-utils/commit/0de4a85bd6caa3dfec673ceb3be9130d4051e407))

## [3.0.9](https://github.com/libp2p/js-libp2p-utils/compare/v3.0.8...v3.0.9) (2023-04-18)


### Dependencies

* **dev:** bump it-all from 2.0.1 to 3.0.1 ([#85](https://github.com/libp2p/js-libp2p-utils/issues/85)) ([b029517](https://github.com/libp2p/js-libp2p-utils/commit/b0295176c2c6553209ebb26149497a5f9a73fc9e))
* **dev:** bump it-map from 2.0.1 to 3.0.2 ([#88](https://github.com/libp2p/js-libp2p-utils/issues/88)) ([6e24d5a](https://github.com/libp2p/js-libp2p-utils/commit/6e24d5a91b4df40c7a395d3d3c9379120de0754d))

## [3.0.8](https://github.com/libp2p/js-libp2p-utils/compare/v3.0.7...v3.0.8) (2023-04-12)


### Dependencies

* bump @libp2p/interface-connection from 3.1.1 to 4.0.0 ([#90](https://github.com/libp2p/js-libp2p-utils/issues/90)) ([d140507](https://github.com/libp2p/js-libp2p-utils/commit/d140507f1d4263886c515f4877425a01f28b88e7))

## [3.0.7](https://github.com/libp2p/js-libp2p-utils/compare/v3.0.6...v3.0.7) (2023-03-31)


### Dependencies

* **dev:** bump it-pipe from 2.0.5 to 3.0.0 ([#87](https://github.com/libp2p/js-libp2p-utils/issues/87)) ([fc28634](https://github.com/libp2p/js-libp2p-utils/commit/fc286345ff55e23b7619da2bdcedfd848d7c1f85))

## [3.0.6](https://github.com/libp2p/js-libp2p-utils/compare/v3.0.5...v3.0.6) (2023-03-27)


### Bug Fixes

* handle non ip4/ip6/dns addresses in isPrivate ([#84](https://github.com/libp2p/js-libp2p-utils/issues/84)) ([af2c222](https://github.com/libp2p/js-libp2p-utils/commit/af2c2221ad175a06f758a45fc71fbb2f870eece4))

## [3.0.5](https://github.com/libp2p/js-libp2p-utils/compare/v3.0.4...v3.0.5) (2023-03-17)


### Trivial Changes

* replace err-code with CodeError ([#70](https://github.com/libp2p/js-libp2p-utils/issues/70)) ([beb252d](https://github.com/libp2p/js-libp2p-utils/commit/beb252d79f69d0f49d1fa4fd664a49e33ff80cd3)), closes [js-libp2p#1269](https://github.com/libp2p/js-libp2p/issues/1269)
* Update .github/workflows/semantic-pull-request.yml [skip ci] ([acad1fe](https://github.com/libp2p/js-libp2p-utils/commit/acad1fe38a1cfef19f63de7283e721caec059d34))
* Update .github/workflows/semantic-pull-request.yml [skip ci] ([1b96837](https://github.com/libp2p/js-libp2p-utils/commit/1b96837cac6c9625ed243d0f62595582a57f7f04))
* Update .github/workflows/semantic-pull-request.yml [skip ci] ([10d6e7a](https://github.com/libp2p/js-libp2p-utils/commit/10d6e7a7731b746f199ffb2f186e28185cb512f5))


### Dependencies

* bump @multiformats/multiaddr from 11.6.1 to 12.0.0 ([#83](https://github.com/libp2p/js-libp2p-utils/issues/83)) ([3eeeeba](https://github.com/libp2p/js-libp2p-utils/commit/3eeeeba52b764b96463a1b6bcfcff394492eab2e))
* **dev:** bump aegir from 37.12.1 to 38.1.7 ([#80](https://github.com/libp2p/js-libp2p-utils/issues/80)) ([2c262ba](https://github.com/libp2p/js-libp2p-utils/commit/2c262ba37d3668bc4f957914c40c5167cd8faf4f))

## [3.0.4](https://github.com/libp2p/js-libp2p-utils/compare/v3.0.3...v3.0.4) (2022-12-16)


### Documentation

* publish api docs ([#69](https://github.com/libp2p/js-libp2p-utils/issues/69)) ([044fd72](https://github.com/libp2p/js-libp2p-utils/commit/044fd7232eb0be2d8cd71fab6130c4f30190e22b))

## [3.0.3](https://github.com/libp2p/js-libp2p-utils/compare/v3.0.2...v3.0.3) (2022-12-07)


### Bug Fixes

* update project readme ([#66](https://github.com/libp2p/js-libp2p-utils/issues/66)) ([7e977a2](https://github.com/libp2p/js-libp2p-utils/commit/7e977a2739717225a4b1d74304e69500652a3386))


### Dependencies

* bump private-ip from 2.3.4 to 3.0.0 ([#63](https://github.com/libp2p/js-libp2p-utils/issues/63)) ([956f404](https://github.com/libp2p/js-libp2p-utils/commit/956f404bba12f2c712999046b19825496fe8be41)), closes [ChainSafe/is-ip#1](https://github.com/ChainSafe/is-ip/issues/1) [#19](https://github.com/libp2p/js-libp2p-utils/issues/19) [#21](https://github.com/libp2p/js-libp2p-utils/issues/21)
* **dev:** bump it-all from 1.0.6 to 2.0.0 ([#62](https://github.com/libp2p/js-libp2p-utils/issues/62)) ([99cca25](https://github.com/libp2p/js-libp2p-utils/commit/99cca2505721f282ed557dcfd28d8b46d064d6e2)), closes [#28](https://github.com/libp2p/js-libp2p-utils/issues/28) [#28](https://github.com/libp2p/js-libp2p-utils/issues/28) [#27](https://github.com/libp2p/js-libp2p-utils/issues/27) [#24](https://github.com/libp2p/js-libp2p-utils/issues/24)
* **dev:** bump it-map from 1.0.6 to 2.0.0 ([#61](https://github.com/libp2p/js-libp2p-utils/issues/61)) ([88b05b4](https://github.com/libp2p/js-libp2p-utils/commit/88b05b4a6223774cd6dbaaa4f97e1da318f89856))
* **dev:** bump uint8arrays from 3.1.1 to 4.0.2 ([#60](https://github.com/libp2p/js-libp2p-utils/issues/60)) ([ca0b632](https://github.com/libp2p/js-libp2p-utils/commit/ca0b63243b0ae23b6fa9195387466516c9acce80)), closes [#41](https://github.com/libp2p/js-libp2p-utils/issues/41) [#40](https://github.com/libp2p/js-libp2p-utils/issues/40) [#28](https://github.com/libp2p/js-libp2p-utils/issues/28) [#41](https://github.com/libp2p/js-libp2p-utils/issues/41) [#40](https://github.com/libp2p/js-libp2p-utils/issues/40) [#28](https://github.com/libp2p/js-libp2p-utils/issues/28) [#41](https://github.com/libp2p/js-libp2p-utils/issues/41) [#40](https://github.com/libp2p/js-libp2p-utils/issues/40) [#28](https://github.com/libp2p/js-libp2p-utils/issues/28)

## [3.0.2](https://github.com/libp2p/js-libp2p-utils/compare/v3.0.1...v3.0.2) (2022-09-21)


### Trivial Changes

* Update .github/workflows/stale.yml [skip ci] ([ea425dc](https://github.com/libp2p/js-libp2p-utils/commit/ea425dc19253202009497587681da1a7703ac429))


### Dependencies

* update @multiformats/multiaddr to 11.0.0 ([#59](https://github.com/libp2p/js-libp2p-utils/issues/59)) ([46bff23](https://github.com/libp2p/js-libp2p-utils/commit/46bff23bc5296359cfca02fbf078ee197a1629cc))

## [3.0.1](https://github.com/libp2p/js-libp2p-utils/compare/v3.0.0...v3.0.1) (2022-08-10)


### Bug Fixes

* update deps ([#55](https://github.com/libp2p/js-libp2p-utils/issues/55)) ([134c633](https://github.com/libp2p/js-libp2p-utils/commit/134c633f107247ce309ed7da3a29f872615ee920))

## [3.0.0](https://github.com/libp2p/js-libp2p-utils/compare/v2.0.1...v3.0.0) (2022-06-27)


### ⚠ BREAKING CHANGES

* **deps:** the API of the returned MultiaddrConnection has changed

### Trivial Changes

* **deps:** bump @libp2p/interface-connection from 1.0.1 to 2.1.0 ([#51](https://github.com/libp2p/js-libp2p-utils/issues/51)) ([0f99bf8](https://github.com/libp2p/js-libp2p-utils/commit/0f99bf833f7732d74eac4a06fd2b607555c7f34b))

## [2.0.1](https://github.com/libp2p/js-libp2p-utils/compare/v2.0.0...v2.0.1) (2022-06-27)


### Trivial Changes

* remove unused deps ([#52](https://github.com/libp2p/js-libp2p-utils/issues/52)) ([8f339c9](https://github.com/libp2p/js-libp2p-utils/commit/8f339c9a50b466d65b41492abfd1bd88ffa0a38c))

## [2.0.0](https://github.com/libp2p/js-libp2p-utils/compare/v1.0.10...v2.0.0) (2022-06-15)


### ⚠ BREAKING CHANGES

* uses new single-issue libp2p interface modules

### Features

* update libp2p interfaces ([#47](https://github.com/libp2p/js-libp2p-utils/issues/47)) ([018fbe4](https://github.com/libp2p/js-libp2p-utils/commit/018fbe48f3506c0b90dc88779a3f12a2714ab09c))

### [1.0.10](https://github.com/libp2p/js-libp2p-utils/compare/v1.0.9...v1.0.10) (2022-04-07)


### Trivial Changes

* update aegir ([#39](https://github.com/libp2p/js-libp2p-utils/issues/39)) ([34f1fde](https://github.com/libp2p/js-libp2p-utils/commit/34f1fde4310c6571e90a6d312924146e089b5a9d))

### [1.0.9](https://github.com/libp2p/js-libp2p-utils/compare/v1.0.8...v1.0.9) (2022-03-15)


### Bug Fixes

* refactor address sort to be a regular sort function ([#35](https://github.com/libp2p/js-libp2p-utils/issues/35)) ([8d4e3d6](https://github.com/libp2p/js-libp2p-utils/commit/8d4e3d6f1b56d24e4e58df16ded87d3ca4f82a3f))

### [1.0.8](https://github.com/libp2p/js-libp2p-utils/compare/v1.0.7...v1.0.8) (2022-03-03)


### Bug Fixes

* correct update path for stream-to-ma-conn ([#34](https://github.com/libp2p/js-libp2p-utils/issues/34)) ([90cc6f5](https://github.com/libp2p/js-libp2p-utils/commit/90cc6f563c8640ba52ebfe2f8794999664ccd7eb))

### [1.0.7](https://github.com/libp2p/js-libp2p-utils/compare/v1.0.6...v1.0.7) (2022-03-02)


### Bug Fixes

* pass duplex to stream-to-ma-conn not stream ([#33](https://github.com/libp2p/js-libp2p-utils/issues/33)) ([ebc5c60](https://github.com/libp2p/js-libp2p-utils/commit/ebc5c6074c971e39c6e5c5c51e251aa00c544b50))

### [1.0.6](https://github.com/libp2p/js-libp2p-utils/compare/v1.0.5...v1.0.6) (2022-02-10)


### Bug Fixes

* update interfaces ([#32](https://github.com/libp2p/js-libp2p-utils/issues/32)) ([5d960f3](https://github.com/libp2p/js-libp2p-utils/commit/5d960f3d1566ccb9bf043b71eca5a83117955940))

### [1.0.5](https://github.com/libp2p/js-libp2p-utils/compare/v1.0.4...v1.0.5) (2022-01-15)


### Bug Fixes

* update it-* deps to typed versions ([#30](https://github.com/libp2p/js-libp2p-utils/issues/30)) ([b65ae5c](https://github.com/libp2p/js-libp2p-utils/commit/b65ae5c813efdc20ac11a13f349dc914ffc64c48))

### [1.0.4](https://github.com/libp2p/js-libp2p-utils/compare/v1.0.3...v1.0.4) (2022-01-15)


### Trivial Changes

* engines version ([#29](https://github.com/libp2p/js-libp2p-utils/issues/29)) ([47ce53c](https://github.com/libp2p/js-libp2p-utils/commit/47ce53c34b0106101215ed4b3ffe9f1fffd51cb6))

### [1.0.3](https://github.com/libp2p/js-libp2p-utils/compare/v1.0.2...v1.0.3) (2022-01-14)


### Trivial Changes

* project updates ([#23](https://github.com/libp2p/js-libp2p-utils/issues/23)) ([cb7ea61](https://github.com/libp2p/js-libp2p-utils/commit/cb7ea61e6df7a721863ad8fba7c73d376b2c3ab8))

### [1.0.2](https://github.com/libp2p/js-libp2p-utils/compare/v1.0.1...v1.0.2) (2022-01-08)


### Trivial Changes

* add semantic release config ([#22](https://github.com/libp2p/js-libp2p-utils/issues/22)) ([5fcf8c7](https://github.com/libp2p/js-libp2p-utils/commit/5fcf8c7f57864e4e92f6606656cf3ea1f214f0c4))

## [0.4.1](https://github.com/libp2p/js-libp2p-utils/compare/v0.4.0...v0.4.1) (2021-07-08)



# [0.4.0](https://github.com/libp2p/js-libp2p-utils/compare/v0.3.1...v0.4.0) (2021-07-07)


### chore

* update to new multiformats ([#18](https://github.com/libp2p/js-libp2p-utils/issues/18)) ([24ca72c](https://github.com/libp2p/js-libp2p-utils/commit/24ca72c95bf485af513fba59830796a5fcf71437))


### BREAKING CHANGES

* updates multiaddr which uses the new CID class



## [0.3.1](https://github.com/libp2p/js-libp2p-utils/compare/v0.3.0...v0.3.1) (2021-04-12)



# [0.3.0](https://github.com/libp2p/js-libp2p-utils/compare/v0.2.3...v0.3.0) (2021-04-08)


### Features

* add types ([#16](https://github.com/libp2p/js-libp2p-utils/issues/16)) ([e0552b5](https://github.com/libp2p/js-libp2p-utils/commit/e0552b5b6b1d912a8f6f1e39b1a4b70fca91f547))



<a name="0.2.3"></a>
## [0.2.3](https://github.com/libp2p/js-libp2p-utils/compare/v0.2.2...v0.2.3) (2020-11-30)



<a name="0.2.2"></a>
## [0.2.2](https://github.com/libp2p/js-libp2p-utils/compare/v0.2.1...v0.2.2) (2020-11-16)


### Features

* address sorter ([#13](https://github.com/libp2p/js-libp2p-utils/issues/13)) ([cb5e716](https://github.com/libp2p/js-libp2p-utils/commit/cb5e716))



<a name="0.2.1"></a>
## [0.2.1](https://github.com/libp2p/js-libp2p-utils/compare/v0.1.3...v0.2.1) (2020-10-08)


### Chores

* update deps ([#9](https://github.com/libp2p/js-libp2p-utils/issues/9)) ([a2ea68f](https://github.com/libp2p/js-libp2p-utils/commit/a2ea68f))


### Features

* is multiaddr private and loopback ([#10](https://github.com/libp2p/js-libp2p-utils/issues/10)) ([d7fa562](https://github.com/libp2p/js-libp2p-utils/commit/d7fa562))


### BREAKING CHANGES

* - The multiaddr dep of this module uses Uint8Arrays and may not be
  compatible with previous versions

* chore: remove gh url



<a name="0.2.0"></a>
# [0.2.0](https://github.com/libp2p/js-libp2p-utils/compare/v0.1.3...v0.2.0) (2020-08-07)


### Chores

* update deps ([#9](https://github.com/libp2p/js-libp2p-utils/issues/9)) ([a2ea68f](https://github.com/libp2p/js-libp2p-utils/commit/a2ea68f))


### BREAKING CHANGES

* - The multiaddr dep of this module uses Uint8Arrays and may not be
  compatible with previous versions

* chore: remove gh url



<a name="0.1.3"></a>
## [0.1.3](https://github.com/libp2p/js-libp2p-utils/compare/v0.1.2...v0.1.3) (2020-07-15)


### Features

* arrayEquals for non primitive types with equals function ([80668ff](https://github.com/libp2p/js-libp2p-utils/commit/80668ff))



<a name="0.1.2"></a>
## [0.1.2](https://github.com/libp2p/js-libp2p-utils/compare/v0.1.1...v0.1.2) (2020-02-15)


### Features

* stream to multiaddr connection converter ([#2](https://github.com/libp2p/js-libp2p-utils/issues/2)) ([6220631](https://github.com/libp2p/js-libp2p-utils/commit/6220631))



<a name="0.1.1"></a>
## [0.1.1](https://github.com/libp2p/js-libp2p-utils/compare/v0.1.0...v0.1.1) (2020-02-13)



<a name="0.1.0"></a>
# 0.1.0 (2019-09-23)


### Features

* ip port to multiaddr ([#1](https://github.com/libp2p/js-libp2p-utils/issues/1)) ([426b421](https://github.com/libp2p/js-libp2p-utils/commit/426b421))
