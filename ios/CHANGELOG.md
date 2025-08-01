# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [7.4.2](https://github.com/ionic-team/capacitor/compare/7.4.1...7.4.2) (2025-07-10)

### Bug Fixes

- **http:** Properly URL-encode key and values during `x-www-form-urlencoded` POSTs ([#8037](https://github.com/ionic-team/capacitor/issues/8037)) ([87b4641](https://github.com/ionic-team/capacitor/commit/87b4641d1fa32b78e6fc2e87ee7b2c49b625b213))

## [7.4.1](https://github.com/ionic-team/capacitor/compare/7.4.0...7.4.1) (2025-07-03)

**Note:** Version bump only for package @capacitor/ios

# [7.4.0](https://github.com/ionic-team/capacitor/compare/7.3.0...7.4.0) (2025-06-18)

**Note:** Version bump only for package @capacitor/ios

# [7.3.0](https://github.com/ionic-team/capacitor/compare/7.2.0...7.3.0) (2025-06-05)

### Bug Fixes

- Remove all plugin listeners in bridge reset ([#7962](https://github.com/ionic-team/capacitor/issues/7962)) ([06aeea9](https://github.com/ionic-team/capacitor/commit/06aeea973aa56ac2fb791f893ebd899253ee65f9))

### Features

- expose `appStartPath` on cap config server configuration ([#8019](https://github.com/ionic-team/capacitor/issues/8019)) ([a274fef](https://github.com/ionic-team/capacitor/commit/a274fef069176a8e528a22f4734d1e29a539709c))
- **ios:** Alternative debug config for SPM ([#7982](https://github.com/ionic-team/capacitor/issues/7982)) ([a054aa5](https://github.com/ionic-team/capacitor/commit/a054aa5bb4d5eabe5da5d42a380bd51b8785958c))

# [7.2.0](https://github.com/ionic-team/capacitor/compare/7.1.0...7.2.0) (2025-03-31)

### Bug Fixes

- **ios:** respect shouldEncodeUrlParams value ([#7931](https://github.com/ionic-team/capacitor/issues/7931)) ([4fb12a0](https://github.com/ionic-team/capacitor/commit/4fb12a03a92c0f38b0d48b114252342f4bdc17bf))

### Features

- **http:** Apply overrideUserAgent to requests ([#7906](https://github.com/ionic-team/capacitor/issues/7906)) ([52482c9](https://github.com/ionic-team/capacitor/commit/52482c9d3c575b737054b41f9d1730c70cc5f471))
- **ios:** Enable Fullscreen API on WebView ([#7909](https://github.com/ionic-team/capacitor/issues/7909)) ([172638e](https://github.com/ionic-team/capacitor/commit/172638ec7b6eb67bf25f8dac2818122ba31c2c91))

# [7.1.0](https://github.com/ionic-team/capacitor/compare/7.0.1...7.1.0) (2025-03-12)

### Bug Fixes

- **http:** boundary not added for Request objects ([#7897](https://github.com/ionic-team/capacitor/issues/7897)) ([bdaa6f3](https://github.com/ionic-team/capacitor/commit/bdaa6f3c38c33f3a021ac61f2de89101a5b66cff))
- **ios:** don't check isMediaExtension on range requests ([#7868](https://github.com/ionic-team/capacitor/issues/7868)) ([028caa5](https://github.com/ionic-team/capacitor/commit/028caa5378d359fb1004098aa93a24ad0f49a4ae))
- **ios:** listen for CapacitorViewDidAppear ([#7850](https://github.com/ionic-team/capacitor/issues/7850)) ([e24ffb7](https://github.com/ionic-team/capacitor/commit/e24ffb7d4de0bf3d53e92537f21c864f121c1fad))
- **ios:** Reset plugin listeners when WebView process is terminated ([#7905](https://github.com/ionic-team/capacitor/issues/7905)) ([d039157](https://github.com/ionic-team/capacitor/commit/d0391576726955b2c1b484f1ca9a03465b9ef67e))

### Features

- Add function to inject external JS into WebView before document load ([#7864](https://github.com/ionic-team/capacitor/issues/7864)) ([ec0954c](https://github.com/ionic-team/capacitor/commit/ec0954c197543e913939f3ab9c4bcb172bfa3530))

## [7.0.1](https://github.com/ionic-team/capacitor/compare/7.0.0...7.0.1) (2025-01-21)

**Note:** Version bump only for package @capacitor/ios

# [7.0.0](https://github.com/ionic-team/capacitor/compare/7.0.0-rc.1...7.0.0) (2025-01-20)

**Note:** Version bump only for package @capacitor/ios

# [7.0.0-rc.1](https://github.com/ionic-team/capacitor/compare/7.0.0-rc.0...7.0.0-rc.1) (2025-01-20)

**Note:** Version bump only for package @capacitor/ios

# [7.0.0-rc.0](https://github.com/ionic-team/capacitor/compare/7.0.0-beta.0...7.0.0-rc.0) (2024-12-20)

**Note:** Version bump only for package @capacitor/ios

# [7.0.0-beta.0](https://github.com/ionic-team/capacitor/compare/7.0.0-alpha.2...7.0.0-beta.0) (2024-12-20)

### Bug Fixes

- **ios:** Make Bridge webView first responder ([#7753](https://github.com/ionic-team/capacitor/issues/7753)) ([77e4668](https://github.com/ionic-team/capacitor/commit/77e4668fa8dbb24b4561387e101547f74e37538e))

### Features

- Add global initialFocus configuration ([#7775](https://github.com/ionic-team/capacitor/issues/7775)) ([61d0165](https://github.com/ionic-team/capacitor/commit/61d01653685d8e3594d2d8a6bd870fa9643ba95c))

# [7.0.0-alpha.2](https://github.com/ionic-team/capacitor/compare/7.0.0-alpha.1...7.0.0-alpha.2) (2024-11-19)

**Note:** Version bump only for package @capacitor/ios

# [7.0.0-alpha.1](https://github.com/ionic-team/capacitor/compare/6.1.2...7.0.0-alpha.1) (2024-10-14)

### Bug Fixes

- **ios:** fix retain cycle caused by CDVPluginManager ([#7692](https://github.com/ionic-team/capacitor/issues/7692)) ([02bdb3d](https://github.com/ionic-team/capacitor/commit/02bdb3d1d15907dcc577f16b7f2e22050e54ffef))

### Features

- **core:** expose `methodName` via `CAPPluginCall` ([#7641](https://github.com/ionic-team/capacitor/issues/7641)) ([df109aa](https://github.com/ionic-team/capacitor/commit/df109aa1cfa1ea824e22feecbd2b7183a57fc693))
- **ios:** JSValueEncoder/Decoder feature parity with JSONEncoder/Decoder ([#7647](https://github.com/ionic-team/capacitor/issues/7647)) ([410249b](https://github.com/ionic-team/capacitor/commit/410249b6c626e67235f25b466ed4969d52148bd1)), closes [#7576](https://github.com/ionic-team/capacitor/issues/7576)

## [6.1.2](https://github.com/ionic-team/capacitor/compare/6.1.1...6.1.2) (2024-08-07)

### Bug Fixes

- **http:** pass original url as query param on the proxy url ([#7527](https://github.com/ionic-team/capacitor/issues/7527)) ([1da06e6](https://github.com/ionic-team/capacitor/commit/1da06e66cb9cfbf5a5cc48ba6c23cdbe18bc8fc0))

## [6.1.1](https://github.com/ionic-team/capacitor/compare/6.1.0...6.1.1) (2024-07-17)

### Bug Fixes

- **http:** handle UInt8Array on body ([#7546](https://github.com/ionic-team/capacitor/issues/7546)) ([cfb9ce1](https://github.com/ionic-team/capacitor/commit/cfb9ce175615f69fe86b61af6d51ec2044d147cd))
- **ios:** make removeAllListeners accessible from javascript ([#7566](https://github.com/ionic-team/capacitor/issues/7566)) ([388a822](https://github.com/ionic-team/capacitor/commit/388a8223c60e8eac8437ca4cb26a93ab359f53ad))

# [6.1.0](https://github.com/ionic-team/capacitor/compare/6.0.0...6.1.0) (2024-06-11)

### Bug Fixes

- **http:** don't override readyState for non POST requests ([#7488](https://github.com/ionic-team/capacitor/issues/7488)) ([30c13a8](https://github.com/ionic-team/capacitor/commit/30c13a865e7710e6dc5f0ee014e951d52d030795))
- **ios:** check if urlSchemeTask is stopped before calling its methods ([#7482](https://github.com/ionic-team/capacitor/issues/7482)) ([b32b5b1](https://github.com/ionic-team/capacitor/commit/b32b5b17ed14bd43c846b3fcb930bfd88e245e40))

### Features

- **ios:** CAPPluginMethod selector-based initializer ([#7412](https://github.com/ionic-team/capacitor/issues/7412)) ([44c5b55](https://github.com/ionic-team/capacitor/commit/44c5b55e36b85471a85ee5a1af47bdb1a5d83a8b))

# [6.0.0](https://github.com/ionic-team/capacitor/compare/6.0.0-rc.2...6.0.0) (2024-04-15)

### Bug Fixes

- **http:** Add URLSearchParams support ([#7374](https://github.com/ionic-team/capacitor/issues/7374)) ([9367ecc](https://github.com/ionic-team/capacitor/commit/9367ecc56a0c78249dccdf95dca5006422144289))
- **http:** prevent POST request from being proxied ([#7395](https://github.com/ionic-team/capacitor/issues/7395)) ([7b8c352](https://github.com/ionic-team/capacitor/commit/7b8c3523decd5610dcf09e926640bf35b382d61d))

# [6.0.0-rc.2](https://github.com/ionic-team/capacitor/compare/6.0.0-rc.1...6.0.0-rc.2) (2024-03-25)

### Bug Fixes

- **http:** change proxy url generation ([#7354](https://github.com/ionic-team/capacitor/issues/7354)) ([318c316](https://github.com/ionic-team/capacitor/commit/318c316847c5b059fb88b46d4acd31e1ced477e5))
- inject cordova files if a cordova plugin is present ([#7363](https://github.com/ionic-team/capacitor/issues/7363)) ([ce9d505](https://github.com/ionic-team/capacitor/commit/ce9d50585b1cab183245197878bf625cf0289275))
- vue 3 log warning causes error on iOS ([#6993](https://github.com/ionic-team/capacitor/issues/6993)) ([87271e2](https://github.com/ionic-team/capacitor/commit/87271e2671013ad35d13b22f2e96d4fe8f4eeaf0))

# [6.0.0-rc.1](https://github.com/ionic-team/capacitor/compare/6.0.0-rc.0...6.0.0-rc.1) (2024-03-15)

### Bug Fixes

- **core:** make 'content-type' header count for XMLHttpRequest patch ([#7161](https://github.com/ionic-team/capacitor/issues/7161)) ([26d7f68](https://github.com/ionic-team/capacitor/commit/26d7f688284914c6ef795564ba424119efc32a1c))
- **http:** handle proxy urls with port ([#7273](https://github.com/ionic-team/capacitor/issues/7273)) ([514409a](https://github.com/ionic-team/capacitor/commit/514409aeb93ad65be105bbe2da8d2cd86ff159b0))
- **http:** keep original URL properties on proxy ([#7329](https://github.com/ionic-team/capacitor/issues/7329)) ([cbb6407](https://github.com/ionic-team/capacitor/commit/cbb6407225b42a0d9db4f335a9766f119501021d))
- **http:** Make proxy work with Request objects ([#7348](https://github.com/ionic-team/capacitor/issues/7348)) ([7e68725](https://github.com/ionic-team/capacitor/commit/7e6872573df03ab5cdc10a1a27db3e9fe81a141d))
- **http:** route get requests through custom handler ([#6818](https://github.com/ionic-team/capacitor/issues/6818)) ([b853d06](https://github.com/ionic-team/capacitor/commit/b853d065055b5a819949551be58b62d40b52e37c))
- **http:** set port for proxy url ([#7341](https://github.com/ionic-team/capacitor/issues/7341)) ([a3059dc](https://github.com/ionic-team/capacitor/commit/a3059dca4a7746d9fb7102a7d41f4da80e2f48b4))
- **ios:** Moves `updateBinaryVersion` call to the end of `loadView`. ([#7226](https://github.com/ionic-team/capacitor/issues/7226)) ([7724760](https://github.com/ionic-team/capacitor/commit/77247602ac150797d2375118f702cf9ba39ea957))
- **ios:** overwrite CORS headers on livereload ([#7339](https://github.com/ionic-team/capacitor/issues/7339)) ([0c8d69b](https://github.com/ionic-team/capacitor/commit/0c8d69b7f9c163730e7d74bb0147b61742c61676))

### Features

- **webview:** add setServerAssetPath method ([881235b](https://github.com/ionic-team/capacitor/commit/881235b14de23ef988746bfb89a5a0fc3c8d8466))

# [6.0.0-rc.0](https://github.com/ionic-team/capacitor/compare/6.0.0-beta.2...6.0.0-rc.0) (2024-01-23)

### Bug Fixes

- remove duplicates from auto registration array using set ([#7192](https://github.com/ionic-team/capacitor/issues/7192)) ([c4984ae](https://github.com/ionic-team/capacitor/commit/c4984ae4433602dbe028f72736cb6e56e8f92bf9))
- stop crashing from `objc_getClassList` ([#7187](https://github.com/ionic-team/capacitor/issues/7187)) ([e148db7](https://github.com/ionic-team/capacitor/commit/e148db7758e4186ad45fd74185a10fb757ff9b29))

### Features

- **ios:** Replace usage of UserDefaults with KeyValueStore. ([#7191](https://github.com/ionic-team/capacitor/issues/7191)) ([cd58ba2](https://github.com/ionic-team/capacitor/commit/cd58ba2a654f40bf72616f430d7b9604b283e23d))

# [6.0.0-beta.2](https://github.com/ionic-team/capacitor/compare/6.0.0-beta.1...6.0.0-beta.2) (2023-12-14)

**Note:** Version bump only for package @capacitor/ios

# [6.0.0-beta.1](https://github.com/ionic-team/capacitor/compare/6.0.0-beta.0...6.0.0-beta.1) (2023-12-14)

### Bug Fixes

- **ios:** Add Codable folder to podspec source_files ([#7131](https://github.com/ionic-team/capacitor/issues/7131)) ([04d1d55](https://github.com/ionic-team/capacitor/commit/04d1d557b51fcac31281a3f547300f06c6dacfb2))

# [6.0.0-beta.0](https://github.com/ionic-team/capacitor/compare/6.0.0-alpha.2...6.0.0-beta.0) (2023-12-13)

### Bug Fixes

- **http:** parse readablestream data on fetch request objects ([#6919](https://github.com/ionic-team/capacitor/issues/6919)) ([80ec3b7](https://github.com/ionic-team/capacitor/commit/80ec3b73db18b7b6841bf90ed50a67389946ab87))
- **ios:** add some new cordova-ios classes used by Cordova plugins ([#7096](https://github.com/ionic-team/capacitor/issues/7096)) ([3db9051](https://github.com/ionic-team/capacitor/commit/3db9051eb015cf5f402f81b4cbaa7b27a5c9477a))

### Features

- **ios:** Add Codable support for CAPPluginCall and JSValueContainer ([#7119](https://github.com/ionic-team/capacitor/issues/7119)) ([af417e0](https://github.com/ionic-team/capacitor/commit/af417e0cbbb1a3a7b3b62756eebb8d1dc0952cc4))

# [6.0.0-alpha.2](https://github.com/ionic-team/capacitor/compare/6.0.0-alpha.1...6.0.0-alpha.2) (2023-11-15)

### Bug Fixes

- **ios:** Remove CocoaPods Xcode 15 workaround that causes issues ([#7059](https://github.com/ionic-team/capacitor/issues/7059)) ([043a8db](https://github.com/ionic-team/capacitor/commit/043a8dba4059e33c7445696c186110bef1130e16))

# [6.0.0-alpha.1](https://github.com/ionic-team/capacitor/compare/5.2.3...6.0.0-alpha.1) (2023-11-08)

### Bug Fixes

- **android:** make local urls use unpatched fetch ([#6953](https://github.com/ionic-team/capacitor/issues/6953)) ([e50e56c](https://github.com/ionic-team/capacitor/commit/e50e56c5231f230497d1bd420e02e2e065c38f86))
- **http:** add support for Request objects in fetch ([24b3cc1](https://github.com/ionic-team/capacitor/commit/24b3cc113e3d8aae5d85dbf2d25bec0c35136477))
- **http:** inherit object properties on window.XMLHttpRequest ([91c11d0](https://github.com/ionic-team/capacitor/commit/91c11d06f773c45a10f6f2d52f672ae6f189b162))

### Features

- Add XCFrameworks ([#7020](https://github.com/ionic-team/capacitor/issues/7020)) ([5306095](https://github.com/ionic-team/capacitor/commit/53060955dc83cdbfda66bed60c2efcba395a9ca8))
- **ios:** Makes CapacitorBridge, WebViewAssetHandler, and WebViewDelegationHandler open classes, along with several of their methods ([#7009](https://github.com/ionic-team/capacitor/issues/7009)) ([40d62cb](https://github.com/ionic-team/capacitor/commit/40d62cbce950c2f3972764fe134cc37f2343f33d))
- modify package.swift on update and sync ([#7042](https://github.com/ionic-team/capacitor/issues/7042)) ([24573fb](https://github.com/ionic-team/capacitor/commit/24573fb864c43551e2ce42721b45ff901155627d))

# [5.6.0](https://github.com/ionic-team/capacitor/compare/5.5.1...5.6.0) (2023-12-14)

### Bug Fixes

- **ios:** add some new cordova-ios classes used by Cordova plugins ([#7115](https://github.com/ionic-team/capacitor/issues/7115)) ([5fb902b](https://github.com/ionic-team/capacitor/commit/5fb902b232d9afded2edc865c8d3c0c0e7efe5e7))

## [5.5.1](https://github.com/ionic-team/capacitor/compare/5.5.0...5.5.1) (2023-10-25)

### Bug Fixes

- **ios:** CAPWebView config update ([#7004](https://github.com/ionic-team/capacitor/issues/7004)) ([f3e8be0](https://github.com/ionic-team/capacitor/commit/f3e8be0453c31f74a2fdf4c9a6d8d7967a6b5c20))

# [5.5.0](https://github.com/ionic-team/capacitor/compare/5.4.2...5.5.0) (2023-10-11)

**Note:** Version bump only for package @capacitor/ios

## [5.4.2](https://github.com/ionic-team/capacitor/compare/5.4.1...5.4.2) (2023-10-04)

### Bug Fixes

- **android:** make local urls use unpatched fetch ([#6954](https://github.com/ionic-team/capacitor/issues/6954)) ([56fb853](https://github.com/ionic-team/capacitor/commit/56fb8536af53f4f4ee49b9394fd966ad514b9458))

## [5.4.1](https://github.com/ionic-team/capacitor/compare/5.4.0...5.4.1) (2023-09-21)

### Bug Fixes

- **http:** parse readablestream data on fetch request objects ([3fe0642](https://github.com/ionic-team/capacitor/commit/3fe06426bd20713e2322780b70bc5d97ad371fae))
- **http:** return xhr response headers case insensitive ([687b6b1](https://github.com/ionic-team/capacitor/commit/687b6b1780506c17fb73ed1d9cbf50c1d1e40ef1))
- **ios:** Add workaround for CocoaPods problem on Xcode 15 ([#6921](https://github.com/ionic-team/capacitor/issues/6921)) ([1ffa244](https://github.com/ionic-team/capacitor/commit/1ffa2441fc8a04e4bf1712d0afb868a83e7f1951))

# [5.4.0](https://github.com/ionic-team/capacitor/compare/5.3.0...5.4.0) (2023-09-14)

### Bug Fixes

- **http:** add support for defining xhr and angular http response types ([09bd040](https://github.com/ionic-team/capacitor/commit/09bd040dfe4b8808d7499b6ee592005420406cac))
- **http:** add support for Request objects in fetch ([2fe4535](https://github.com/ionic-team/capacitor/commit/2fe4535e781b1a5cfa0f3359c1afa5c360073b6a))
- **http:** inherit object properties on window.XMLHttpRequest ([5cd3b2f](https://github.com/ionic-team/capacitor/commit/5cd3b2fa6d6936864e1aab2e98963df2d4da3b95))

# [5.3.0](https://github.com/ionic-team/capacitor/compare/5.2.3...5.3.0) (2023-08-23)

**Note:** Version bump only for package @capacitor/ios

## [5.2.3](https://github.com/ionic-team/capacitor/compare/5.2.2...5.2.3) (2023-08-10)

### Bug Fixes

- **cli:** signing type option issue ([#6716](https://github.com/ionic-team/capacitor/issues/6716)) ([ee0f745](https://github.com/ionic-team/capacitor/commit/ee0f7457e458ca4bb4eb74f67552ac2ace76016b))
- **cookies:** hide httpOnly cookies from client ([0cc927e](https://github.com/ionic-team/capacitor/commit/0cc927ef5f0f7076a6d486d666d78483f1d71c54))
- **http:** return valid response for relative url xhr requests ([bde6569](https://github.com/ionic-team/capacitor/commit/bde65696218f97a8328041f137457f46e5eb766a))

## [5.2.2](https://github.com/ionic-team/capacitor/compare/5.2.1...5.2.2) (2023-07-19)

### Bug Fixes

- add http method to prototype.open ([#6740](https://github.com/ionic-team/capacitor/issues/6740)) ([1fd2d87](https://github.com/ionic-team/capacitor/commit/1fd2d8762ff2341a8fe20eec9e774c6a29576e88))

## [5.2.1](https://github.com/ionic-team/capacitor/compare/5.2.0...5.2.1) (2023-07-13)

### Bug Fixes

- allow single parameter on setRequestBody ([#6728](https://github.com/ionic-team/capacitor/issues/6728)) ([5343bdb](https://github.com/ionic-team/capacitor/commit/5343bdb60d26849cd8f9c8ff28ba7d9ddbd05b26))

# [5.2.0](https://github.com/ionic-team/capacitor/compare/5.1.1...5.2.0) (2023-07-12)

### Bug Fixes

- **cookies:** sanitize url before retrieving/setting cookies ([ca40634](https://github.com/ionic-team/capacitor/commit/ca4063471f215d3f7525e51592d9c72138a52855))
- **http:** fire events in correct order when using xhr ([5ed3617](https://github.com/ionic-team/capacitor/commit/5ed361787596bb5949f6ae5e366495f296352bf3))

### Features

- **http:** support for FormData requests ([#6708](https://github.com/ionic-team/capacitor/issues/6708)) ([849c564](https://github.com/ionic-team/capacitor/commit/849c56458205bea3b078b1ee19807d7fd84c47b1))

## [5.1.1](https://github.com/ionic-team/capacitor/compare/5.1.0...5.1.1) (2023-07-05)

### Bug Fixes

- **ios:** Revert server url addition for CAPWebView. ([#6705](https://github.com/ionic-team/capacitor/issues/6705)) ([1b8352d](https://github.com/ionic-team/capacitor/commit/1b8352dc5124dc3f57d7881d619537cbf8c3674b))

# [5.1.0](https://github.com/ionic-team/capacitor/compare/5.0.5...5.1.0) (2023-06-29)

### Bug Fixes

- **ios:** Return proper MIME Type for local WASM files ([#6675](https://github.com/ionic-team/capacitor/issues/6675)) ([d7856de](https://github.com/ionic-team/capacitor/commit/d7856de62a4c058ac474ae91a5fd221dabf99c0a))
- **ios:** set cors headers in asset handler for live reload ([e5a1c81](https://github.com/ionic-team/capacitor/commit/e5a1c81fe81904dfd7e3f5100a04088173effc1c))

## [5.0.5](https://github.com/ionic-team/capacitor/compare/5.0.4...5.0.5) (2023-06-09)

### Bug Fixes

- **http:** don't throw errors when content-type is null on response ([#6627](https://github.com/ionic-team/capacitor/issues/6627)) ([538821f](https://github.com/ionic-team/capacitor/commit/538821f267aa3b79548fed6aaea8880ff949ffdd))

## [5.0.4](https://github.com/ionic-team/capacitor/compare/5.0.3...5.0.4) (2023-05-23)

**Note:** Version bump only for package @capacitor/ios

## [5.0.3](https://github.com/ionic-team/capacitor/compare/5.0.2...5.0.3) (2023-05-10)

**Note:** Version bump only for package @capacitor/ios

## [5.0.2](https://github.com/ionic-team/capacitor/compare/5.0.1...5.0.2) (2023-05-09)

**Note:** Version bump only for package @capacitor/ios

## [5.0.1](https://github.com/ionic-team/capacitor/compare/5.0.0...5.0.1) (2023-05-05)

**Note:** Version bump only for package @capacitor/ios

# [5.0.0](https://github.com/ionic-team/capacitor/compare/5.0.0-rc.3...5.0.0) (2023-05-03)

**Note:** Version bump only for package @capacitor/ios

# [5.0.0-rc.3](https://github.com/ionic-team/capacitor/compare/5.0.0-rc.2...5.0.0-rc.3) (2023-05-03)

**Note:** Version bump only for package @capacitor/ios

# [5.0.0-rc.2](https://github.com/ionic-team/capacitor/compare/5.0.0-rc.1...5.0.0-rc.2) (2023-05-03)

**Note:** Version bump only for package @capacitor/ios

# [5.0.0-rc.1](https://github.com/ionic-team/capacitor/compare/5.0.0-rc.0...5.0.0-rc.1) (2023-05-02)

**Note:** Version bump only for package @capacitor/ios

# [5.0.0-rc.0](https://github.com/ionic-team/capacitor/compare/5.0.0-beta.3...5.0.0-rc.0) (2023-05-01)

**Note:** Version bump only for package @capacitor/ios

# [5.0.0-beta.3](https://github.com/ionic-team/capacitor/compare/5.0.0-beta.2...5.0.0-beta.3) (2023-04-21)

**Note:** Version bump only for package @capacitor/ios

# [5.0.0-beta.2](https://github.com/ionic-team/capacitor/compare/5.0.0-beta.1...5.0.0-beta.2) (2023-04-13)

### Bug Fixes

- **ios/android:** copy url from nativeResponse to response ([#6482](https://github.com/ionic-team/capacitor/issues/6482)) ([828fb71](https://github.com/ionic-team/capacitor/commit/828fb71ebb52c0655d5879ad0edaac7368ab2b96))

### Features

- **ios:** add webContentsDebuggingEnabled configuration ([#6495](https://github.com/ionic-team/capacitor/issues/6495)) ([c691e4a](https://github.com/ionic-team/capacitor/commit/c691e4aecbfb7a45ce0465d1fe9020ab715815d3))

# [5.0.0-beta.1](https://github.com/ionic-team/capacitor/compare/5.0.0-beta.0...5.0.0-beta.1) (2023-04-03)

**Note:** Version bump only for package @capacitor/ios

# [5.0.0-beta.0](https://github.com/ionic-team/capacitor/compare/5.0.0-alpha.1...5.0.0-beta.0) (2023-03-31)

### Bug Fixes

- 204 http response ([#6266](https://github.com/ionic-team/capacitor/issues/6266)) ([771f6ce](https://github.com/ionic-team/capacitor/commit/771f6ce1f35159848db218a42dc4f56b5106f750))
- **ios:** Event listeners were unexpectedly nil ([#6445](https://github.com/ionic-team/capacitor/issues/6445)) ([209d4ed](https://github.com/ionic-team/capacitor/commit/209d4edace610b00e689440a5c08e72f5da60cc2))

### Features

- retain multiple calls per event until consumed ([#6419](https://github.com/ionic-team/capacitor/issues/6419)) ([5aba2cb](https://github.com/ionic-team/capacitor/commit/5aba2cbe29bdbab2a7af861c65d8323acf9c54a6))

# [5.0.0-alpha.1](https://github.com/ionic-team/capacitor/compare/4.7.0...5.0.0-alpha.1) (2023-03-16)

### Bug Fixes

- **iOS:** Separate cookies by `; ` rather than `;` when accessing through `document.cookie` ([#6313](https://github.com/ionic-team/capacitor/issues/6313)) ([beade60](https://github.com/ionic-team/capacitor/commit/beade6020e25dc405e796e1b06bf6dd90b217693))

# [4.7.0](https://github.com/ionic-team/capacitor/compare/4.6.3...4.7.0) (2023-02-22)

### Bug Fixes

- handle fetch headers that are Headers objects ([#6320](https://github.com/ionic-team/capacitor/issues/6320)) ([cb00e49](https://github.com/ionic-team/capacitor/commit/cb00e4952acca8e877555f30b2190f6685d25934))
- **ios:** Avoid double encoding on http urls ([#6288](https://github.com/ionic-team/capacitor/issues/6288)) ([4768085](https://github.com/ionic-team/capacitor/commit/4768085414768bb2c013afcc6c645664893cd297))
- **ios:** Correctly Attach Headers to Request ([#6303](https://github.com/ionic-team/capacitor/issues/6303)) ([a3f875c](https://github.com/ionic-team/capacitor/commit/a3f875cf42e111fde07d6e87643264b19ed77573))

## [4.6.3](https://github.com/ionic-team/capacitor/compare/4.6.2...4.6.3) (2023-02-03)

### Bug Fixes

- **ios:** crash when http headers contain numbers ([#6251](https://github.com/ionic-team/capacitor/issues/6251)) ([028c556](https://github.com/ionic-team/capacitor/commit/028c556a50b41ee99fe8f4f1aa2f42d3fd57f92d))

## [4.6.2](https://github.com/ionic-team/capacitor/compare/4.6.1...4.6.2) (2023-01-17)

### Bug Fixes

- **ios:** CapacitorHttp cannot use delete method ([#6220](https://github.com/ionic-team/capacitor/issues/6220)) ([4d238a9](https://github.com/ionic-team/capacitor/commit/4d238a9e0dcf1e3e8c105c3aa4c7361abf16398e))
- **ios:** encode whitespace in http plugin urls ([#6169](https://github.com/ionic-team/capacitor/issues/6169)) ([dccb0a9](https://github.com/ionic-team/capacitor/commit/dccb0a99850c7c878906156a509ecd675836ef1a))
- **ios/android:** better http error handling ([#6208](https://github.com/ionic-team/capacitor/issues/6208)) ([7d4d70a](https://github.com/ionic-team/capacitor/commit/7d4d70a0500b7996c710c0762907f44bdf27c92b))

## [4.6.1](https://github.com/ionic-team/capacitor/compare/4.6.0...4.6.1) (2022-12-05)

**Note:** Version bump only for package @capacitor/ios

# [4.6.0](https://github.com/ionic-team/capacitor/compare/4.5.0...4.6.0) (2022-12-01)

### Bug Fixes

- **cookies:** Use Set-Cookie headers to persist cookies ([57f8b39](https://github.com/ionic-team/capacitor/commit/57f8b39d7f4c5ee0e5e5cb316913e9450a81d22b))

### Features

- **ios:** Plugin Registration and Plugin Instance Support ([#6072](https://github.com/ionic-team/capacitor/issues/6072)) ([9f1d863](https://github.com/ionic-team/capacitor/commit/9f1d863c1222096334a0dd05f39ce7f984a2763a))

# [4.5.0](https://github.com/ionic-team/capacitor/compare/4.4.0...4.5.0) (2022-11-16)

### Bug Fixes

- **cli/ios:** Read handleApplicationNotifications configuration option ([#6030](https://github.com/ionic-team/capacitor/issues/6030)) ([99ccf18](https://github.com/ionic-team/capacitor/commit/99ccf181f6ee8a00ed97bdbf9076e2b2ea27cd57))

### Features

- **cookies:** add get cookies plugin method ([ba1e770](https://github.com/ionic-team/capacitor/commit/ba1e7702a3338714aee24388c0afea39706c9341))

# [4.4.0](https://github.com/ionic-team/capacitor/compare/4.3.0...4.4.0) (2022-10-21)

### Bug Fixes

- **cookies:** make document.cookie setter synchronous ([2272abf](https://github.com/ionic-team/capacitor/commit/2272abf3d3d9dc82d9ca0d03b17e2b78f11f61fc))
- **http:** fix local http requests on native platforms ([c4e040a](https://github.com/ionic-team/capacitor/commit/c4e040a6f8c6b54bac6ae320e5f0f008604fe50f))

# [4.3.0](https://github.com/ionic-team/capacitor/compare/4.2.0...4.3.0) (2022-09-21)

### Bug Fixes

- **core:** Exception object was not set on Cap ([#5917](https://github.com/ionic-team/capacitor/issues/5917)) ([9ca27a4](https://github.com/ionic-team/capacitor/commit/9ca27a4f8441b368f8bf9d97dda57b1a55ac0e4e))

### Features

- Capacitor Cookies & Capacitor Http core plugins ([d4047cf](https://github.com/ionic-team/capacitor/commit/d4047cfa947676777f400389a8d65defae140b45))

# [4.2.0](https://github.com/ionic-team/capacitor/compare/4.1.0...4.2.0) (2022-09-08)

**Note:** Version bump only for package @capacitor/ios

# [4.1.0](https://github.com/ionic-team/capacitor/compare/4.0.1...4.1.0) (2022-08-18)

### Bug Fixes

- **ios:** Prevent Xcode 14 warning on CAPWebView ([#5821](https://github.com/ionic-team/capacitor/issues/5821)) ([66954ef](https://github.com/ionic-team/capacitor/commit/66954ef6bc93f2038d85a386ef2f8b582af11bc3))
- **ios:** return proper mimeType on M1 x86_64 simulators ([#5853](https://github.com/ionic-team/capacitor/issues/5853)) ([325b6fe](https://github.com/ionic-team/capacitor/commit/325b6fe83939efaaef44c7e8624e33de742a57e2)), closes [#5793](https://github.com/ionic-team/capacitor/issues/5793)

### Features

- **ios:** Add `setServerBasePath(_:)` to CAPBridgeProtocol ([#5860](https://github.com/ionic-team/capacitor/issues/5860)) ([76f28e7](https://github.com/ionic-team/capacitor/commit/76f28e70a5c0a03e4c6b9a93a0c068666a2c38ff))

## [4.0.1](https://github.com/ionic-team/capacitor/compare/4.0.0...4.0.1) (2022-07-28)

### Bug Fixes

- **ios:** publish Podfile script ([#5799](https://github.com/ionic-team/capacitor/issues/5799)) ([604f03a](https://github.com/ionic-team/capacitor/commit/604f03a29bc500d2841987d0a0f1b20d34fba7d6))

# [4.0.0](https://github.com/ionic-team/capacitor/compare/4.0.0-beta.2...4.0.0) (2022-07-27)

### Bug Fixes

- **ios:** error data is optional ([#5782](https://github.com/ionic-team/capacitor/issues/5782)) ([da48d79](https://github.com/ionic-team/capacitor/commit/da48d798c3463de9de188ae6a6475fd6afba6091))

### Features

- **android:** Add Optional Data Param for Error Object ([#5719](https://github.com/ionic-team/capacitor/issues/5719)) ([174172b](https://github.com/ionic-team/capacitor/commit/174172b6c64dc9117c48ed0e20c25e0b6c2fb625))
- **android:** Use addWebMessageListener where available ([#5427](https://github.com/ionic-team/capacitor/issues/5427)) ([c2dfe80](https://github.com/ionic-team/capacitor/commit/c2dfe808446717412b35e82713d123b7a052f264))
- **ios:** Add overrideable router var for CAPWebView. ([#5743](https://github.com/ionic-team/capacitor/issues/5743)) ([c1de1c0](https://github.com/ionic-team/capacitor/commit/c1de1c0138aad188a760118e35983d10d257f8e7))
- **iOS:** post install script for deployment target ([#5783](https://github.com/ionic-team/capacitor/issues/5783)) ([f5afa94](https://github.com/ionic-team/capacitor/commit/f5afa94b3b9c246d87b2af03359840f503bace90))
- Add option for custom error page ([#5723](https://github.com/ionic-team/capacitor/issues/5723)) ([e8bdef3](https://github.com/ionic-team/capacitor/commit/e8bdef3b4634e4ad45fa8fc34c7c0ab8dfa383f3))

# [4.0.0-beta.2](https://github.com/ionic-team/capacitor/compare/4.0.0-beta.1...4.0.0-beta.2) (2022-07-08)

### Bug Fixes

- **ios:** Add check for both serverURL and localURL in navigation ([#5736](https://github.com/ionic-team/capacitor/issues/5736)) ([8e824f3](https://github.com/ionic-team/capacitor/commit/8e824f33ad4df898fb8c0936a8f5e9041832a5c5))
- **ios:** properly deliver retained events after listener re-add [#5732](https://github.com/ionic-team/capacitor/issues/5732) ([c5d6328](https://github.com/ionic-team/capacitor/commit/c5d632831924a1bcc868bc46b42f7ff619408752))

### Features

- **ios:** Add `setServerBasePath(path:)` to CAPWebView ([#5742](https://github.com/ionic-team/capacitor/issues/5742)) ([1afbf8a](https://github.com/ionic-team/capacitor/commit/1afbf8a9dd0b8f7b1ac439d24e5d8ba26f786318))
- Add CapWebView ([#5715](https://github.com/ionic-team/capacitor/issues/5715)) ([143d266](https://github.com/ionic-team/capacitor/commit/143d266ef0a818bac59dbbdaeda3b5c382ebfa1d))

# [4.0.0-beta.1](https://github.com/ionic-team/capacitor/compare/4.0.0-beta.0...4.0.0-beta.1) (2022-06-27)

### Bug Fixes

- **ios:** Remove Cordova as an embedded framework ([#5709](https://github.com/ionic-team/capacitor/issues/5709)) ([bbf6d24](https://github.com/ionic-team/capacitor/commit/bbf6d248bf9217a5c5c6c15c7bcfeda209aba5b1))

### Features

- **ios:** Allow to configure popover size ([#5717](https://github.com/ionic-team/capacitor/issues/5717)) ([ca1a125](https://github.com/ionic-team/capacitor/commit/ca1a125e5ab05d6066dd303bc75e99dfe21f210a))

# [4.0.0-beta.0](https://github.com/ionic-team/capacitor/compare/3.6.0...4.0.0-beta.0) (2022-06-17)

### Bug Fixes

- **ios:** make removeAllListeners return a promise ([#5526](https://github.com/ionic-team/capacitor/issues/5526)) ([815f71b](https://github.com/ionic-team/capacitor/commit/815f71b6b62f6c4d5f66e6a36c190bb00a96fdcc))

### Features

- **ios:** add getConfig to CAPPlugin ([#5495](https://github.com/ionic-team/capacitor/issues/5495)) ([224a9d0](https://github.com/ionic-team/capacitor/commit/224a9d075629d9c9da9ddc658eb282617fc46d09))
- **ios:** Add preferredContentMode configuration option ([#5583](https://github.com/ionic-team/capacitor/issues/5583)) ([5b6dfa3](https://github.com/ionic-team/capacitor/commit/5b6dfa3fe29c85632546b299f03cc04a77cf7475))
- **ios:** Support of range requests on WebViewAssetHandler ([#5659](https://github.com/ionic-team/capacitor/issues/5659)) ([348c08d](https://github.com/ionic-team/capacitor/commit/348c08d511e9d57a1b2ecedc3290c65fa9ba3924))

# [3.6.0](https://github.com/ionic-team/capacitor/compare/3.5.1...3.6.0) (2022-06-17)

### Bug Fixes

- **ios:** Use `URL(fileURLWithPath:)` instead of `URL(string:)` ([#5603](https://github.com/ionic-team/capacitor/issues/5603)) ([5fac1b2](https://github.com/ionic-team/capacitor/commit/5fac1b2da5aa5882087716cb2aa862d89173f4a1))

### Features

- **iOS, Android:** add AppUUID Lib for plugins ([#5690](https://github.com/ionic-team/capacitor/issues/5690)) ([05e76cf](https://github.com/ionic-team/capacitor/commit/05e76cf526a44e07fa75f9482fa2223a13918638))

# [4.0.0-alpha.2](https://github.com/ionic-team/capacitor/compare/3.4.1...4.0.0-alpha.2) (2022-05-12)

### Bug Fixes

- **ios:** make removeAllListeners return a promise ([#5526](https://github.com/ionic-team/capacitor/issues/5526)) ([815f71b](https://github.com/ionic-team/capacitor/commit/815f71b6b62f6c4d5f66e6a36c190bb00a96fdcc))

### Features

- **ios:** add getConfig to CAPPlugin ([#5495](https://github.com/ionic-team/capacitor/issues/5495)) ([224a9d0](https://github.com/ionic-team/capacitor/commit/224a9d075629d9c9da9ddc658eb282617fc46d09))
- **ios:** Add preferredContentMode configuration option ([#5583](https://github.com/ionic-team/capacitor/issues/5583)) ([5b6dfa3](https://github.com/ionic-team/capacitor/commit/5b6dfa3fe29c85632546b299f03cc04a77cf7475))

## [3.5.1](https://github.com/ionic-team/capacitor/compare/3.5.0...3.5.1) (2022-05-04)

**Note:** Version bump only for package @capacitor/ios

# [3.5.0](https://github.com/ionic-team/capacitor/compare/3.4.3...3.5.0) (2022-04-22)

### Features

- **ios:** Add overrideable routing for CAPBridgeViewController subclasses ([#5546](https://github.com/ionic-team/capacitor/issues/5546)) ([8875d5e](https://github.com/ionic-team/capacitor/commit/8875d5e2721e8a8ee763ce70cb672db383f36efa))

# [4.0.0-alpha.1](https://github.com/ionic-team/capacitor/compare/3.4.1...4.0.0-alpha.1) (2022-03-25)

### Features

- **ios:** add getConfig to CAPPlugin ([#5495](https://github.com/ionic-team/capacitor/issues/5495)) ([224a9d0](https://github.com/ionic-team/capacitor/commit/224a9d075629d9c9da9ddc658eb282617fc46d09))

## [3.4.3](https://github.com/ionic-team/capacitor/compare/3.4.2...3.4.3) (2022-03-04)

**Note:** Version bump only for package @capacitor/ios

## [3.4.2](https://github.com/ionic-team/capacitor/compare/3.4.1...3.4.2) (2022-03-03)

**Note:** Version bump only for package @capacitor/ios

## [3.4.1](https://github.com/ionic-team/capacitor/compare/3.4.0...3.4.1) (2022-02-09)

### Bug Fixes

- **ios:** Reload webView on webViewWebContentProcessDidTerminate ([#5391](https://github.com/ionic-team/capacitor/issues/5391)) ([beebff4](https://github.com/ionic-team/capacitor/commit/beebff4550575c28c233937a11a8eacf5a76411c))

# [3.4.0](https://github.com/ionic-team/capacitor/compare/3.3.4...3.4.0) (2022-01-19)

### Features

- **ios:** Add new iOS 15 Motion permission delegate ([#5317](https://github.com/ionic-team/capacitor/issues/5317)) ([c05a3cb](https://github.com/ionic-team/capacitor/commit/c05a3cbbf02217e3972d5e067970cae18bff3faa))
- **ios:** Add new iOS15 media capture permission delegate ([#5196](https://github.com/ionic-team/capacitor/issues/5196)) ([d8b54ac](https://github.com/ionic-team/capacitor/commit/d8b54ac23414bfe56e50e1254066630a6f87eb0e))

## [3.3.4](https://github.com/ionic-team/capacitor/compare/3.3.3...3.3.4) (2022-01-05)

**Note:** Version bump only for package @capacitor/ios

## [3.3.3](https://github.com/ionic-team/capacitor/compare/3.3.2...3.3.3) (2021-12-08)

### Bug Fixes

- **ios:** Present js alert on top of the presented VC ([#5282](https://github.com/ionic-team/capacitor/issues/5282)) ([a53d236](https://github.com/ionic-team/capacitor/commit/a53d236452e99d1e6151e19e313b3d1545957419))

## [3.3.2](https://github.com/ionic-team/capacitor/compare/3.3.1...3.3.2) (2021-11-17)

**Note:** Version bump only for package @capacitor/ios

## [3.3.1](https://github.com/ionic-team/capacitor/compare/3.3.0...3.3.1) (2021-11-05)

**Note:** Version bump only for package @capacitor/ios

# [3.3.0](https://github.com/ionic-team/capacitor/compare/3.2.5...3.3.0) (2021-11-03)

### Bug Fixes

- **core:** avoid crash on logging circular objects ([#5186](https://github.com/ionic-team/capacitor/issues/5186)) ([1451ec8](https://github.com/ionic-team/capacitor/commit/1451ec850a9ef73267a032638e73f1fc440647b9))
- **ios:** Avoid CDVScreenOrientationDelegate umbrella header warning ([#5156](https://github.com/ionic-team/capacitor/issues/5156)) ([31ec30d](https://github.com/ionic-team/capacitor/commit/31ec30de193aa3117dbb7eda928ef3a365d5667c))

## [3.2.5](https://github.com/ionic-team/capacitor/compare/3.2.4...3.2.5) (2021-10-13)

### Bug Fixes

- **ios:** proper handling of allowNavigation with multiple wildcard ([#5096](https://github.com/ionic-team/capacitor/issues/5096)) ([cda17a6](https://github.com/ionic-team/capacitor/commit/cda17a6c1504235c1c1e4826830f1d0e2ef2d35c))

## [3.2.4](https://github.com/ionic-team/capacitor/compare/3.2.3...3.2.4) (2021-09-27)

### Bug Fixes

- **ios:** Add CDVScreenOrientationDelegate protocol on CAPBridgeViewController ([#5070](https://github.com/ionic-team/capacitor/issues/5070)) ([530477d](https://github.com/ionic-team/capacitor/commit/530477d05e1364931f83a30d61d4f9b5cb687b19))
- **ios:** show correct line number on console logs ([#5073](https://github.com/ionic-team/capacitor/issues/5073)) ([ec41e74](https://github.com/ionic-team/capacitor/commit/ec41e743aa4ba81e791ad446fac461b7f43b46ed))

## [3.2.3](https://github.com/ionic-team/capacitor/compare/3.2.2...3.2.3) (2021-09-15)

**Note:** Version bump only for package @capacitor/ios

## [3.2.2](https://github.com/ionic-team/capacitor/compare/3.2.1...3.2.2) (2021-09-02)

### Bug Fixes

- **ios:** fixing podspec source paths ([#5002](https://github.com/ionic-team/capacitor/issues/5002)) ([6004a43](https://github.com/ionic-team/capacitor/commit/6004a43c608a4c967e3444c83954ad2095c3dcfd))

## [3.2.1](https://github.com/ionic-team/capacitor/compare/3.2.0...3.2.1) (2021-09-01)

**Note:** Version bump only for package @capacitor/ios

# [3.2.0](https://github.com/ionic-team/capacitor/compare/3.1.2...3.2.0) (2021-08-18)

**Note:** Version bump only for package @capacitor/ios

## [3.1.2](https://github.com/ionic-team/capacitor/compare/3.1.1...3.1.2) (2021-07-21)

**Note:** Version bump only for package @capacitor/ios

## [3.1.1](https://github.com/ionic-team/capacitor/compare/3.1.0...3.1.1) (2021-07-07)

### Bug Fixes

- fixing peer deps issues in android and ios libs ([310d9f4](https://github.com/ionic-team/capacitor/commit/310d9f486db976cb258fcda5ac893f019667617f))

# [3.1.0](https://github.com/ionic-team/capacitor/compare/3.0.2...3.1.0) (2021-07-07)

### Bug Fixes

- **ios:** isNewBinary is true if defaults have no stored versions ([#4779](https://github.com/ionic-team/capacitor/issues/4779)) ([bd86dbe](https://github.com/ionic-team/capacitor/commit/bd86dbeb74771ed201d0100773babf49e6764818))

### Features

- **ios:** Add limitsNavigationsToAppBoundDomains configuration option ([#4789](https://github.com/ionic-team/capacitor/issues/4789)) ([2b7016f](https://github.com/ionic-team/capacitor/commit/2b7016f3b4d62fd8c9d03fde2745b3d515bf08b2))

## [3.0.2](https://github.com/ionic-team/capacitor/compare/3.0.1...3.0.2) (2021-06-23)

### Bug Fixes

- **core:** cordova events not firing ([#4712](https://github.com/ionic-team/capacitor/issues/4712)) ([ca4e3b6](https://github.com/ionic-team/capacitor/commit/ca4e3b62dba6a40e593a1404ba2fe2b416a4ac14))
- **ios:** Use proper native events for cordova events ([#4720](https://github.com/ionic-team/capacitor/issues/4720)) ([99c21dc](https://github.com/ionic-team/capacitor/commit/99c21dcf98f1418d992e845492c730160611783a))

## [3.0.1](https://github.com/ionic-team/capacitor/compare/3.0.0...3.0.1) (2021-06-09)

### Bug Fixes

- Make isPluginAvailable available on bridge ([#4589](https://github.com/ionic-team/capacitor/issues/4589)) ([151e7a8](https://github.com/ionic-team/capacitor/commit/151e7a899d9646dbd5625a2539fd3f2297349bc5))

# [3.0.0](https://github.com/ionic-team/capacitor/compare/3.0.0-rc.4...3.0.0) (2021-05-18)

**Note:** Version bump only for package @capacitor/ios

# [3.0.0-rc.4](https://github.com/ionic-team/capacitor/compare/3.0.0-rc.3...3.0.0-rc.4) (2021-05-18)

**Note:** Version bump only for package @capacitor/ios

# [3.0.0-rc.3](https://github.com/ionic-team/capacitor/compare/3.0.0-rc.2...3.0.0-rc.3) (2021-05-11)

**Note:** Version bump only for package @capacitor/ios

# [3.0.0-rc.2](https://github.com/ionic-team/capacitor/compare/3.0.0-rc.1...3.0.0-rc.2) (2021-05-07)

### Bug Fixes

- **ios:** Don't auto release saved calls ([#4535](https://github.com/ionic-team/capacitor/issues/4535)) ([4f76933](https://github.com/ionic-team/capacitor/commit/4f76933b98d0461564d3dca9b36d4ea1eba8ed49))

# [3.0.0-rc.1](https://github.com/ionic-team/capacitor/compare/3.0.0-rc.0...3.0.0-rc.1) (2021-04-29)

### Bug Fixes

- generate Capacitor.Plugins object ([#4496](https://github.com/ionic-team/capacitor/issues/4496)) ([1c71b7a](https://github.com/ionic-team/capacitor/commit/1c71b7adb2c325e34d980dbf578dc22afb2c332b))
- **ios:** cordova-plugin-screen-orientation compatibility ([#4367](https://github.com/ionic-team/capacitor/issues/4367)) ([b893a57](https://github.com/ionic-team/capacitor/commit/b893a57aaaf3a16e13db9c33037a12f1a5ac92e0))
- **ios:** fire resume/pause events if no cordova plugins installed ([#4467](https://github.com/ionic-team/capacitor/issues/4467)) ([0105f7a](https://github.com/ionic-team/capacitor/commit/0105f7a2c68f2e7bec16ca23384b6acbb2f3057b))
- **ios:** put cancel button of confirm/prompt on the left ([#4464](https://github.com/ionic-team/capacitor/issues/4464)) ([e5b53aa](https://github.com/ionic-team/capacitor/commit/e5b53aa687a70938994802c7b1367cfcbb1e3811))

### Features

- Unify logging behavior across environments ([#4416](https://github.com/ionic-team/capacitor/issues/4416)) ([bae0f3d](https://github.com/ionic-team/capacitor/commit/bae0f3d2cee84978636d0f589bc7e2f745671baf))
- **iOS:** Include native-bridge.js as a resource in both Cocoapods and direct build ([#4505](https://github.com/ionic-team/capacitor/issues/4505)) ([c16ccc0](https://github.com/ionic-team/capacitor/commit/c16ccc0118aec57dc23649894bc3bcd83827f89f))

# [3.0.0-rc.0](https://github.com/ionic-team/capacitor/compare/3.0.0-beta.6...3.0.0-rc.0) (2021-03-10)

### Features

- **iOS:** Obj-C convenience accessors on CAPPluginCall ([#4309](https://github.com/ionic-team/capacitor/issues/4309)) ([e3657d7](https://github.com/ionic-team/capacitor/commit/e3657d77647187946ffcd4c4791f4a47c768db7f))
- **iOS:** Unifying saving plugin calls ([#4253](https://github.com/ionic-team/capacitor/issues/4253)) ([de71da5](https://github.com/ionic-team/capacitor/commit/de71da52b80ff52d0234a5301fc6cae675640a33))

# [3.0.0-beta.6](https://github.com/ionic-team/capacitor/compare/3.0.0-beta.5...3.0.0-beta.6) (2021-02-27)

**Note:** Version bump only for package @capacitor/ios

# [3.0.0-beta.5](https://github.com/ionic-team/capacitor/compare/3.0.0-beta.4...3.0.0-beta.5) (2021-02-27)

**Note:** Version bump only for package @capacitor/ios

# [3.0.0-beta.4](https://github.com/ionic-team/capacitor/compare/3.0.0-beta.3...3.0.0-beta.4) (2021-02-26)

**Note:** Version bump only for package @capacitor/ios

# [3.0.0-beta.3](https://github.com/ionic-team/capacitor/compare/3.0.0-beta.2...3.0.0-beta.3) (2021-02-18)

### Features

- **iOS:** Add automatic Date serialization to bridge communication ([#4177](https://github.com/ionic-team/capacitor/issues/4177)) ([3dabc69](https://github.com/ionic-team/capacitor/commit/3dabc69eab1c8ce0b7734acb641b67d349ec3093))

# [3.0.0-beta.2](https://github.com/ionic-team/capacitor/compare/3.0.0-beta.1...3.0.0-beta.2) (2021-02-08)

### Bug Fixes

- address bug in `isPluginAvailable()` for web and native ([#4114](https://github.com/ionic-team/capacitor/issues/4114)) ([2fbd954](https://github.com/ionic-team/capacitor/commit/2fbd95465a321b8f4c50d4daf22a63d8043cee9b))
- **iOS:** preserve null values in bridged types ([#4072](https://github.com/ionic-team/capacitor/issues/4072)) ([6dc691e](https://github.com/ionic-team/capacitor/commit/6dc691e66a07a421d5d4b08028ea05a65b3ddd84))

# [3.0.0-beta.1](https://github.com/ionic-team/capacitor/compare/3.0.0-beta.0...3.0.0-beta.1) (2021-01-14)

**Note:** Version bump only for package @capacitor/ios

# [3.0.0-beta.0](https://github.com/ionic-team/capacitor/compare/3.0.0-alpha.14...3.0.0-beta.0) (2021-01-13)

**Note:** Version bump only for package @capacitor/ios

# [3.0.0-alpha.14](https://github.com/ionic-team/capacitor/compare/3.0.0-alpha.13...3.0.0-alpha.14) (2021-01-13)

**Note:** Version bump only for package @capacitor/ios

# [3.0.0-alpha.13](https://github.com/ionic-team/capacitor/compare/3.0.0-alpha.12...3.0.0-alpha.13) (2021-01-13)

### Bug Fixes

- **iOS:** properly handle date types during JSValue coercion ([#4043](https://github.com/ionic-team/capacitor/issues/4043)) ([1affae7](https://github.com/ionic-team/capacitor/commit/1affae7cf8d2f49681bf25be48633ab985bbd12f))
- **iOS:** skip Swift type coercion on Cordova plugin calls ([#4048](https://github.com/ionic-team/capacitor/issues/4048)) ([7bb9e0f](https://github.com/ionic-team/capacitor/commit/7bb9e0f22fdea369a6522c2d63a5b56baab9f5ca))

# [3.0.0-alpha.12](https://github.com/ionic-team/capacitor/compare/3.0.0-alpha.11...3.0.0-alpha.12) (2021-01-08)

**Note:** Version bump only for package @capacitor/ios

# [3.0.0-alpha.11](https://github.com/ionic-team/capacitor/compare/3.0.0-alpha.10...3.0.0-alpha.11) (2020-12-26)

### Features

- **iOS:** Open CAPBridgeViewController for subclassing ([#3973](https://github.com/ionic-team/capacitor/issues/3973)) ([a601705](https://github.com/ionic-team/capacitor/commit/a601705f8116ac10d1a0b5942511952c07cf474e))

# [3.0.0-alpha.9](https://github.com/ionic-team/capacitor/compare/3.0.0-alpha.8...3.0.0-alpha.9) (2020-12-15)

**Note:** Version bump only for package @capacitor/ios

# [3.0.0-alpha.8](https://github.com/ionic-team/capacitor/compare/3.0.0-alpha.7...3.0.0-alpha.8) (2020-12-15)

### Bug Fixes

- **ios:** expose lastURL getter ([#3898](https://github.com/ionic-team/capacitor/issues/3898)) ([90b7fe3](https://github.com/ionic-team/capacitor/commit/90b7fe39f5a7cb9d584618a6fba66338f2bbf5fe))

# [3.0.0-alpha.7](https://github.com/ionic-team/capacitor/compare/3.0.0-alpha.6...3.0.0-alpha.7) (2020-12-02)

### Bug Fixes

- **ios:** share message handler between webview and bridge ([#3875](https://github.com/ionic-team/capacitor/issues/3875)) ([f7dff2e](https://github.com/ionic-team/capacitor/commit/f7dff2e661a54bee770940ee1ebd9eab6456ba2e))

### Features

- **ios:** add local and remote notification router ([#3796](https://github.com/ionic-team/capacitor/issues/3796)) ([f3edaf9](https://github.com/ionic-team/capacitor/commit/f3edaf93d4328ea3ee90df573bf14ef0efc7553b))
- **ios:** add path utilities to bridge ([#3842](https://github.com/ionic-team/capacitor/issues/3842)) ([c31eb35](https://github.com/ionic-team/capacitor/commit/c31eb35f83a33626a9d88731c0fff18966c71b0b))
- **iOS:** Add base implementation of permissions calls ([#3856](https://github.com/ionic-team/capacitor/issues/3856)) ([d733236](https://github.com/ionic-team/capacitor/commit/d7332364212794a5005229defd05c129921d9c5d))
- **iOS:** Refactoring configuration ([#3759](https://github.com/ionic-team/capacitor/issues/3759)) ([e2e64c2](https://github.com/ionic-team/capacitor/commit/e2e64c23b88d93a1c594df51dddd0c55d5f37770))

# [3.0.0-alpha.6](https://github.com/ionic-team/capacitor/compare/3.0.0-alpha.5...3.0.0-alpha.6) (2020-10-30)

### Features

- unified errors and error codes ([#3673](https://github.com/ionic-team/capacitor/issues/3673)) ([f9e0803](https://github.com/ionic-team/capacitor/commit/f9e08038aa88f7453e8235f380d2767a12a7a073))

# [3.0.0-alpha.5](https://github.com/ionic-team/capacitor/compare/3.0.0-alpha.4...3.0.0-alpha.5) (2020-10-06)

**Note:** Version bump only for package @capacitor/ios

# [3.0.0-alpha.4](https://github.com/ionic-team/capacitor/compare/3.0.0-alpha.3...3.0.0-alpha.4) (2020-09-23)

**Note:** Version bump only for package @capacitor/ios

# [3.0.0-alpha.3](https://github.com/ionic-team/capacitor/compare/3.0.0-alpha.2...3.0.0-alpha.3) (2020-09-15)

**Note:** Version bump only for package @capacitor/ios

# [3.0.0-alpha.2](https://github.com/ionic-team/capacitor/compare/3.0.0-alpha.1...3.0.0-alpha.2) (2020-08-31)

### Features

- Add extension for creating data from data url ([#3474](https://github.com/ionic-team/capacitor/issues/3474)) ([2909fd0](https://github.com/ionic-team/capacitor/commit/2909fd0ac0d9fdb2cdb7fd25e38742451aa05fb1))

# [3.0.0-alpha.1](https://github.com/ionic-team/capacitor/compare/2.4.0...3.0.0-alpha.1) (2020-08-21)

### Bug Fixes

- **ios:** config bug from swiftlint refactor ([ace879f](https://github.com/ionic-team/capacitor/commit/ace879f42b19aa064efa80142c3783f736745344))

# [3.0.0-alpha.0](https://github.com/ionic-team/capacitor/compare/2.3.0...3.0.0-alpha.0) (2020-07-23)
