# Version 0.12.0

* Only return an error if the extrinsic failed. [#156](https://github.com/paritytech/substrate-subxt/pull/156)
* Update to rc6. [#155](https://github.com/paritytech/substrate-subxt/pull/155)
* Different assert. [#153](https://github.com/paritytech/substrate-subxt/pull/153)
* Add a method to fetch an unhashed key, close #100 [#152](https://github.com/paritytech/substrate-subxt/pull/152)
* Fix port number. [#151](https://github.com/paritytech/substrate-subxt/pull/151)
* Implement the `concat` in `twox_64_concat` [#150](https://github.com/paritytech/substrate-subxt/pull/150)
* Storage map iter [#148](https://github.com/paritytech/substrate-subxt/pull/148)

# Version 0.11.0

* Fix build error, wabt 0.9.2 is yanked [#146](https://github.com/paritytech/substrate-subxt/pull/146)
* Rc5 [#143](https://github.com/paritytech/substrate-subxt/pull/143)
* Refactor: extract functions and types for creating extrinsics [#138](https://github.com/paritytech/substrate-subxt/pull/138)
* event subscription example [#140](https://github.com/paritytech/substrate-subxt/pull/140)
* Document the `Call` derive macro [#137](https://github.com/paritytech/substrate-subxt/pull/137)
* Document the #[module] macro [#135](https://github.com/paritytech/substrate-subxt/pull/135)
* Support authors api. [#134](https://github.com/paritytech/substrate-subxt/pull/134)

# Version 0.10.1 (2020-06-19)

* Release client v0.2.0 [#133](https://github.com/paritytech/substrate-subxt/pull/133)

# Version 0.10.0 (2020-06-19)

* Upgrade to substrate rc4 release [#131](https://github.com/paritytech/substrate-subxt/pull/131)
* Support unsigned extrinsics. [#130](https://github.com/paritytech/substrate-subxt/pull/130)

# Version 0.9.0 (2020-06-25)

* Events sub [#126](https://github.com/paritytech/substrate-subxt/pull/126)
* Improve error handling in proc-macros, handle DispatchError etc. [#123](https://github.com/paritytech/substrate-subxt/pull/123)
* Support embedded full/light node clients. [#91](https://github.com/paritytech/substrate-subxt/pull/91)
* Zero sized types [#121](https://github.com/paritytech/substrate-subxt/pull/121)
* Fix optional store items. [#120](https://github.com/paritytech/substrate-subxt/pull/120)
* Make signing fallable and asynchronous [#119](https://github.com/paritytech/substrate-subxt/pull/119)

# Version 0.8.0 (2020-05-26)

* Update to Substrate release candidate [#116](https://github.com/paritytech/substrate-subxt/pull/116)
* Update to alpha.8 [#114](https://github.com/paritytech/substrate-subxt/pull/114)
* Refactors the api [#113](https://github.com/paritytech/substrate-subxt/pull/113)

# Version 0.7.0 (2020-05-13)

* Split subxt [#102](https://github.com/paritytech/substrate-subxt/pull/102)
* Add support for RPC `state_getReadProof` [#106](https://github.com/paritytech/substrate-subxt/pull/106)
* Update to substrate alpha.7 release [#105](https://github.com/paritytech/substrate-subxt/pull/105)
* Double map and plain storage support, introduce macros [#93](https://github.com/paritytech/substrate-subxt/pull/93)
* Raw payload return SignedPayload struct [#92](https://github.com/paritytech/substrate-subxt/pull/92)

# Version 0.6.0 (2020-04-15)

* Raw extrinsic payloads in Client [#83](https://github.com/paritytech/substrate-subxt/pull/83)
* Custom extras [#89](https://github.com/paritytech/substrate-subxt/pull/89)
* Wrap and export BlockNumber [#87](https://github.com/paritytech/substrate-subxt/pull/87)
* All substrate dependencies upgraded to `alpha.6`

# Version 0.5.0 (2020-03-25)

* First release
* All substrate dependencies upgraded to `alpha.5`

