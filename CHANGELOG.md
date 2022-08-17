## 1.0.0 (2022-08-17)


### ⚠ BREAKING CHANGES

* switch to named exports, ESM only

### Features

* convert to typescript ([#2](https://github.com/nickreynolds/nat-port-mapper/issues/2)) ([e46bb43](https://github.com/nickreynolds/nat-port-mapper/commit/e46bb43225a1c717bb2ed1bc8527ab66fe164a11))


### Bug Fixes

* add error listener to ssdp ([#16](https://github.com/nickreynolds/nat-port-mapper/issues/16)) ([afafb69](https://github.com/nickreynolds/nat-port-mapper/commit/afafb6993bbfc62030091ad7099e464035282168))
* browser shim ([#3](https://github.com/nickreynolds/nat-port-mapper/issues/3)) ([6d095f8](https://github.com/nickreynolds/nat-port-mapper/commit/6d095f84f10e0da1c2f5b1b6a38cbb01eea123ba))
* cache resolved gateway until timeout ([#15](https://github.com/nickreynolds/nat-port-mapper/issues/15)) ([1ad50c3](https://github.com/nickreynolds/nat-port-mapper/commit/1ad50c34a1a5889bc3271073d85abdfe3e565b1f)), closes [#14](https://github.com/nickreynolds/nat-port-mapper/issues/14)
* clear timeouts and shut down servers ([#14](https://github.com/nickreynolds/nat-port-mapper/issues/14)) ([9219952](https://github.com/nickreynolds/nat-port-mapper/commit/9219952244710555e93d72679f50956e411517b6))
* pass a noop as a callback to bound functions ([9996370](https://github.com/nickreynolds/nat-port-mapper/commit/999637035a460679cdf71c8b2561a0c84982f07a)), closes [#24](https://github.com/nickreynolds/nat-port-mapper/issues/24)
* shut down cleanly ([#17](https://github.com/nickreynolds/nat-port-mapper/issues/17)) ([8a157c4](https://github.com/nickreynolds/nat-port-mapper/commit/8a157c4223ac1d19b5d05d6ef3372a0e129ff790))
* update xml2js parser options ([#2](https://github.com/nickreynolds/nat-port-mapper/issues/2)) ([#13](https://github.com/nickreynolds/nat-port-mapper/issues/13)) ([389c2f2](https://github.com/nickreynolds/nat-port-mapper/commit/389c2f2ecfad84ae61ee4f6dc3d457c32f3b2e77))


### Trivial Changes

* bump readme ([075f9d4](https://github.com/nickreynolds/nat-port-mapper/commit/075f9d400fc4f9269a7635837289dcdc70aef5ca))
* **deps:** bump @libp2p/logger from 1.1.6 to 2.0.0 ([#18](https://github.com/nickreynolds/nat-port-mapper/issues/18)) ([22a9b05](https://github.com/nickreynolds/nat-port-mapper/commit/22a9b059a23abb649d5658c272a5b067bc971261))
* **release:** 1.0.0 [skip ci] ([de85119](https://github.com/nickreynolds/nat-port-mapper/commit/de8511933ab8478642d06b871e19d72aa50bb858)), closes [#2](https://github.com/nickreynolds/nat-port-mapper/issues/2) [#24](https://github.com/nickreynolds/nat-port-mapper/issues/24)
* **release:** 1.0.1 [skip ci] ([e451365](https://github.com/nickreynolds/nat-port-mapper/commit/e451365dff7acd8fa19bae562daac50e46651176)), closes [#3](https://github.com/nickreynolds/nat-port-mapper/issues/3)
* **release:** 1.0.2 [skip ci] ([364b885](https://github.com/nickreynolds/nat-port-mapper/commit/364b885b5f89e63e3d0e9fece6a253cd1baf6fa8)), closes [#2](https://github.com/nickreynolds/nat-port-mapper/issues/2) [#13](https://github.com/nickreynolds/nat-port-mapper/issues/13)
* **release:** 1.0.3 [skip ci] ([04999d9](https://github.com/nickreynolds/nat-port-mapper/commit/04999d9190ff545981f54d1dbe341b72d5832cbd)), closes [#14](https://github.com/nickreynolds/nat-port-mapper/issues/14)
* **release:** 1.0.4 [skip ci] ([6d95c45](https://github.com/nickreynolds/nat-port-mapper/commit/6d95c450aeed39dddb3a35a0f24588597a0813ba)), closes [#15](https://github.com/nickreynolds/nat-port-mapper/issues/15) [#14](https://github.com/nickreynolds/nat-port-mapper/issues/14)
* **release:** 1.0.5 [skip ci] ([c3b6b75](https://github.com/nickreynolds/nat-port-mapper/commit/c3b6b75257fb5620c4c9ed1f0457cf98f7b76e22)), closes [#16](https://github.com/nickreynolds/nat-port-mapper/issues/16)
* **release:** 1.0.6 [skip ci] ([3b357d3](https://github.com/nickreynolds/nat-port-mapper/commit/3b357d33fd6533c3e6c6b8a208eeab9fc09e94a8)), closes [#17](https://github.com/nickreynolds/nat-port-mapper/issues/17)
* **release:** 1.0.7 [skip ci] ([68febb1](https://github.com/nickreynolds/nat-port-mapper/commit/68febb1eff164f1f2c7562e9405feec5989b53a6)), closes [#18](https://github.com/nickreynolds/nat-port-mapper/issues/18)
* update names ([4999aec](https://github.com/nickreynolds/nat-port-mapper/commit/4999aec5b6a425c610286fd80d150a2d57edd5a8))

## [1.0.7](https://github.com/achingbrain/nat-port-mapper/compare/v1.0.6...v1.0.7) (2022-06-16)


### Trivial Changes

* **deps:** bump @libp2p/logger from 1.1.6 to 2.0.0 ([#18](https://github.com/achingbrain/nat-port-mapper/issues/18)) ([22a9b05](https://github.com/achingbrain/nat-port-mapper/commit/22a9b059a23abb649d5658c272a5b067bc971261))

### [1.0.6](https://github.com/achingbrain/nat-port-mapper/compare/v1.0.5...v1.0.6) (2022-05-26)


### Bug Fixes

* shut down cleanly ([#17](https://github.com/achingbrain/nat-port-mapper/issues/17)) ([8a157c4](https://github.com/achingbrain/nat-port-mapper/commit/8a157c4223ac1d19b5d05d6ef3372a0e129ff790))

### [1.0.5](https://github.com/achingbrain/nat-port-mapper/compare/v1.0.4...v1.0.5) (2022-05-20)


### Bug Fixes

* add error listener to ssdp ([#16](https://github.com/achingbrain/nat-port-mapper/issues/16)) ([afafb69](https://github.com/achingbrain/nat-port-mapper/commit/afafb6993bbfc62030091ad7099e464035282168))

### [1.0.4](https://github.com/achingbrain/nat-port-mapper/compare/v1.0.3...v1.0.4) (2022-05-19)


### Bug Fixes

* cache resolved gateway until timeout ([#15](https://github.com/achingbrain/nat-port-mapper/issues/15)) ([1ad50c3](https://github.com/achingbrain/nat-port-mapper/commit/1ad50c34a1a5889bc3271073d85abdfe3e565b1f)), closes [#14](https://github.com/achingbrain/nat-port-mapper/issues/14)

### [1.0.3](https://github.com/achingbrain/nat-port-mapper/compare/v1.0.2...v1.0.3) (2022-05-18)


### Bug Fixes

* clear timeouts and shut down servers ([#14](https://github.com/achingbrain/nat-port-mapper/issues/14)) ([9219952](https://github.com/achingbrain/nat-port-mapper/commit/9219952244710555e93d72679f50956e411517b6))

### [1.0.2](https://github.com/achingbrain/nat-port-mapper/compare/v1.0.1...v1.0.2) (2022-05-17)


### Bug Fixes

* update xml2js parser options ([#2](https://github.com/achingbrain/nat-port-mapper/issues/2)) ([#13](https://github.com/achingbrain/nat-port-mapper/issues/13)) ([389c2f2](https://github.com/achingbrain/nat-port-mapper/commit/389c2f2ecfad84ae61ee4f6dc3d457c32f3b2e77))

### [1.0.1](https://github.com/achingbrain/upnp-nat/compare/v1.0.0...v1.0.1) (2022-03-11)


### Bug Fixes

* browser shim ([#3](https://github.com/achingbrain/upnp-nat/issues/3)) ([6d095f8](https://github.com/achingbrain/upnp-nat/commit/6d095f84f10e0da1c2f5b1b6a38cbb01eea123ba))

## 1.0.0 (2022-02-27)


### ⚠ BREAKING CHANGES

* switch to named exports, ESM only

### Features

* convert to typescript ([#2](https://github.com/achingbrain/upnp-nat/issues/2)) ([e46bb43](https://github.com/achingbrain/upnp-nat/commit/e46bb43225a1c717bb2ed1bc8527ab66fe164a11))


### Bug Fixes

* pass a noop as a callback to bound functions ([9996370](https://github.com/achingbrain/upnp-nat/commit/999637035a460679cdf71c8b2561a0c84982f07a)), closes [#24](https://github.com/achingbrain/upnp-nat/issues/24)
