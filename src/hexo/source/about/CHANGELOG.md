---
category: "about"
description: "Check all the changes in the different sonar versions"
layout: "changelog"
permalink: "about/changelog/index.html"
title: "0.14.1"
---
# 0.14.1 (November 2, 2017)

## Bug fixes / Improvements

* [[`4d13905075`](https://github.com/sonarwhal/sonar/commit/4d139050755af4bf828727c4d699c85813162fb7)] - Fix: Debugging Protocol Connector improvements (see also: [`#621`](https://github.com/sonarwhal/sonar/issues/621)).
* [[`f5650fba6f`](https://github.com/sonarwhal/sonar/commit/f5650fba6f800b3e8b36ec2a325d24a3ecb5b14d)] - Fix: Force exit when `exitCode` is received (see also: [`#622`](https://github.com/sonarwhal/sonar/issues/622)).
* [[`8de8005af3`](https://github.com/sonarwhal/sonar/commit/8de8005af30777e68f86fed7c19ecf348c19721c)] - Fix: Rule manifest-app-name (see also: [`#610`](https://github.com/sonarwhal/sonar/issues/610)).
* [[`0c17774475`](https://github.com/sonarwhal/sonar/commit/0c1777447521f466be4774fb997cd272b962b405)] - Docs: Update `Permission issue` in User Guide.


# 0.14.0 (October 31, 2017)

## Bug fixes / Improvements

* [[`f6136dc82e`](https://github.com/sonarwhal/sonar/commit/f6136dc82ec925dc45bc973e1fc80574a0054873)] - Fix: Make `jsdom` not hang for invalid certificate (see also: [`#612`](https://github.com/sonarwhal/sonar/issues/612), and [`#615`](https://github.com/sonarwhal/sonar/issues/615)).
* [[`c62ec505c5`](https://github.com/sonarwhal/sonar/commit/c62ec505c5ea623f460c1d7b89e66aa634246f03)] - Docs: Make minor fixes in examples.
* [[`85a432e9ff`](https://github.com/sonarwhal/sonar/commit/85a432e9ff7a3bd33c37de094b28b507c7a66834)] - Docs: Fix broken links.
* [[`400f5b5592`](https://github.com/sonarwhal/sonar/commit/400f5b5592338b6b1f621c4fad21d47f2dadc14c)] - Docs: Rename `Developer Guide` to `Contributor Guide` (see also: [`#609`](https://github.com/sonarwhal/sonar/issues/609)).
* [[`924c0e7cef`](https://github.com/sonarwhal/sonar/commit/924c0e7ceff3930cbe527a353ffa4312a71909d2)] - Docs: Fix link in `no-protocol-relative-urls.md`.

## New features

* [[`a1833cd08d`](https://github.com/sonarwhal/sonar/commit/a1833cd08d37f0195c93da2d85e55be48f77ab72)] - Update: `snyk-snapshot.json`.


# 0.13.0 (October 27, 2017)

## Breaking Changes

* [[`255bb7bc0c`](https://github.com/sonarwhal/sonar/commit/255bb7bc0c5429475619a51926cedf709e7c0c68)] - Breaking: Change definition of `ignoredUrls`.


# 0.12.3 (October 23, 2017)

## Bug fixes / Improvements

* [[`3f03824695`](https://github.com/sonarwhal/sonar/commit/3f03824695d1553dfe4d5334632a9ea28e694d9c)] - Fix: Issue with Cloudinary and error handling.
* [[`1e131ddb28`](https://github.com/sonarwhal/sonar/commit/1e131ddb2828d1718b1c2c756d3cda7c38f4ba0b)] - Docs: Fix link in `docs/about/FAQ.md` (see also: [`#592`](https://github.com/sonarwhal/sonar/issues/592)).


# 0.12.2 (October 20, 2017)

## Bug fixes / Improvements

* [[`4ed7cf2aa9`](https://github.com/sonarwhal/sonar/commit/4ed7cf2aa9092e15576287226271dfa9b8e82979)] - Fix: Issue in Cloudinary with invalid images.


# 0.12.1 (October 20, 2017)

## Bug fixes / Improvements

* [[`0e141f33ce`](https://github.com/sonarwhal/sonar/commit/0e141f33ce7d159e22c7e33aa15867e03eff025a)] - Fix: Cloudinary authentication issue.


# 0.12.0 (October 19, 2017)

## Bug fixes / Improvements

* [[`92c815ca57`](https://github.com/sonarwhal/sonar/commit/92c815ca57cf791e93a36b68c602588a4f1b2cc2)] - Fix: Improve `test-server` and `debugging-protocol` requests logic (see also: [`#582`](https://github.com/sonarwhal/sonar/issues/582)).

## New features

* [[`8a7e1ea5f7`](https://github.com/sonarwhal/sonar/commit/8a7e1ea5f7bbe5dc21db412a79aec487354d986b)] - New: Add image optimization rule using Cloudinary's service (see also: [`#575`](https://github.com/sonarwhal/sonar/issues/575)).


# 0.11.0 (October 19, 2017)

## Breaking Changes

* [[`f794bc8f36`](https://github.com/sonarwhal/sonar/commit/f794bc8f362c970d0cc398546e7bf614a4759661)] - Breaking: Require `text/javascript` as the media type for JavaScript files (see also: [`#568`](https://github.com/sonarwhal/sonar/issues/568)).

## Bug fixes / Improvements

* [[`55b2190c35`](https://github.com/sonarwhal/sonar/commit/55b2190c354fde5ed581c4d00a9f5e235ff4ae53)] - Docs: Update FAQ with information about the online scanner and the project history (see also: [`#580`](https://github.com/sonarwhal/sonar/issues/580)).


# 0.10.2 (October 5, 2017)

## Bug fixes / Improvements

* [[`8da2e2da12`](https://github.com/sonarwhal/sonar/commit/8da2e2da1296098146095849d59bdf7b56eabc18)] - Fix: Redo last release in order to fix the `node\r` related issue (see also: [`#564`](https://github.com/sonarwhal/sonar/issues/564)).


# 0.10.1 (October 4, 2017)

## Bug fixes / Improvements

* [[`2918e04ce7`](https://github.com/sonarwhal/sonar/commit/2918e04ce7a21381cacee03ffe373a3bc276bb54)] - Fix: Generate correctly the `.sonarrc` file if not found (see also: [`#562`](https://github.com/sonarwhal/sonar/issues/562)).


# 0.10.0 (October 3, 2017)

## Bug fixes / Improvements

* [[`f5c0218bdf`](https://github.com/sonarwhal/sonar/commit/f5c0218bdf5ef85921f032edece6c903abda9d07)] - Fix: Update `new-core-rule` templates (see also: [`#551`](https://github.com/sonarwhal/sonar/issues/551)).
* [[`f2e500d16b`](https://github.com/sonarwhal/sonar/commit/f2e500d16b4ff5c690e84b67811ec7dd319a675c)] - Fix: New version notifications handling (see also: [`#507`](https://github.com/sonarwhal/sonar/issues/507)).
* [[`bb17fbbc2b`](https://github.com/sonarwhal/sonar/commit/bb17fbbc2b9e92fc6e5bf705da1dbf75da828971)] - Fix: Don't show help after analyzing site (see also: [`#553`](https://github.com/sonarwhal/sonar/issues/553)).
* [[`f6dae7cfe2`](https://github.com/sonarwhal/sonar/commit/f6dae7cfe21068b56f6e7d9b9a9156943980545c)] - Fix: Property name for new tab url.
* [[`718f7198ac`](https://github.com/sonarwhal/sonar/commit/718f7198ac1bf0624fb9a13a3bc71445942c9f40)] - Fix: Make tests more reliable and faster (see also: [`#502`](https://github.com/sonarwhal/sonar/issues/502)).

## New features

* [[`62a52a66a4`](https://github.com/sonarwhal/sonar/commit/62a52a66a409adc106dc0f7100b4a38253a95f82)] - New: Make viewport rule work with `viewport-fit` (see also: [`#557`](https://github.com/sonarwhal/sonar/issues/557)).
* [[`01fbe5ee9c`](https://github.com/sonarwhal/sonar/commit/01fbe5ee9cc2d8c9e93f61ddfbfc47cd41e9faae)] - New: Add `amp-validator` rule (see also: [`#545`](https://github.com/sonarwhal/sonar/issues/545)).
* [[`67553dce6c`](https://github.com/sonarwhal/sonar/commit/67553dce6c0c390b561cca0d44aa0bf8a07e7515)] - New: Add option to create external rule (see also: [`#528`](https://github.com/sonarwhal/sonar/issues/528)).


# 0.9.0 (September 27, 2017)

## Breaking Changes

* [[`e585daa5d5`](https://github.com/sonarwhal/sonar/commit/e585daa5d51db030edc259443705d938d7ff66a6)] - Breaking: Make `rawResponse` a `Promise<Buffer>` (see also: [`#164`](https://github.com/sonarwhal/sonar/issues/164)).

## Bug fixes / Improvements

* [[`0cfb1bb49c`](https://github.com/sonarwhal/sonar/commit/0cfb1bb49c847eb4d5ed54691dbb88cb796694bf)] - Fix: Create new rule only in `sonar`'s root folder (see also: [`#527`](https://github.com/sonarwhal/sonar/issues/527)).

## New features

* [[`67553dce6c`](https://github.com/sonarwhal/sonar/commit/67553dce6c0c390b561cca0d44aa0bf8a07e7515)] - New: Add option to create external rule (see also: [`#528`](https://github.com/sonarwhal/sonar/issues/528)).


# 0.8.1 (September 22, 2017)

## Bug fixes / Improvements

* [[`41a56bef2f`](https://github.com/sonarwhal/sonar/commit/41a56bef2ffd21b3612e3c0b637754b95629d242)] - Fix: Add `tests/helpers` to `npm` package (see also: [`#532`](https://github.com/sonarwhal/sonar/issues/532)).
* [[`8207e0fb3b`](https://github.com/sonarwhal/sonar/commit/8207e0fb3b4dc7fa180e6b057babd78252d560a8)] - Docs: Add `connector` support information (see also: [`#523`](https://github.com/sonarwhal/sonar/issues/523)).


# 0.8.0 (September 20, 2017)

## Bug fixes / Improvements

* [[`ff45cb6497`](https://github.com/sonarwhal/sonar/commit/ff45cb649737eaad438d54934d85bea556fdf1c5)] - Fix: Improve documentation for connectors (see also: [`#500`](https://github.com/sonarwhal/sonar/issues/500)).

## New features

* [[`84561d847f`](https://github.com/sonarwhal/sonar/commit/84561d847f598158d571ddef6a8f5f8201592254)] - New: Add `chrome-launcher` support for Windows Subsystem for Linux (WSL) (see also: [`GoogleChrome/chrome-launcher#26`](https://github.com/GoogleChrome/chrome-launcher/issues/26)).


# 0.7.0 (September 15, 2017)

## Breaking Changes

* [[`75b936b710`](https://github.com/sonarwhal/sonar/commit/75b936b710505160fda7200034e4aada13ce1688)] - Breaking: Add support for multiple formatters (see also: [`#322`](https://github.com/sonarwhal/sonar/issues/322)).

## Bug fixes / Improvements

* [[`f3074a3cbb`](https://github.com/sonarwhal/sonar/commit/f3074a3cbbb5f5508d87836e042037dddcee63f7)] - Fix: Make `apple-touch-icons` rule not break for invalid or corrupt images (see also: [`#515`](https://github.com/sonarwhal/sonar/issues/515)).
* [[`b2e30d6d1f`](https://github.com/sonarwhal/sonar/commit/b2e30d6d1fd0f0a3f00a80fd04420d662ca6747a)] - Docs: Add `--engine-strict` to install instructions (see also: [`#511`](https://github.com/sonarwhal/sonar/issues/511)).


# 0.6.3 (September 11, 2017)

## Bug fixes / Improvements

* [[`fcafcc9add`](https://github.com/sonarwhal/sonar/commit/fcafcc9add5baac6fc006708ebc15ed35cec6cea)] - Fix: Make `npm` package not include `devDependencies`.


# 0.6.2 (September 8, 2017)

## Bug fixes / Improvements

* [[`bedc9644dc`](https://github.com/sonarwhal/sonar/commit/bedc9644dcd844455140da8fb2572716c8135fec)] - Fix: Make `npm` package actually include `npm-shrinkwrap.json` file (see also: [`#481`](https://github.com/sonarwhal/sonar/issues/481)).


# 0.6.1 (September 8, 2017)

## Bug fixes / Improvements

* [[`0d7b4038bf`](https://github.com/sonarwhal/sonar/commit/0d7b4038bfd07987c969253429c77d4acc997eab)] - Fix: Add `npm-shrinkwrap.json` to the `npm` package (see also: [`#481`](https://github.com/sonarwhal/sonar/issues/481)).
* [[`3300798874`](https://github.com/sonarwhal/sonar/commit/3300798874163866fa38da6a8295ad10033878a3)] - Fix: SemVer related issue with `no-vulnerable-javascript-libraries` rule (see also: [`#504`](https://github.com/sonarwhal/sonar/issues/504)).


# 0.6.0 (September 8, 2017)

## Bug fixes / Improvements

* [[`32dcb344bd`](https://github.com/sonarwhal/sonar/commit/32dcb344bd36a2e5aa94ae2e3589e0d9cb5ad72c)] - Fix: Make improvements to `chrome` connector (see also: [`#387`](https://github.com/sonarwhal/sonar/issues/387), and [`#471`](https://github.com/sonarwhal/sonar/issues/471)).
* [[`97bc6ea26b`](https://github.com/sonarwhal/sonar/commit/97bc6ea26b61b32c98499e4754a66ad48ce21511)] - Fix: Make `fetchContent` return raw data in chrome (see also: [`#495`](https://github.com/sonarwhal/sonar/issues/495)).
* [[`a5b9951d2d`](https://github.com/sonarwhal/sonar/commit/a5b9951d2d2a83d047c22f9b08252974666e1355)] - Fix: Spinner getting stuck issue (see also: [`#485`](https://github.com/sonarwhal/sonar/issues/485)).
* [[`481961c571`](https://github.com/sonarwhal/sonar/commit/481961c571059137a780aa3d5243ab4d232a016d)] - Docs: Make rule code examples more consistent.
* [[`e2af8a87cf`](https://github.com/sonarwhal/sonar/commit/e2af8a87cf2a3a1fb892006853b98a423fd7dff6)] - Fix: Infinite hop calculation when there's a cycle (see also: [`#486`](https://github.com/sonarwhal/sonar/issues/486)).

## New features

* [[`ab11a172a3`](https://github.com/sonarwhal/sonar/commit/ab11a172a3d6a0f84a316d63654df29ecd343a7c)] - Update: `snyk-snapshot.json`.
* [[`78b6cb1bb1`](https://github.com/sonarwhal/sonar/commit/78b6cb1bb1d677aadb316f24e05f56342ffacbcc)] - New: Add rule to check manifest's `name` and `short_name` members (see also: [`#136`](https://github.com/sonarwhal/sonar/issues/136)).
* [[`7c4947eac1`](https://github.com/sonarwhal/sonar/commit/7c4947eac194c1985ca666b3e504274814b0520e)] - New: Add rule to check `apple-touch-icon`s usage (see also: [`#33`](https://github.com/sonarwhal/sonar/issues/33)).
* [[`d13e26be35`](https://github.com/sonarwhal/sonar/commit/d13e26be354752ea59740cfc7604952c04d21dcd)] - New: Add `summary` fomatter (see also: [`#487`](https://github.com/sonarwhal/sonar/issues/487)).


# 0.5.2 (September 2, 2017)

## Bug fixes / Improvements

* [[`861931f83d`](https://github.com/sonarwhal/sonar/commit/861931f83d257172efb219f04cc45fbbfd414093)] - Fix: Make `html-checker` rule not break if no HTML is passed.
* [[`d3899126b8`](https://github.com/sonarwhal/sonar/commit/d3899126b87019a516654757b3ac07f3156f3e53)] - Fix: Error in `onLoadingFailed` (see also: [`#469`](https://github.com/sonarwhal/sonar/issues/469)).
* [[`4eeeda950f`](https://github.com/sonarwhal/sonar/commit/4eeeda950f20ec737f73df96e4770efb1aa585a5)] - Fix: Improve error messages for `highest-available-document-mode` rule (see also: [`#483`](https://github.com/sonarwhal/sonar/issues/483) and [`#477`](https://github.com/sonarwhal/sonar/issues/477)).
* [[`19f95d12be`](https://github.com/sonarwhal/sonar/commit/19f95d12be6a4f0c911b343efe541f1e1b321788)] - Fix: Error with `jsdom` and attribute names containing `.` (see also: [`#482`](https://github.com/sonarwhal/sonar/issues/482)).
* [[`b125186fb7`](https://github.com/sonarwhal/sonar/commit/b125186fb759d9d92b952111681f50b28b71f3f1)] - Fix: Remove `null` locations from error messages (see also: [`#478`](https://github.com/sonarwhal/sonar/issues/478)).


# 0.5.1 (September 1, 2017)

## Bug fixes / Improvements

* [[`f45b745479`](https://github.com/sonarwhal/sonar/commit/f45b745479d5b38670b6e6f3a9293abda60c3fde)] - Fix: Lock `jsdom` to `v11.1.0` in `package.json`.


# 0.5.0 (August 31, 2017)

## Breaking Changes

* [[`c2d0282591`](https://github.com/sonarwhal/sonar/commit/c2d0282591b79fab4c32ba45e939b4eb96438237)] - Breaking: Rename `cdp` connector to `chrome` (see also: [`#361`](https://github.com/sonarwhal/sonar/issues/361)).

## Bug fixes / Improvements

* [[`0cc1f05e51`](https://github.com/sonarwhal/sonar/commit/0cc1f05e515755e6f25542c6c4d0362b48e3ba4e)] - Docs: Tweak `no-vulnerable-javascript-libraries` rule related documentation (see also: [`#470`](https://github.com/sonarwhal/sonar/issues/470)).
* [[`984aabcf7c`](https://github.com/sonarwhal/sonar/commit/984aabcf7c8cdc0d5f77922ea002f75164740a44)] - Fix: Filter out duplicate fetch requests (see also: [`#460`](https://github.com/sonarwhal/sonar/issues/460)).
* [[`df53c0ef36`](https://github.com/sonarwhal/sonar/commit/df53c0ef36bb642344da1f3a7f9ec27c95e8dd78)] - Fix: Update CLI templates (see also: [`#461`](https://github.com/sonarwhal/sonar/issues/461)).
* [[`bbf1e6eaa4`](https://github.com/sonarwhal/sonar/commit/bbf1e6eaa401a14733a623a9416292966d8e64e0)] - Fix: Make `content-type` correctly detect the `charset`.

## New features

* [[`60c6c725d1`](https://github.com/sonarwhal/sonar/commit/60c6c725d138212b07cee00cc8b508f6b37a2e2d)] - Update: `snyk-snapshot.json`.
* [[`633f6d3a53`](https://github.com/sonarwhal/sonar/commit/633f6d3a53cca623fff796d0b5e8ce721bf7213c)] - New: Ask about `browserslist` when generating the configs (see also: [`#446`](https://github.com/sonarwhal/sonar/issues/446)).
* [[`0852ab95b2`](https://github.com/sonarwhal/sonar/commit/0852ab95b27cd9934df6805fe333aedbd102cff8)] - New: Add rule to check for vulnerable libraries (see also: [`#125`](https://github.com/sonarwhal/sonar/issues/125)).


# 0.4.0 (August 25, 2017)

## Breaking Changes

* [[`e35b778004`](https://github.com/sonarwhal/sonar/commit/e35b778004be3038d0b994f9a258dd454b994622)] - Breaking: Make `content-type` rule use proper fonts types (see also: [`#425`](https://github.com/sonarwhal/sonar/issues/425)).
* [[`941d439aff`](https://github.com/sonarwhal/sonar/commit/941d439affca16e3af1b0df90e739ee746df2313)] - Breaking: Upgrade `file-type` to `v6.1.0` (see also: [`#428`](https://github.com/sonarwhal/sonar/issues/428)).
* [[`c03079912b`](https://github.com/sonarwhal/sonar/commit/c03079912beda28a7d4f7b4bc9427b3cd0e8e621)] - Breaking: Use `browserslist` defaults (see also: [`#452`](https://github.com/sonarwhal/sonar/issues/452) and [`#453`](https://github.com/sonarwhal/sonar/issues/453)).

## Bug fixes / Improvements

* [[`0507ff7279`](https://github.com/sonarwhal/sonar/commit/0507ff72793989790694695ef2633d8d177218de)] - Docs: Fix link to `no-disallowed-headers` (see also: [`#403`](https://github.com/sonarwhal/sonar/issues/403)).
* [[`56fc97aa3c`](https://github.com/sonarwhal/sonar/commit/56fc97aa3c4f84f89eb5fb07a59b4c36d8e4deb8)] - Fix: Make `rule-generator` not encode quotes (see also: [`#392`](https://github.com/sonarwhal/sonar/issues/392)).
* [[`49833d62ca`](https://github.com/sonarwhal/sonar/commit/49833d62ca4e5ccd2c9ad90ad010aabf9587a1f4)] - Fix: `SyntaxError` when using `jsdom` (see also: [`#404`](https://github.com/sonarwhal/sonar/issues/404)).
* [[`45955ebc5c`](https://github.com/sonarwhal/sonar/commit/45955ebc5ce0473a421cb2bb4445721c2801c50c)] - Docs: Fix link in `strict-transport-security.md` (see also: [`#417`](https://github.com/sonarwhal/sonar/issues/417)).
* [[`dd161ed3d0`](https://github.com/sonarwhal/sonar/commit/dd161ed3d0abddb10c6bfc9d5be51ca68c916964)] - Docs: Make minor improvements (see also: [`#437`](https://github.com/sonarwhal/sonar/issues/437)).
* [[`5cc4484a83`](https://github.com/sonarwhal/sonar/commit/5cc4484a836881a6fa0ec40eee56027c143bf2f4)] - Docs: Update `Code of Conduct` links.
* [[`aa14e6cb57`](https://github.com/sonarwhal/sonar/commit/aa14e6cb573afe07345fa64f489bc17b53c5792d)] - Fix: Avoid analyzing `/favicon.ico` multiple times (see also: [`#427`](https://github.com/sonarwhal/sonar/issues/427)).
* [[`9755cadf04`](https://github.com/sonarwhal/sonar/commit/9755cadf0442203ca30d2850d4e950ac068b9503)] - Fix: Error when scanning non-existent URL (see also: [`#389`](https://github.com/sonarwhal/sonar/issues/389)).

## New features

* [[`2be5a4ba20`](https://github.com/sonarwhal/sonar/commit/2be5a4ba203aea66b6b61ac7e9c2a4c7fdf191f8)] - New: Add rule to check the usage of the `Strict-Transport-Security` header (see also: [`#23`](https://github.com/sonarwhal/sonar/issues/23)).
* [[`e9e4a95fd7`](https://github.com/sonarwhal/sonar/commit/e9e4a95fd73210d44cb62fa0769082756d136ad0)] - New: Notify users when a new version of `sonar` is available (see also: [`#419`](https://github.com/sonarwhal/sonar/issues/419)).
* [[`d515c5aa8b`](https://github.com/sonarwhal/sonar/commit/d515c5aa8bf1cba850d4f7bafaeb33588ab3a5f7)] - New: Create a new config file if one doesn't exist (see also: [`#354`](https://github.com/sonarwhal/sonar/issues/354)).
* [[`12a415f40d`](https://github.com/sonarwhal/sonar/commit/12a415f40dcdb711861b2494be31f0504cac3471)] - New: Add rule to check the usage of the `Set-Cookie` header (see also: [`#24`](https://github.com/sonarwhal/sonar/issues/24)).
* [[`f70a4d37e8`](https://github.com/sonarwhal/sonar/commit/f70a4d37e8ef24c6165b548c3d45cbfea1e9439b)] - New: Add rule to check the usage of the `viewport` meta tag (see also: [`#82`](https://github.com/sonarwhal/sonar/issues/82)).


# 0.3.0 (July 1, 2017)

## Breaking Changes

* [[`acfd196ed7`](https://github.com/sonarwhal/sonar/commit/acfd196ed708b4f40d08ea9c7063a6d60dd2f812)] - Breaking: Rename `disallowed-headers` rule.

## Bug fixes / Improvements

* [[`d55171d36e`](https://github.com/sonarwhal/sonar/commit/d55171d36e367c46b3d0ec2f791c7ec2d955bd52)] - Docs: Add missing `)` in x-content-type-options.md.
* [[`28c782db16`](https://github.com/sonarwhal/sonar/commit/28c782db16ca6140a083fae76f143a05f595694e)] - Fix: Make `disown-opener` ignore certain protocols.


# 0.2.0 (July 2, 2017)

## Breaking Changes

* [[`8b202fb8d9`](https://github.com/sonarwhal/sonar/commit/8b202fb8d930248275fe9984ba23e868be35f77c)] - Breaking: Disable `ssllabs` rule by default (see also: [`#355`](https://github.com/sonarwhal/sonar/issues/355)).
* [[`6fcb46ae17`](https://github.com/sonarwhal/sonar/commit/6fcb46ae17abc1933f8ee30b98cad59d15be9843)] - Breaking: Use `connector` instead of `collector` (see also: [`#286`](https://github.com/sonarwhal/sonar/issues/286), and [`#358`](https://github.com/sonarwhal/sonar/issues/358)).

## Bug fixes / Improvements

* [[`b9d278e7a1`](https://github.com/sonarwhal/sonar/commit/b9d278e7a189f4bb12992f0bdcbf78cd471f95c1)] - Docs: Move `CODE_OF_CONDUCT.md` in the root (see also: [`#353`](https://github.com/sonarwhal/sonar/issues/353)).
* [[`7b904d6b4f`](https://github.com/sonarwhal/sonar/commit/7b904d6b4f68bcf8b757a1aa3b04b842e5f0317b)] - Docs: Fix broken links (see also: [`#363`](https://github.com/sonarwhal/sonar/issues/363)).
* [[`ae149ba609`](https://github.com/sonarwhal/sonar/commit/ae149ba60916e593b2afc0d64252e43d527e6e64)] - Docs: Add pull request related guidelines (see also: [`#373`](https://github.com/sonarwhal/sonar/issues/373)).
* [[`d52247d3e1`](https://github.com/sonarwhal/sonar/commit/d52247d3e10686255c8596aaf494b0bb26cd954e)] - Docs: Add note about handling permission issues (see also: [`#308`](https://github.com/sonarwhal/sonar/issues/308), and [`#364`](https://github.com/sonarwhal/sonar/issues/364)).
* [[`9cd8d7fdc9`](https://github.com/sonarwhal/sonar/commit/9cd8d7fdc9baf68c59a823801de04c87f49b31d8)] - Docs: Fix broken links in `pull-requests.md`.
* [[`fd6c083f84`](https://github.com/sonarwhal/sonar/commit/fd6c083f841132189a54e3d8d3bba9ff88473e1d)] - Docs: Make minor improvements (see also: [`#367`](https://github.com/sonarwhal/sonar/issues/367)).

## New features

* [[`08f36db2b4`](https://github.com/sonarwhal/sonar/commit/08f36db2b4b9736f5c7f0522861cda8eed658926)] - New: Add rule to check markup validity (see also: [`#28`](https://github.com/sonarwhal/sonar/issues/28)).
* [[`2893a0a7c1`](https://github.com/sonarwhal/sonar/commit/2893a0a7c16abca27c1ce457d0ff05d7334b093f)] - New: Make connectors download manifest & favicon (see also: [`#71`](https://github.com/sonarwhal/sonar/issues/71)).


# 0.1.0 (June 30, 2017)

## Breaking changes

* [[`2e29881377d`](https://github.com/sonarwhal/sonar/commit/2e29881377dd36a2e8d13b006482346b18b6bc73)] -
  Change how `sonar` resources are loaded
  (see also: [`#234`](https://github.com/sonarwhal/sonar/issues/234)).

## Bug fixes / Improvements

* [[`98e3b2e5aa3`](https://github.com/sonarwhal/sonar/commit/98e3b2e5aa34445e7871f897071f7216f7fdd561)] -
  Fix `Could not find node with given id` error
  (see also: [`#275`](https://github.com/sonarwhal/sonar/issues/275)).
* [[`48ed6e9e19c`](https://github.com/sonarwhal/sonar/commit/48ed6e9e19ccf47e84f6e960cc37be1dd2b2a262)] -
  Refactor `CDP` related code
  (see also:
  [`#311`](https://github.com/sonarwhal/sonar/issues/311),
  [`#330`](https://github.com/sonarwhal/sonar/issues/330),
  [`#324`](https://github.com/sonarwhal/sonar/issues/324), and
  [`#332`](https://github.com/sonarwhal/sonar/issues/332)).
* [[`c3803821c06`](https://github.com/sonarwhal/sonar/commit/c3803821c0619b5210f5fe0fd1a37d27fb9a1143)] -
  Improve requester
  (see also: [`#260`](https://github.com/sonarwhal/sonar/issues/260)).
* [[`b613918fdde`](https://github.com/sonarwhal/sonar/commit/b613918fdde302106a3b777f70df0c9a31fcc37c)] -
  Improve documentation.

## New features

* [[`3e2863b3963`](https://github.com/sonarwhal/sonar/commit/3e2863b3963403406b178b46ade8b62824e432bd)] -
  Add support for rule shorthands, and ability to specify rules as an array
  (see also: [`#283`](https://github.com/sonarwhal/sonar/issues/283)).
* [[`b54dd55b48a`](https://github.com/sonarwhal/sonar/commit/b54dd55b48aada5e2fd63df002a2d2096e1164be)] -
  Add rule generator
  (see also: [`#238`](https://github.com/sonarwhal/sonar/issues/238)).
* [[`70018b6b33b`](https://github.com/sonarwhal/sonar/commit/70018b6b33bca821cab9de23900d47dac24b1524)] -
  Make `disown-opener` rule use `targetedBrowsers`.
