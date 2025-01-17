# Changelog

## [2.1.0](https://www.github.com/googleapis/java-common-protos/compare/v2.0.1...v2.1.0) (2021-02-24)


### Features

* Add `ErrorReason` enum from `google.api.error_reason` for Google API and minor proto updates. ([528a2ae](https://www.github.com/googleapis/java-common-protos/commit/528a2ae726e9a63a49e4850078f28a14431c033f))
* add Interval, Month, PhoneNumber type protos ([#80](https://www.github.com/googleapis/java-common-protos/issues/80)) ([696083b](https://www.github.com/googleapis/java-common-protos/commit/696083b83bd3ba906d13cfdd50846971a74b165f))
* Add the `UNORDERED_LIST` enum value for `google.api.field_behavior`. ([#95](https://www.github.com/googleapis/java-common-protos/issues/95)) ([51d6ae0](https://www.github.com/googleapis/java-common-protos/commit/51d6ae0b02c9c7dd32cf55dd0a67181a3f8618fe))
* Enhance the AttributeContext semantics, and other comments update ([#113](https://www.github.com/googleapis/java-common-protos/issues/113)) ([528a2ae](https://www.github.com/googleapis/java-common-protos/commit/528a2ae726e9a63a49e4850078f28a14431c033f))


### Documentation

* changes "may" to preferred "might" ([efb1726](https://www.github.com/googleapis/java-common-protos/commit/efb17264f970dcaecb3e59664c99e413baa8bc8f))
* regenerate javadocs from protos ([#69](https://www.github.com/googleapis/java-common-protos/issues/69)) ([1759fe7](https://www.github.com/googleapis/java-common-protos/commit/1759fe7650869500e0d7b712fe8ef1bcc346d27a))
* update generated logging type javadoc ([#87](https://www.github.com/googleapis/java-common-protos/issues/87)) ([9f122e8](https://www.github.com/googleapis/java-common-protos/commit/9f122e82982d96c91343ee6c082f1687570fa15b))
* Update inclusive language in the documentation. Also other latest doc updates. ([#78](https://www.github.com/googleapis/java-common-protos/issues/78)) ([fda2e7b](https://www.github.com/googleapis/java-common-protos/commit/fda2e7be4961ef27fc0908f5dffd63b6248f0507))
* Updates "unit" description: changes "KBy" to "kBy" ([#99](https://www.github.com/googleapis/java-common-protos/issues/99)) ([efb1726](https://www.github.com/googleapis/java-common-protos/commit/efb17264f970dcaecb3e59664c99e413baa8bc8f))
* updates an "http" link to "https" ([efb1726](https://www.github.com/googleapis/java-common-protos/commit/efb17264f970dcaecb3e59664c99e413baa8bc8f))


### Dependencies

* update dependency com.google.guava:guava to v30.1-android ([#96](https://www.github.com/googleapis/java-common-protos/issues/96)) ([ad6beb6](https://www.github.com/googleapis/java-common-protos/commit/ad6beb636c6fbd6ede923db4b2132cc2b1c2b5b3))
* update dependency com.google.protobuf:protobuf-bom to v3.14.0 ([#86](https://www.github.com/googleapis/java-common-protos/issues/86)) ([ad85e3a](https://www.github.com/googleapis/java-common-protos/commit/ad85e3a9e0becdb0873a3aa474bb45ecbe02b7d6))
* update dependency com.google.protobuf:protobuf-bom to v3.15.0 ([#116](https://www.github.com/googleapis/java-common-protos/issues/116)) ([8e48b28](https://www.github.com/googleapis/java-common-protos/commit/8e48b28797d00b61b3ecfa2eb2a75aa4fe6d9dd9))
* update dependency com.google.protobuf:protobuf-bom to v3.15.2 ([#118](https://www.github.com/googleapis/java-common-protos/issues/118)) ([5e7415a](https://www.github.com/googleapis/java-common-protos/commit/5e7415aa6b05dac3080a29d3e9e01b949c9bc864))
* update dependency io.grpc:grpc-bom to v1.35.0 ([#93](https://www.github.com/googleapis/java-common-protos/issues/93)) ([6243d5b](https://www.github.com/googleapis/java-common-protos/commit/6243d5b733a1ec83860a5b5e4e3fc307c9ae52dd))
* update dependency io.grpc:grpc-bom to v1.36.0 ([#119](https://www.github.com/googleapis/java-common-protos/issues/119)) ([9eb9d03](https://www.github.com/googleapis/java-common-protos/commit/9eb9d03f69cdb4bf6ed8243ba253441fdd982ff1))

### [2.0.1](https://www.github.com/googleapis/java-common-protos/compare/v2.0.0...v2.0.1) (2020-11-02)


### Dependencies

* update dependency com.google.guava:guava to v30 ([#68](https://www.github.com/googleapis/java-common-protos/issues/68)) ([744f4a7](https://www.github.com/googleapis/java-common-protos/commit/744f4a72fc373440c4ac5fa5e8b85152ca8385be))
* update dependency io.grpc:grpc-bom to v1.33.1 ([#67](https://www.github.com/googleapis/java-common-protos/issues/67)) ([b729eb3](https://www.github.com/googleapis/java-common-protos/commit/b729eb3ca99aa510c3bb31fa5225a0f5d18edfd0))

## [2.0.0](https://www.github.com/googleapis/java-common-protos/compare/v1.18.1...v2.0.0) (2020-10-15)


### ⚠ BREAKING CHANGES

* `features` removed from Endpoint

### Features

* remove `features` from Endpoint. add service_root_url to Documentation add UNIMPLEMENTED, PRELAUNCH LaunchStage values add monitoried_resource_types to MetricDescriptor ([#35](https://www.github.com/googleapis/java-common-protos/issues/35)) ([cdd4e56](https://www.github.com/googleapis/java-common-protos/commit/cdd4e5633b1e4f5dc199ddc513ea7f238d2150d5))


### Dependencies

* update dependency com.google.protobuf:protobuf-bom to v3.12.4 ([#19](https://www.github.com/googleapis/java-common-protos/issues/19)) ([8d43144](https://www.github.com/googleapis/java-common-protos/commit/8d43144f2512a566005f8ae9ef0819fd9c165d39))
* update dependency com.google.protobuf:protobuf-bom to v3.13.0 ([#26](https://www.github.com/googleapis/java-common-protos/issues/26)) ([a51daab](https://www.github.com/googleapis/java-common-protos/commit/a51daab546f84d6ef3ed1d457d304f3ec986afd9))
* update dependency io.grpc:grpc-bom to v1.31.1 ([#16](https://www.github.com/googleapis/java-common-protos/issues/16)) ([a0b20f1](https://www.github.com/googleapis/java-common-protos/commit/a0b20f1d9bf787f3cc6c4634f13fcd6e895a69e1))
* update dependency io.grpc:grpc-bom to v1.32.1 ([#31](https://www.github.com/googleapis/java-common-protos/issues/31)) ([3dc5426](https://www.github.com/googleapis/java-common-protos/commit/3dc54267e1d166d28351113f4374b25eec7b5714))
* update dependency io.grpc:grpc-bom to v1.32.2 ([#56](https://www.github.com/googleapis/java-common-protos/issues/56)) ([1e62ad5](https://www.github.com/googleapis/java-common-protos/commit/1e62ad5229b0e3387d6af0512bd043c59782109f))

### [1.18.1](https://www.github.com/googleapis/java-common-protos/compare/v1.18.0...v1.18.1) (2020-08-11)


### Dependencies

* update dependency com.google.protobuf:protobuf-bom to v3.12.0 ([#8](https://www.github.com/googleapis/java-common-protos/issues/8)) ([cb0fcd9](https://www.github.com/googleapis/java-common-protos/commit/cb0fcd9f74ca51220d3b9e4b330575920732dfa1))
* update dependency com.google.protobuf:protobuf-bom to v3.12.2 ([#10](https://www.github.com/googleapis/java-common-protos/issues/10)) ([d1e68f6](https://www.github.com/googleapis/java-common-protos/commit/d1e68f6733737f31cad7855ffee10000ec37f73a))
* update dependency io.grpc:grpc-bom to v1.30.0 ([#12](https://www.github.com/googleapis/java-common-protos/issues/12)) ([67a5c0f](https://www.github.com/googleapis/java-common-protos/commit/67a5c0f695eefd0dca740544089a338cfecb700f))

## [1.18.0](https://www.github.com/googleapis/java-common-protos/compare/v1.17.0...v1.18.0) (2020-05-04)


### Features

* add DateTime/TimeOfDay protos ([#1](https://www.github.com/googleapis/java-common-protos/issues/1)) ([e33500c](https://www.github.com/googleapis/java-common-protos/commit/e33500c45789ece6f5f3b29d37a127bdc767dde0))
