# Changelog

All notable changes to this project are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).
Versions follow Home Assistant calendar versioning (`YYYY.M.PATCH`)
and [Conventional Commits](https://www.conventionalcommits.org/).

## [2026.11.0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/releases/tag/2026.11.0) - 2026-11-03



### Breaking Changes

- [**breaking**] replace the parse contract with V2 ParseOutcome([5f45302](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5f45302e4ae0d864d04d5c4fff36c6e1b04e2cc9))


### Bug Fixes

- outdoor temp, MASS empty match, forum docs (#283)([26f701f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/26f701f3cfad1335fcda5c55a48250f7b52588e5))

- **speech:** boost only hard ASR names (#282)([cfd3ee5](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cfd3ee55d35a6d812d80af513fc6c50540be1820))

- **dispatch:** volume/cover services and MASS match wait([344d0bc](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/344d0bcabcc20783b4e248ec194a8bd0deb2017d))

- **media:** reject weak MASS matches and name the track (#280)([f5ea9f3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f5ea9f3554360d526d1ae3956e948d12bad21664))

- drop aiohttp from the HA manifest requirements([58b63e8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/58b63e82f787f39869a8f96edb94c4bf36cfcf54))

- raise parse timeout and stop false mid-sentence status([c844436](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c8444365789b59585bb2bb75149dfa8320bc902a))

- raise parse timeout and stop mid-sentence status replay([1039fb1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1039fb190f27a53030f99279165f792049f7a9e5))

- keep hallway and timer phrases from matching weather stems([cd8a8e8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cd8a8e8633d4962f25fac7c654d52a1a3bf7fb18))

- drop banned bitte token from weather query stop list([6e34a59](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6e34a59cc0f1bf6c41efdec86b0b977814f854aa))

- keep shopping lists and OOD weather phrases out of weather lex([02c2ed3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/02c2ed3bec39026546f55ec503b4f66cdccd0a11))

- leave generated weather lists to the pack generator([b70aa0a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b70aa0aa6278f67c794467f355b7c9622795f2f9))

- use Range::contains for night hours([b29933a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b29933a6a8157f6f248e40a5dfa20b3dce1081c7))

- keep handwritten de and en packs under 500 lines([6c52d5e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6c52d5e3742a33b534d1033cdf13fccb61ceda12))

- keep staging Lotse UI when promoting to main([a89fbc8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a89fbc824cc264bfcb8d925fa70da90ca275cbad))

- upgrade url past idna Punycode spoof([e866276](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e866276689df0d35239e4c31ffcd81e0488c4510))

- let Lotse suggest without lane tabs([0d82186](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/0d8218679c24f10b70d8eeff89b88126b1b01e85))

- leave generated AT/CH timer packs to the generator([5a3be76](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5a3be7662d13ec07029d4896d33e598893b8f1f5))

- keep timer decrease and structured AI Task([a7a82fb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a7a82fb7e435dc8002971066d73c5a82274023c2))

- translate settings hints in every locale([7f517f6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/7f517f6e22d4c177c6fabb2e7cc1ca50cde1e7bb))

- toast whether save actually landed([23d0c79](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/23d0c7960791781c01eacd3a3e84c7e442577760))

- list LLM models from addon ingress([7a1ed4f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/7a1ed4f7f52740a20d97709f3d47f1385cfb10ea))

- speak floor status as natural clauses([50df50a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/50df50acd8fd54135e03d361dc091a77f4511461))

- list floor temperatures per room([5b22a40](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5b22a40b4be0604fd4cc195141876825015a76ed))

- let Configure switch App and bundled engine on Supervisor([158c951](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/158c9514ed25fdf9de4f5fbdcfaa00b827306750))

- size the HACS sidebar with HA's iframe panel([0696162](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/0696162a9bcc1614441d627867ff5a8747a88484))

- do not treat aus/all as all-off scene([4eff355](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4eff3559f96db82df37e70535d06deb880b24b77))

- pick named lamps, helper timers, and staging sidebar([e7f6e96](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e7f6e96cd2b5e7f2bff65ef1749ba766853f0891))

- keep named standleuchte when skipping room lights([aeeca0d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/aeeca0d49f68e46165e4e8524ab578fd9a892a87))

- English room-light gold and named bedside side([2854ed8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2854ed86f5a72ea5ecb8b0ffa405c04bd3ffe54c))

- align gold with room lights, timers, and music([4ca470c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4ca470c4916e3a85c5bb3a6870167749a88630dc))

- add engineOffline to every Assist locale([eb9146f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/eb9146ff13591e4fae6e7ebbe7fec8f57da95538))

- fail closed when custom phrases cannot persist([9dbecdd](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9dbecdd91824ab28c60102501021be01277cac82))

- keep staging Assist code when promoting to main([684a325](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/684a3254f2c9fde0635b1d677b2452dfc0cc99fc))

- apply Debian security updates in the runtime image([4c30cfe](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4c30cfe032286ea8f5373282d2283246d9b9c487))

- only skip household weather when a calendar noun is present([3d503d3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3d503d3d3359564d227e564e06fc6f3fe77daebe))

- keep Assist on the Lab plan and show pipeline settings([53fc5bc](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/53fc5bcbe0e9128995ff5f2ff97505fac67fee2f))

- store stream-published flag on speech extra_data([cf6accc](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cf6accca3328daa067b59b7819793256ffacf804))

- publish LLM tokens into Assist chat([47108f2](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/47108f216287227caf6e95fd9f69d815c6bf6e8c))

- show HACS and app changelogs before install([f57a746](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f57a74644cebc764fc0eb1a83fc0e341325c123b))

- keep floor and area status when climate is in the snapshot([20d58c1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/20d58c11d3ddab0afccb124653c7cbd16e080d01))

- satisfy clippy on Lemonade URL guess and hydrate without HA states([fdd7466](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fdd7466f5b9ab3a3282f40a210bebbb587959550))

- keep Assist weather and climate speech after LLM refine([b8091b4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b8091b43b40caa9e3d2fc3e6c44858801fd2e732))

- fill operator chrome keys and satisfy clippy([aec558f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/aec558f3c1166f0fbc6bf52b5337faf803174a68))

- satisfy clippy on unused Lotse helper([4647cfe](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4647cfe52be7f9e6183db2bd39be60a21454e249))

- keep Assist weather in the live home graph([5411a6c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5411a6c06036ff8b1e2fa852fa6845103136088a))

- use clamp for refine token budget([5595968](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5595968a3dabe364e8baf600fa85356c70630c48))

- keep first calendar speech and stream assist live([ba936ff](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ba936ffd74cf19437422eac13b70230000f3605e))

- satisfy clippy on trainer merge writes([48d70b7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/48d70b75392c5fc4cc23f215adedb3cc44631aa9))

- keep HA string generators importable([46d7926](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/46d792651c3d664a29ad9637d7d3e13e4fa7963b))

- close leftover operator gaps on staging([55c130b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/55c130bcbd17ecefc6d2fabe3ece11b18b0b5d1f))

- stop using the HA OpenAI SDK on Assist LLM paths([fe1a8b0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fe1a8b05335244f39467886e50afdb09387a0955))

- show Home charts by default and skip wizard flash([a553b7e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a553b7e45ee0598a8734b0ae37d071c19b5ed5a7))

- make cargo-audit ignore idna and allow webpki-roots license([ec2b7b8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ec2b7b8137ea9b2201b856768d5d0186f0f21016))

- CI for LLM client fmt, clippy, translations, and idna advisory([fb9232f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fb9232fa964c58e580de5adec3e1da1d53769a6a))

- apply Debian security updates in the runtime image([eb9217a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/eb9217a358ba7c27e7d19951afdac4c01d0c9f77))

- only skip household weather when a calendar noun is present([2379acd](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2379acd763cdebebeb42d479195d80efe28effdf))

- keep Assist on the Lab plan and show pipeline settings([041d8a9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/041d8a9de249213139d6a7127f9455b1dffdb148))

- store stream-published flag on speech extra_data([7df3f60](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/7df3f6098bf9880514650b64de5223ebf1913dd5))

- publish LLM tokens into Assist chat([cfefb58](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cfefb58dca822c3eba45949a4e4b491873787ea8))

- close Assist listen after execute([41491a3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/41491a39b666fe12e660efb15e6b3bc20d874e6c))

- use Option::map for native ceiling fixture tokens([703250e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/703250e13b11581df8e5b765253c49aed2068549))

- close per-language parity gaps and always test all locales([4aa8988](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4aa8988a47adafcbdd53ab419529b172fe480a01))

- speak clarify and guards in the request locale, not German([0c5988b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/0c5988bf8e3ca6a371bfe41f8ef1bb02c4cd2e75))

- play kitchen Alexa and refuse non-TV living-room binds([9ac83a1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9ac83a18dfb73836c23b49961176a4876e661717))

- apply heat, relative dim, Kelvin, kitchen play, and honest TV speech([34fdb07](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/34fdb0790f1d4bc98eff98e8090628674dd5fa82))

- keep bare TV on the Fernseher alias, room TV on the living player([66230d3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/66230d3eae16ac957cf19ba8361ae0c97ab3713b))

- keep clock, living-room TV, and kitchen follow-up honest on Assist([278f4cf](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/278f4cfd85a9d2fcbe235df0f0d195060bc24039))

- restore last-light seed and stop media from stealing TV or scripts([e7493ed](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e7493edcf8eda9addda353ada0466e9b75e8bdbb))

- rustfmt the suite and keep action.rs under 500 lines([f190499](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f1904995466c378424546a86a1c7b0595ea60460))

- satisfy rustfmt, clippy, and the isolated-fallback session test([5748f16](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5748f16c961521b004b5ccd426ccfdd38a52c500))

- give the story LLM prior turns so egal stays on topic([c49a5fd](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c49a5fd272bf5cde73d8fe6ca5758d824ef0eca6))

- keep LLM story replies in chat instead of living-room status([47893b3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/47893b3fdaa11cb87a7c0054d860094f779d2e06))

- keep the last light so "schalte es wieder ein" works after a new wake([484f98d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/484f98d304df69c9d4a4873a4c179c991b33d8ee))

- keep music nouns off the TV pool and recover island ASR([94f57d6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/94f57d66526a321a8d177586a38992909bb7c407))

- keep German home-graph tokens out of generated packs([bed41bb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bed41bb5238d79a9d4d8e862cd104bc2285fb27e))

- close native-script parity gaps for laundry, unlock, and lists([4896458](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4896458ce112d8d598958d063b96992e75b05151))

- treat ac as cooling and label parity fixtures more precisely([e4ab033](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e4ab033fce3c3d951ec2a4fc73011def761b21b7))

- confine overlay, bundle, and journal files under the data dir([84e7355](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/84e7355d38d215961546360dd31280422027bc38))

- run the bundled engine on Alpine Home Assistant Core([f91b0c6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f91b0c6e958eacf861b5c7f7b39e2603ee5ebe01))

- pack the engine tarball member as klar([3ae4060](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3ae406053dfec889cc31b6d78b4ffbfe1541d857))

- keep compound.rs under the 500-line gate([92ce6e7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/92ce6e7dc9122cca1336f197e77aed9f372190b2))

- speak final TTS and stream it by sentence([6201129](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/620112940e02d0c20187f722cd5c11ac9cad56d4))

- match umlaut rooms like Küche to HA slugs([fff3d05](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fff3d053b1afbf9ddfafb2683ea18a0f4e05224d))

- options flow 400 on Configure (#108)([1e75383](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1e753831d7c7d0e7a3409ffa9c2463affb794026))

- stop LLM fallback from speaking Klar tool names([096c704](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/096c704b512e2de705ae25f61a18646829ee2055))

- keep Wiedergabe pause out of the German pack path([0bf48f4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/0bf48f49ed72647eb1c900f0d627ba432f986dd9))

- treat Wiedergabe stopp as media pause([e2e6a58](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e2e6a5859933763af9f34b17763cc61f396979ff))

- play named music on Music Assistant instead of turning the player on([1c1bd1c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1c1bd1cad1527f295badb8eaa7b2bbbf722a5879))

- label language options and keep a missing Lovelace config from aborting setup([a2a6151](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a2a61517e2c626938a12355aacef703a197c9b36))

- give the Klar Lovelace dashboard an id so setup can load([9c3f74c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9c3f74cd1e1e5fe1c7e3ac7e97ff78cfcfbca694))

- switch Stable/Staging at any time and pick language from a dropdown([f0a9eb1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f0a9eb11380f9d76ebd161bd75c920c966f51e82))

- describe staging RCs from commits since main([daeb3fd](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/daeb3fd00bbbb7de94c1c45d8774c07645b26b04))

- drop RE2-illegal lookahead from the KLAR_TOKEN gitleaks rule([2b0dab6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2b0dab64580513076cdde53ad157a1c51d1efb56))

- make Staging security gates runnable without extra licenses([4c07c4c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4c07c4cf5e7ab4393bb706d88ba00a259cefd656))

- grant callee permissions so Staging does not die at startup([2462c8b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2462c8bc35e2698c7044774036537052d61d5932))

- restore shopping, room-scoped fixtures, and floor-lamp resolve([52ebda8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/52ebda8c86a4c9783b7be8945a6fb293ab88025e))

- refresh stale parity datasets and sort hassfest manifest keys([ddf24e5](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ddf24e5d117ac82f4c98b4c6d11986e4a74245c2))

- unblock staging PR CI for fmt, clippy, pack size, and hassfest([07bd43e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/07bd43e7d170656f895ccf4ba96b1311de0d931a))

- speak room climate from HA state when area get fails([142a7c8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/142a7c8e1ae360c946623e6bffe627249ac31180))

- let HA sync homes and answer temperature queries([ce107ae](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ce107ae4a898325562fb419a89e657d6593a9b29))

- accept V2 parse trace tokens from the engine([51126f4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/51126f4ad85c6c2f5a15ca67b385a489ebb73ee1))

- match rustfmt 1.97 line wrapping([b616d1d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b616d1da3bd990f7949e818d0eacdab3a8ced9d0))

- satisfy clippy 1.97 some_filter([bfd8b3a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bfd8b3ad81743290d3e8ae9e709e2245ba43678a))

- harden Music Assistant targeting([f995ccb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f995ccbcb7642f4e1e2b64b3d47bcf456ba33b83))

- satisfy clippy for media parsing([f38048d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f38048d75331b4e52b539214bbec0024985dcb47))

- format Music Assistant voice control changes([240e577](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/240e577aba55a4418ced07d3527e8ed0866552f7))

- enable ingress writes and live traffic stats([bae4bce](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bae4bcead7fd34b7a709ef425dd7785156cae019))

- keep graph nodes in view([28e5e60](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/28e5e60b9aec0033ccde8706ca44aee330772ac6))

- include React UI in release images([3a6ae6b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3a6ae6bf0836f070ef33f6eb662542e0a64a7497))

- restore CI checks after test move([bead2af](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bead2af1d2d55267a9a130c93fff8b97b7d6ed65))

- let personality refine sound natural instead of stamping a cue([c37156e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c37156e95706d672921fba0d655b95f22389af91))

- include LICENSE and third-party notices in release artifacts([eaf0d32](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/eaf0d3203a2e7e4932e230052690445e739e721e))

- unify room light targeting and harden the parse path([ff33d9b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ff33d9bedad485888dd9570a382a479aa715d47f))

- harden API auth and infer action from the resolved target([79dfa13](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/79dfa1331edefd147965cc092edce671f82cf2b5))

- speak HA display names and keep compound light status([517bb37](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/517bb3784f528610f52ee9a9a1b06d68b19e1f16))

- detect formal news follow-up prompts([af6dcde](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/af6dcde84b09a1b6acf21b99566094ed3637d68f))

- keep curated changelog history when cutting a release([ac8f7d1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ac8f7d1ac6678debf9b33d8254d90ce267517c1d))

- elide needless lifetime on fallback_climate([b934148](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b9341485a9aa8e483bcffbe11e6aee6ff0f766d1))

- skip Adaptive Lighting switches when expanding Licht([70ee27c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/70ee27c4b90ef92b18d53d0f74618b694fecea60))

- start release checks from the prepare job([94433cf](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/94433cf14971c61a5dfe0492643242ab725792c6))

- land release commits without an Actions pull request([4de314a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4de314a631984ce1a41c3a99c8cece92c81084ae))

- store Assist personality in the Home Assistant integration (#30)([27b4846](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/27b48467b7e7accef7ffa5f9d47335e33eb22771))

- keep room-scoped all-lights and run the parsed entity (#29)([ad298e4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ad298e4d8f2ac3ddf1965e4d5e3191adb8f4c0ec))

- keep und-names in questions and prefer the outlet (#27)([d8d5585](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d8d5585027d21fb0d2636cfe6d4129ec61309b54))

- pass the device name so Assist can run entity-only intents (#26)([904cd85](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/904cd856aebd043a63dabc184333b9473497fd43))

- do not match aus to the Alles-aus scene (#24)([f3a3bd6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f3a3bd622bf668c70ee8c9a9d3205eb386a3d92b))

- keep one target and replay pronoun follow-ups (#22)([50a2ca2](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/50a2ca285881d57f16f968917ad0d8d7472e828d))

- speak German states and keep the web UI personality on Assist (#20)([f322059](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f32205998c86a1d35e21d75cb1bac9084b686d18))

- inherit Hue room areas so Schlafzimmerlicht hits the Kugel([2ee34c8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2ee34c863db6d8e310eeff259131848056cd6597))

- resolve live Wohnung lights, names, and English phrases([8fa3318](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8fa331880af731590b7ffae678adfc222d35a972))

- cancel timers and speak climate temperature (#12)([3449b33](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3449b338232d885039cc8d26ce6382797a8979a4))

- start Assist timers and match the real shopping list (#10)([e3e6de2](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e3e6de2e16e0678681e1565f49169c2526765a5f))

- German and English Assist speech and rooms (#8)([3b4da80](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3b4da808fbf07152b60f65bd800337d08621878b))

- bilingual Assist conversation agent (#6)([04a806a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/04a806af3359c951bc9c8b23ba5cff316471f434))


### Documentation

- credit Aquila MIT voice suite([51e785b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/51e785b4afec05a9f672de93922f65fcf3039bd3))

- credit Aquila MIT voice suite([ae99f65](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ae99f6515918f7c5957f5d26a405c4e9602ed0c8))

- plan moving Assist product logic from Python into the engine([ef77932](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ef77932917cbbce778f535324a55a9911664c281))

- ship ADR 0001 work on staging, not as a main release([fd61d85](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fd61d857a233794b9937cf7a598416f7bbf99dfe))

- require every compiled locale on each ADR 0001 stage([4f09e64](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4f09e649b18dee548f8d3631dbdfd06fe5a743c6))

- add ADR 0001 implementation plan with staged PRs([5333b49](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5333b49dcab3dc81c78e46e67da4e54700e7c3d8))

- treat language packs as seeded lexicon databases([48deda0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/48deda0f6797ceab776b285da67e29ecd324a522))

- make all three policy layers UI- and trainer-controlled([249a46a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/249a46ac22761b502b7f984c1c2187662a68f007))

- propose ADR 0001 for visible rules and an LLM trainer([405dabd](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/405dabdf90949a54ef5088466fe2e7ca0110c8bf))

- add an interactive runtime architecture map([e8aae11](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e8aae119fce178222c663ae0fff1546046d92cfd))

- bump rust from 1.97-bookworm to 1.98-bookworm (#125)([af96514](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/af9651497d102188391f16aa7246f6e5af380638))

- spell out HACS vs App vs bundled engine([2125e2d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2125e2dbe6cd553b5765b03fa334f92563d52ba1))

- show 67 languages and the follow-up banner([e9802c8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e9802c838e917c8539685a4c22a24b5da71ce76b))

- bump rust from 1.85-bookworm to 1.97-bookworm (#104)([4d5bf80](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4d5bf804d2bc7685d84fcc815cb7fa6837237cc5))

- shrink the README logo so it fits the HACS info panel([ea8e596](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ea8e5964c74c462a7394537a8a9920092d2ba4be))

- use a markdown image for the logo so HACS can render it([82b0cd4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/82b0cd4482ffe841886b6a192e612751c462e4c3))

- load the README logo from an absolute URL so HACS can show it([221c2c4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/221c2c4b1961909e59167731c3ca20faed5b7608))


### Features

- **weather:** parse and speak forecast in every locale([2623e62](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2623e62cb762a79c322797cd728a2b6856b9f773))

- **speech:** ASR boost prompt for Whisper (#275)([5deab9b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5deab9b5006e8dcd6cb0b8acace4cd4a62e2c30f))

- let Lotse write mapping and rules([f371d5e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f371d5eb5fb064e3cd6ff3f59534f414bddda2fb))

- add AI Task and LLM call console([75b3086](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/75b308662a7baa85413ac73541c1d470848646e5))

- refine spoken NLU replies by kind([429a20f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/429a20f5b66d4b20d0ea693a30148ad3602e1b8c))

- native timer decrease and how-long in every locale([3f755ef](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3f755ef49bc1c0ad9e555369200a3a344ebee56f))

- harden writes, HACS sidebar, and locale speech([c76067c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c76067c2eeff4d60e5d36d98d25250da7c8bb55e))

- speak named devices in floor and room status([095bac1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/095bac1f2d7f1a7118ad832304c43f91e09c940d))

- let users opt in to Assist tools on the chit-chat LLM([a87a2fa](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a87a2fae58fdac688bbe87ca07296fcabbca28f5))

- stream LLM deltas into Assist chat and TTS([fb8d530](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fb8d530a0473a5c66035b50cdfc74406b6398dd5))

- provider LLM lists, thinking flags, wizard voice([2f5219d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2f5219da2c3ae83fff9dc40af88e4f625bd29125))

- setup wizard, settings backup, custom voice, and temperature units([8c79b59](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8c79b59fb0464c64acd944b3fd59c7967174d6a4))

- lock Lotse replies and persist light theme([1980eb4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1980eb489fd667bce0ad367f4bdd7ca19d63c084))

- ship Lotse as a resizable operator sidebar([38d3e28](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/38d3e284970d61a6806d044ff0df33b698c7623d))

- bind trainer lanes and wrap the operator console([915e6bf](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/915e6bfaedc28ef19d572e24ceac5fbc1e46f255))

- trainer tools, consent, and Assist HA tools([4cc7ce8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4cc7ce8b146c3c297d5004fd1239e23889c1ad03))

- discover LLM models, collapse nav, fix Lab and legend contrast([cf09111](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cf09111f44a49ecccde50495bba9fa858c7adf32))

- move product settings into the operator UI for every Assist locale([66ae3cd](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/66ae3cd34c7e039ece3e764c1dd697d4c5aaea79))

- render Assist speech from the HA state snapshot([14a05be](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/14a05be760df206b46d8418839c5ee12b9bfa822))

- HA state snapshot contract for post-execute speech([a8262f9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a8262f9786377b610401ce6528d8fbaac1abbddd))

- engine-owned Assist fallback prompts and RAG protocol([7843666](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/784366612d894516fedec3267ebfc8366252f4d2))

- flag quiet_ack_eligible on execute plans([dc61681](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/dc61681f1a5f74b982d6e5618c43ed4ab81d2f67))

- build refine prompts and accept_refined on the engine([42e58a9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/42e58a9578320652b95add8b57bdf1c7b7ca7594))

- lay out Rules lanes as the ADR 0001 path grid([e124b40](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e124b40ff8c6be67727e8389998c7ec88dfeebc7))

- refresh operator UI with Klar tokens and shadcn forms([f6b4c4d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f6b4c4d3012e16fed3e96577e53764e85ba26e52))

- persist Klar LLM in operator UI without a HA agent([407a127](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/407a12706e285885447d916fe40830f4b9b0a814))

- OpenAI-compatible LLM client in Rust with SSE streaming([f7ca237](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f7ca23782cbb5e8a317b4e38c3e2f38d054dad09))

- ship govern safety seeds and trainer validate([250d56a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/250d56a0d8b11b94dbd335f4dec7b5e5cfd62d19))

- overlay match on/off and lexicon set paths([107793a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/107793a4a4ae01da2af9e88d3be245ee0987a410))

- show match, language, and house lanes on one path([e9cfbea](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e9cfbeaa296ac4d7361fbb042ecca5665b143fed))

- expose PolicyTrace path fields and a match catalog([cd35ae6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cd35ae63677b529e6b45d77194c62fccac2021e7))

- speak named devices in floor and room status([dc8ac6a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/dc8ac6a63bf8a1d27002462fcfaf7ea85368875b))

- let users opt in to Assist tools on the chit-chat LLM([8dd72cd](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8dd72cd5bf1286a2d71afe94c961be94f8bd8bcf))

- stream LLM deltas into Assist chat and TTS([fd408b1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fd408b1c26b226a9de6681c5708a884c47d374a1))

- isolate Assist sessions and land the conversation suite([1111544](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1111544c0f01448aca2169b4ea5bd28255e56888))

- localize the HA UI for every Assist locale([9649ec9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9649ec90f17095d69611f94122073e743f2dc74c))

- add a quiet chime switch for simple light replies([05fc35c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/05fc35c72449095cef186724494097552f77065f))

- ship operator UI with wizard, Graph, and light theme([d88f6e2](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d88f6e2b6b615e1a45e1a6143196850d60ed02ea))

- localize operator chrome for Assist locales([c0cbc09](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c0cbc0963c13faaca434c7ea990075171eeca7ef))

- parse Assist STT native script and keep LLM replies in-pack([082296a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/082296a6042aa68ee6f1f79e1dc0100393de8861))

- list, create, delete, and move calendar events([2c57f4e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2c57f4e6caf2a39e51c768caea3563e2b38930b1))

- localize the HA UI for every Assist locale([a8de462](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a8de46258c2393c2ba4f6c49e0787192e2d33e46))

- add a quiet chime switch for simple light replies([dccb80a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/dccb80a3cc14259c3c55d97e4cea6bfb84cccc19))

- add a Stable/Staging switch on main([bb4f8f1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bb4f8f13117b79d1477bc288cc85fadcd5fd9c19))

- apply personality refine to every reply and add Jarvis([050a8b1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/050a8b1b9a6d008573edbba466f5f375400eb568))

- speak NLU replies in a natural voice across locales([0788ab7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/0788ab7d0e256a156c06f3feef8a4d60ccaf01d7))

- drop V1, locale-pure packs, and a keyed catalog([6e7dd47](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6e7dd47b01af3ee798c987345fe4a746d16689f5))

- switch Stable/Staging in one control([e39c5b9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e39c5b95b7bef2da8968f26dcf296e6a56f2d76c))

- full-home language lift, HA channel, and staging RC workflow([ab9709e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ab9709e1dd5e555f5edf2bada4c6cb3b074e7f6e))

- phrase rules, journal tab, fuzzy compounds (#91)([c226a9d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c226a9dccb21e29bddc1429a2b40e89f462f8641))

- policies, journal, NLU-RAG, and quieter UI (#88)([c651441](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c65144115799bc02ca34b26c0240581e35b87c04))

- harden voice matching for ASR errors([e99b683](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e99b6830008468f6392db9a9e18844f94ac99e9b))

- add Music Assistant voice control([70a943b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/70a943b0670fbea0475012c7c0ae834f6ea54df5))

- add React operator UI and support bundles([b08b1ba](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b08b1ba390e5121c4a20e7f401c47b6b671d8577))

- refine NLU replies in each personality voice([1380e2e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1380e2e6306dddcda5306fdcdd3b5d6d19c7f5c6))

- refine NLU replies through the fallback LLM([5ec1b89](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5ec1b89e22d6ae37ab3f962ffe49d503a2556dfd))

- route news questions through a briefing then the LLM([dec7875](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/dec78757648e80a6f1830e2786cc7603c7818576))

- map leftover Assist devices in the web UI (#18)([bc85ce4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bc85ce45a03bd40d942b2dc2d43c81487017e81c))

- publish Docker images and a Home Assistant add-on repository([e62a715](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e62a71537fcea8551cb6ecab60b9f4956f7cfc9e))

- start the Klar engine from the Home Assistant integration([b757353](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b757353758d1dbe221477ef2b9f3b9aba72610f5))

- add HACS install for the Home Assistant integration([26e6916](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/26e6916b5aa494c2c0e8f495b2b9cc8f3d3e5a15))


### Miscellaneous

- **web:** move shadcn to devDependencies([a6f0acd](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a6f0acd8e17d4dde416819f714997815fbf3d175))

- skip parity_langs on staging nextest (#278)([f93076d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f93076d77458344bbb689a0879c75009df7e6c51))

- retrigger required checks for 2026.9.8([91673a7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/91673a72493c6950e38f5eb05d10d5266b32502a))

- stop Dependabot bumping MSRV-pinned idna crates (#237)([caf4fd5](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/caf4fd5336b539728fc8619e19cfb2f6aeaea06e))

- add Cloud Agent environment config([c2dd52d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c2dd52de947b10c5505ca140655bd93886755da8))

- sync generated packs with lang_packs generator([7710c5a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/7710c5aef71ab0429ce260a7e86d716f285872c1))

- drop Python 404 fallbacks now that the engine owns Assist product logic([9c89dcb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9c89dcb9f4a7d7062c0a15f69697feb1db3b8eda))

- land CalVer cuts through a release PR([4dcbbcf](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4dcbbcf66b410dd86eeedfb2c412051f06f9c2fb))

- remove Figma Code Connect from the engine repo([db72567](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/db72567a09b0eac9541455dbda4319dbc0a4f9f7))

- require a green pipeline before any PR merge (#130)([4975f62](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4975f620fa2d6429ffca2be5c2298fdb1b7caf78))

- stop shipping armv7 after Home Assistant dropped 32-bit([a262240](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a2622405d3c66895ec9b2ca4ccbafe1eb31e8287))

- emit Jarvis voice prefixes in generated locale packs([9bf8555](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9bf8555bb7b271b7fb60fc3e21ce0dbdb9e853b1))

- nextest, faster PR checks, auto-release on main (#90)([5b9c1fa](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5b9c1fac3bdcb89787be5803e5540ec6e4ec26fc))

- bump docker/setup-buildx-action from 3 to 4 (#87)([fa42574](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fa42574b82ac8871a32bb6c7e3cac2c4f68a23da))

- bump actions/setup-node from 6 to 7 (#86)([77aa0bd](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/77aa0bd91526c96524737acdfa38bfdd5f57a460))

- bump docker/login-action from 3 to 4 (#85)([2256dd3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2256dd3c79e41f4faf443c6025bbf3b072183563))

- format graph stats fix([74f4487](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/74f44875d926b494f24cbc894b0feedeca944045))

- format release changes([8e6374f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8e6374f7f86fe224480eb5d40cf424ce7fe74722))

- include ENGINE_VERSION in the release land commit([6c7bc7d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6c7bc7dd1578baa9b58bc54bdd70d66543e3fec8))

- run rustfmt in CI([77e0c95](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/77e0c95c7671af99e55f2b55ec99c943fe55d4e2))

- switch releases to Home Assistant calendar versions (#31)([e099c83](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e099c8388927f995fa4ad63337c6f4617af91b32))

- open a release PR instead of pushing version bumps to main([f38a784](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f38a784c1cdbe0acfee2ddfcd4fc52b0bc5b8352))

- add CODEOWNERS, a PR template, and read-only CI permissions([7429d26](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/7429d2609a968ba4059f335ebb6acd1677d33440))

- bump checkout, artifact, and gh-release actions([dbf9171](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/dbf9171c913256658580bd20045168a568dc5959))

- generate changelogs and releases with git-cliff([a3cb586](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a3cb5862c1a448f1312cd41b970e97bf5d222223))


### Other

- Merge pull request #1 from danielsynek94-gif/fix-czech-ci-main([07959a9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/07959a9bae7f3fd001960769e2412ed32038e6c2))

- Fix Czech localization and release checks([d2a01b7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d2a01b74678e37f07865095932b13e17d8421e4f))

- Update image reference in config.yaml([d790f3b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d790f3b0446904805dc48279d828bd1d5e340bb1))

- Update image reference in config.yaml([c7c8c80](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c7c8c8015d20dc6a5cfa7db62ca88c317b6e68ab))

- Update GHCR image reference in build workflow([5ba6308](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5ba63081c31f4cd94ca89b6820f4b099cabd9c61))

- Modify Klar NLU config with new localization details([2dbd8ef](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2dbd8ef84c9c7169a0f4efcafd51122027bc18eb))

- Add files via upload([1f14d46](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1f14d46b78005d07b976dfa75a18a0e2b7c53602))

- Add files via upload([cc77de2](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cc77de2477417bec71f68b8f13ab93fa6a839d33))

- Add files via upload([970f1f6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/970f1f6dd1fa8c618f2acedaf343b94aebd02bf5))

- Add files via upload([483ea3e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/483ea3e44166ac0b4564d5592d8f74629d37a493))

- Add files via upload([4863a99](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4863a9954093028e0f1311bd593da8db70099499))

- Add files via upload([c198c56](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c198c56027bd7975dc4b11879945374a285be641))

- Add files via upload([d50e7a4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d50e7a44161bf227ff487e3dd1d2f739891aad20))

- Add files via upload([66f3d29](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/66f3d292c9856816e9df269791bbec25a8a23414))

- Merge pull request #285 from FABBricate-IT-Solutions/chore/release-2026.10.3([446de79](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/446de79fbcd84ad542c86f112f9432964b24ecbf))

- Merge pull request #284 from FABBricate-IT-Solutions/staging([b1c467f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b1c467f12a1454713ac2e35874661c8a0c0ee0cd))

- Merge pull request #281 from FABBricate-IT-Solutions/fix/volume-cover-dispatch([b805d80](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b805d808d33a2d07fc922aca82ac5da1cffc1988))

- Merge pull request #277 from FABBricate-IT-Solutions/chore/sync-main-into-staging([7674f02](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/7674f02ca05fb2176a193a2083f8a5e661477c30))

- sync main 2026.10.1 into staging([65b5727](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/65b5727ef5ab844e1049957810d27fcfc67085c9))

- Merge pull request #276 from FABBricate-IT-Solutions/chore/release-2026.10.1([0c7fe03](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/0c7fe03d237d6e7a2af6610a1c9ec36c1bd62820))

- bump brace-expansion from 5.0.9 to 5.0.12 in /web([a2efb85](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a2efb853c3f8b3a593186b94660c6017a02e3452))

- bump brace-expansion from 5.0.9 to 5.0.12 in /web([e17711a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e17711a4310f28867166be45d1d7ca6d8ce45c52))

- bump ip-address from 10.7.0 to 10.7.3 in /web([af5de6d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/af5de6dba1f500c567e619cc40610afef2744adb))

- bump ip-address from 10.7.0 to 10.7.3 in /web([e542fc4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e542fc40897dcfde13a759baa2606f7d22e4c326))

- bump fast-uri from 3.1.7 to 3.1.8 in /web([a7e4f4c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a7e4f4c2c4e30b1f72e1e217c8a76121f1bca49b))

- bump fast-uri from 3.1.7 to 3.1.8 in /web([70d1ce9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/70d1ce90312d009bcfc6bbe8005aed77066ccdc5))

- Merge pull request #271 from FABBricate-IT-Solutions/chore/release-2026.10.0([cb2940d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cb2940dbf5f3b6b054d7495135196f38dc182148))

- bump the npm-minor group in /web with 2 updates([2fb41d0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2fb41d0c65af4ff5b0207dc6ef720098d535bc27))

- bump the npm-minor group in /web with 2 updates([d1ca1e0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d1ca1e0690d82c1a7b9e29a2386e5d404f5cf424))

- bump vite from 8.3.0 to 8.3.1 in /web in the npm-patch group([cda77aa](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cda77aa6bcaf31f2515e261af0ddf3a8267182a2))

- bump vite from 8.3.0 to 8.3.1 in /web in the npm-patch group([5f1536e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5f1536e352ea0d5300e175e67f145762b16ebb73))

- bump thiserror from 2.0.20 to 2.0.21 in the rust-patch group([eb6b605](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/eb6b6059cedf7865a66ffb8d841e5c943cd00b33))

- bump thiserror from 2.0.20 to 2.0.21 in the rust-patch group([cbe6fbc](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cbe6fbcc0e4805598bebbc96cb838b7d15ca790a))

- Merge pull request #265 from FABBricate-IT-Solutions/dependabot/cargo/rust-patch-722c7a5dc4([58dc96a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/58dc96af1b0dce34dd8e72df6e4b6a5d9eb338f6))

- bump clap from 4.6.6 to 4.6.7 in the rust-patch group([032ead4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/032ead46e941b6aa40952cd328a39c8e03e8ca2a))

- Merge pull request #266 from FABBricate-IT-Solutions/dependabot/npm_and_yarn/web/npm-minor-7bee64aca0([da0793f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/da0793fd90807b05992483a549536d2b92022f28))

- bump the npm-minor group in /web with 2 updates([35b7b11](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/35b7b117224314bb79bdea9c921ba1e2687bdd6e))

- Merge pull request #264 from FABBricate-IT-Solutions/chore/release-2026.9.11([9f99057](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9f99057e1260e6a71616a8a80707f854cf114033))

- Merge pull request #262 from FABBricate-IT-Solutions/dependabot/npm_and_yarn/web/npm-minor-d15a6bbb73([27e6479](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/27e64795529b379fb12a6e07e6701efbe9113981))

- merge main (rustls + parse fixes) into npm-minor([89fe881](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/89fe881472525ccfcd38df981392b917f43bf22c))

- Merge pull request #263 from FABBricate-IT-Solutions/fix/parse-timeout-and-false-status([e2dc377](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e2dc37722e63934bd0fe53e1d0b79beb016a545b))

- merge main into npm-minor; keep cn 0.2.6 and minor bumps([6c1139a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6c1139aec37198bc4bcee2441795d7333ff03357))

- Merge pull request #261 from FABBricate-IT-Solutions/dependabot/npm_and_yarn/web/npm-patch-5812b47994([fdbe4c5](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fdbe4c5e8732ae78bd8d338b04a515e410d4fced))

- bump cn from 0.2.5 to 0.2.6 in /web in the npm-patch group([91aa9b9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/91aa9b9a66adbf3e845718490b44395700989b0b))

- Merge pull request #260 from FABBricate-IT-Solutions/dependabot/cargo/rust-patch-98b7f37da0([12c17a2](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/12c17a2fdb52ab0bac2e19011d409d6a19334fce))

- bump uuid from 1.26.0 to 1.26.1 in the rust-patch group([379b00e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/379b00ec665be321545e4bcbda214ad1a47f27c5))

- bump the npm-minor group in /web with 6 updates([771e840](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/771e840867c4e631455da2f6e166d6f6e44b3419))

- Merge pull request #259 from FABBricate-IT-Solutions/chore/release-2026.9.10([f5edb18](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f5edb1849b32a2054830106575efbc2f48fa0b6c))

- Merge pull request #258 from FABBricate-IT-Solutions/feat/weather-all-langs([8913939](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8913939292023fafdc8aa42a360e9ff6f64bb4d6))

- Merge pull request #256 from FABBricate-IT-Solutions/chore/release-2026.9.9([22dbf15](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/22dbf159122f9b8f78e1e35fa9719baed44b3d04))

- Merge pull request #255 from FABBricate-IT-Solutions/release/promote-2026.9.9([8891bd6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8891bd68c64565b519c239d1f7b9a95168a7d6b4))

- accept staging product over main 2026.9.8([4a9db2e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4a9db2ec054d3dd0c5e44f1f349c47e3ccc11ca0))

- Merge pull request #240 from FABBricate-IT-Solutions/chore/release-2026.9.8([d0cf956](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d0cf95666e29762beb686d319d17d7dcaf342204))

- Compact Lotse on mobile so the chat keeps the screen (#239)([412108a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/412108a46b719769ab5a9942dbdc5adf7c4f5590))

- Merge pull request #238 from FABBricate-IT-Solutions/chore/release-2026.9.7([daffe7c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/daffe7c73d537f5f297f1c2d57fa952e209c6cc4))

- main into release 2026.9.7([f688333](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f688333772fc9c2f96bbaa62cd11950985163702))

- bump recharts from 3.8.0 to 3.10.1 in /web in the npm-minor group (#236)([5796317](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5796317eb494e56bf3bf64df9d74dea24d195396))

- bump @types/react-dom from 19.2.5 to 19.2.7 in /web in the npm-patch group (#234)([2843919](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2843919682870b03538952dde82adfb47dc54771))

- bump the rust-patch group with 2 updates (#233)([64c715d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/64c715de603a22a551571da7def62edf96daada1))

- Merge pull request #232 from FABBricate-IT-Solutions/chore/release-2026.9.6([c5f2b2e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c5f2b2ea4bb2317687be25b44758a3b08c670ce9))

- main into release 2026.9.6([e7b5172](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e7b517233f7fe5218f7cf0973e2567d21d15787a))

- Merge pull request #197 from FABBricate-IT-Solutions/cursor/setup-dev-environment-a60a([d5f7110](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d5f71108914300ac161d904d733226e55d9b6157))

- Merge pull request #230 from FABBricate-IT-Solutions/fix/idna-rustsec-0421([6c5adcf](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6c5adcfcc0b2a26da82773fdc0bf4e6b434f2533))

- Merge pull request #231 from FABBricate-IT-Solutions/fix/custom-phrase-live-store([8be8509](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8be850902cd34588d8fad9bdce77efef4b825ed4))

- Merge pull request #254 from FABBricate-IT-Solutions/feat/lotse-house-writes([1e6593b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1e6593bb031c6fa36adb5a1a5728912faa5d5bbc))

- Merge pull request #253 from FABBricate-IT-Solutions/fix/lotse-no-lanes([b14b4b2](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b14b4b227db189a2eb9f036234a5a20769dff3ea))

- Merge pull request #252 from FABBricate-IT-Solutions/fix/timer-duration-ai-task([e0e4f69](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e0e4f6964edb497e24cc7aa1523dd92e06004533))

- Merge pull request #251 from FABBricate-IT-Solutions/feat/ai-task-llm-console([1b4b5c3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1b4b5c369fabc6f5e6ef496110afeae98fea2767))

- Merge pull request #250 from FABBricate-IT-Solutions/fix/settings-hint-i18n([1cc6013](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1cc60130586e019c7f98decb95b23bcd30d70352))

- Merge pull request #249 from FABBricate-IT-Solutions/feat/refine-bands([98010d7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/98010d746ebd0cdc3b990319f0c08b99bf1b52cc))

- Merge pull request #248 from FABBricate-IT-Solutions/fix/addon-ingress-llm-models([c5065fd](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c5065fdedf920b842bae616694278bebcf24f66e))

- Merge pull request #247 from FABBricate-IT-Solutions/fix/natural-floor-status([44cecee](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/44ceceef5f3c1399cb967157e5f1d999577b497f))

- Merge pull request #246 from FABBricate-IT-Solutions/fix/floor-temperature-listing([6145b08](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6145b085dacff942faa96758abe2092dbe07c83c))

- Merge pull request #245 from FABBricate-IT-Solutions/fix/engine-host-switch([bc0b95a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bc0b95a252099a0bd38f37f4081a7267c994f0dc))

- Merge pull request #244 from FABBricate-IT-Solutions/fix/hacs-iframe-panel([fd710a0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fd710a0c1e3fd7a298084a595992fe7b25d00f7f))

- Merge pull request #243 from FABBricate-IT-Solutions/feat/locale-timer-how-long([5e5a904](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5e5a904e374283f94ae33bf1e9d02ed943a1f58e))

- Merge pull request #242 from FABBricate-IT-Solutions/fix/live-clarify-timer-sidebar([88d7974](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/88d7974a5e5691874b40f722b53abbcedd342348))

- Merge pull request #241 from FABBricate-IT-Solutions/feat/auth-sidebar-l10n([83aedf8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/83aedf84da139eeaac004a3b7341da4c67c8c493))

- sync staging into auth-sidebar-l10n([b405eb9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b405eb9161d5660565060d3fb025da7fce4aa012))

- Merge pull request #227 from FABBricate-IT-Solutions/docs/credit-aquila-suite([a17b117](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a17b117e1e6d4634dd97b983bdbac1c3dda5567f))

- Merge pull request #229 from FABBricate-IT-Solutions/chore/release-2026.9.5([9b43806](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9b438062cd3bef88b6676dcad568180804a55877))

- Merge pull request #228 from FABBricate-IT-Solutions/docs/credit-aquila-suite-main([bb721c7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bb721c74a85972bd08bcf6e16a282df96419d2e3))

- Merge pull request #226 from FABBricate-IT-Solutions/chore/release-2026.9.4([517b3f0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/517b3f09268877cc78edde960dbb5587bdf7175d))

- Merge pull request #225 from FABBricate-IT-Solutions/release/promote-staging([136c27d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/136c27daa457fc74b465501f3b7cba70c7f69098))

- accept staging product over main 2026.9.3([84a77b9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/84a77b99b56feed645c120808896bea1ba0e2a6f))

- Merge pull request #196 from FABBricate-IT-Solutions/chore/release-2026.9.3([1b6e95d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1b6e95d48346f1268cbfc2c69cde07f7820c5fc1))

- Merge pull request #195 from FABBricate-IT-Solutions/release/promote-image-security-updates([b17384b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b17384b2cace6cc055fe954eb3547b7a5b7ba40c))

- Merge pull request #193 from FABBricate-IT-Solutions/chore/release-2026.9.2([954c0ad](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/954c0adc0511ca45f28ed77042bd84589cef6ac9))

- Merge pull request #192 from FABBricate-IT-Solutions/release/promote-assist-follows-lab([94132aa](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/94132aae94bd4439b5bc2969eecb23bcba439d04))

- Merge pull request #190 from FABBricate-IT-Solutions/chore/release-2026.9.1([ae10883](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ae108834b4e70e67a23030a42774180e1eb6e866))

- Merge pull request #189 from FABBricate-IT-Solutions/release/promote-named-room-status([72aeadb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/72aeadbdd84637f642e91c4461f3503ccb002cfa))

- Merge pull request #187 from FABBricate-IT-Solutions/chore/release-2026.9.0([135831a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/135831a8b26a8d271e1aef65413d7244a1c70731))

- Merge pull request #186 from FABBricate-IT-Solutions/release/promote-allow-llm-tools([6c28793](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6c28793c83f7af6dd60319cbcb3b54e0c848eb4a))

- Merge pull request #184 from FABBricate-IT-Solutions/chore/release-2026.8.67([7d978a6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/7d978a6dc711dd52215991ce50236a1bb7554503))

- Merge pull request #183 from FABBricate-IT-Solutions/release/promote-2026.9.0([3b3539b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3b3539bff51146bd8f8ae39e3d4fe0b59a7140ad))

- Merge pull request #179 from FABBricate-IT-Solutions/chore/release-2026.8.66([dee3640](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/dee3640d0b45d47d7b1182d8a7e06cd82722e933))

- Merge pull request #224 from FABBricate-IT-Solutions/fix/hacs-app-changelog-staging([8474bc4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8474bc41981dc2b238b7fb0efe6e4f2466fe00db))

- Merge pull request #223 from FABBricate-IT-Solutions/fix/floor-status-climate-speech-staging([c6868b7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c6868b7cabecf0d2839a33e1ae1e98bae1ae4d96))

- Merge pull request #222 from FABBricate-IT-Solutions/fix/assist-speech-refine-staging([09128be](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/09128be42664a6c88be046b640375fdb5fd22bf1))

- Merge pull request #221 from FABBricate-IT-Solutions/feat/llm-providers-staging([057bf68](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/057bf68b662593fa893059e35950e354ff80dcfb))

- Merge pull request #220 from FABBricate-IT-Solutions/feat/wizard-settings-staging([3e26cca](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3e26cca1747774ee69ddd5ee0c12770a4240792f))

- Merge pull request #218 from FABBricate-IT-Solutions/feat/calendar-no-double-speak([4acc0dd](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4acc0ddc5524fd4a43400c56bb5b9ede33c2063f))

- Merge pull request #217 from FABBricate-IT-Solutions/feat/trainer-assist-tools([6245ffd](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6245ffd2a9390ecc6235551eb0ce2fb2ad661236))

- Merge pull request #216 from FABBricate-IT-Solutions/cursor/operator-ux-fixes-5caf([cb2f859](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cb2f8590f2b3f3141dccaec1259cc1d15b8f21c2))

- Merge pull request #215 from FABBricate-IT-Solutions/cursor/operator-gaps-5caf([6ab7494](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6ab7494c2b76bddf0d9b335049366bf9de1a89c1))

- Merge pull request #214 from FABBricate-IT-Solutions/cursor/operator-settings-home-5caf([5da0d0a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5da0d0a56c52c52e3f5ee448b5fbecb29115bbdf))

- Merge pull request #213 from FABBricate-IT-Solutions/cursor/python-dup-cleanup-5caf([dc5ee32](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/dc5ee321ded9cde41b2531d073bc7fa9b28b1cb4))

- Merge pull request #212 from FABBricate-IT-Solutions/cursor/engine-speech-render-5caf([569ce95](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/569ce95e8bf13f689f450b56b64fe450df64291e))

- Merge pull request #210 from FABBricate-IT-Solutions/cursor/speech-snapshot-5caf([e46b8d1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e46b8d18e542602a6532773b0d9e9ef652ff4c28))

- Merge pull request #211 from FABBricate-IT-Solutions/cursor/engine-assist-api-5caf([a5c55b4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a5c55b45acc90612e25b68388552662c04612a59))

- Merge pull request #209 from FABBricate-IT-Solutions/cursor/quiet-ack-eligible-5caf([6fb76d3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6fb76d381d359b086ecd978276bf4e4e5f98f690))

- Merge pull request #208 from FABBricate-IT-Solutions/cursor/engine-refine-api-5caf([66c6e6f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/66c6e6fb05e29f280713dda50d65e1ff52972f1d))

- Merge pull request #206 from FABBricate-IT-Solutions/cursor/engine-only-assist-llm-2a85([1561d24](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1561d2427929b2f3eb29c43c4d0de1db51eaedbb))

- Merge pull request #207 from FABBricate-IT-Solutions/cursor/python-rust-boundary-plan-5caf([a31b478](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a31b478cda7f09e557a90277ed78c47260e1b0fb))

- Merge pull request #205 from FABBricate-IT-Solutions/cursor/operator-ui-shadcn-5caf([8800e09](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8800e0976d1248ac226c474f8ac1663116ce75a9))

- Rules path-grid from #204 into operator UI refresh([8dbc128](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8dbc128c6e905d0759020900bb4db48826a86e89))

- ADR 0001 docs from #198 into operator UI refresh([08d1e4e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/08d1e4ed72fdc935d000e0ef10b347abf9a3f8d7))

- Merge pull request #201 from FABBricate-IT-Solutions/cursor/match-controls-overlay-5caf([6359a9d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6359a9d4c5a4ab822bd49ec354d59db900c1fadb))

- Merge pull request #194 from FABBricate-IT-Solutions/fix/image-security-updates([8b34da0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8b34da020ab4b84c4d07d80d2204316c5fbde693))

- Merge pull request #191 from FABBricate-IT-Solutions/fix/assist-follows-lab([fd23225](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fd232255e1fb6e4e417e2f1497c9f88f00609050))

- Merge pull request #188 from FABBricate-IT-Solutions/feat/named-room-status([6c3e49e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6c3e49ee24d752040195997fdd4c0fb48cf6ab7d))

- Merge pull request #185 from FABBricate-IT-Solutions/feat/allow-llm-tools([aaf332a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/aaf332a269d169b9c841dc06535940ae8504feca))

- Merge pull request #181 from FABBricate-IT-Solutions/fix/llm-chat-stream([4d1e066](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4d1e066f97f201ca0dd8e119dc951c05491dcdd1))

- Merge pull request #180 from FABBricate-IT-Solutions/feat/llm-tts-streaming([b240f52](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b240f52d93239313b8e7f6b1aa66877917f9d949))

- Merge pull request #178 from FABBricate-IT-Solutions/fix/close-conversation-after-execute([219a432](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/219a43215b708aa17a584b1cb86c4ae0235bf253))

- Merge pull request #177 from FABBricate-IT-Solutions/chore/release-2026.8.65([459ab37](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/459ab37fb10aed7929976b049357e15f264226f2))

- Merge pull request #176 from FABBricate-IT-Solutions/fix/parity-all-langs-ci([a241e2b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a241e2bdd3c14f9039b6f81d73b6771c3a94feed))

- Merge pull request #175 from FABBricate-IT-Solutions/chore/release-2026.8.64([c17daa1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c17daa17560ea9c026ceba477b199fbfe96dc61d))

- Merge pull request #174 from FABBricate-IT-Solutions/fix/locale-clarify-speech([5584f4b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5584f4b7122a237a6dbfb3f05ef3beba48859ec9))

- bump @types/react-dom in /web in the npm-patch group([d8c65ef](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d8c65efe8774e86a3303c1ae32e823780cfc768e))

- bump uuid from 1.24.1 to 1.26.0 in the rust-minor group([c744247](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c7442479d391bb0b7e1e0decb03cff7606bcb6ea))

- Merge pull request #171 from FABBricate-IT-Solutions/chore/release-2026.8.63([9ea5e41](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9ea5e417f71131e4063ac2b6c09c72465f8ddef3))

- Merge pull request #170 from FABBricate-IT-Solutions/fix/yarn-canned-if-permission([584f578](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/584f578837b07a38d3e38a0dd9a805b18d22ed43))

- If Gemma still offers a story or joke, speak a canned one instead of asking permission.([ea2fc4e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ea2fc4e875d8e275f9c7ee7de3f004736a27d00f))

- Merge pull request #169 from FABBricate-IT-Solutions/chore/release-2026.8.62([855be93](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/855be936a4da49b7f9ac5fec9925be7f60932479))

- Merge pull request #168 from FABBricate-IT-Solutions/fix/story-and-calendar-session([bec3e4f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bec3e4ff3a7ead096e51484ccd04d59bbc64e84d))

- Tell a requested story immediately and keep hyphenated calendar titles off the last kitchen player.([8265969](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/82659696bbe927d28344f0a3098c5bf6930aa080))

- Merge pull request #167 from FABBricate-IT-Solutions/chore/release-2026.8.61([9239bbb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9239bbbe2468d50e024127ee23625819e87f327f))

- Merge pull request #166 from FABBricate-IT-Solutions/fix/ha-ui-follows-system-language([fdbe34b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fdbe34bfe80497b0f44e1c66339351ae70109268))

- Keep rustfmt and the operator-language catalog keys CI-clean.([ceb9379](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ceb937907333dc091d7c61d8aec00dd3a4fb9ebc))

- Advertise every Assist locale and set operator chrome from Settings or KLAR_UI_LOCALE.([412a0a7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/412a0a7575af3b64862fb430a2914f7999798995))

- Set Wohnzimmer percent brightness and keep operator chrome on the HA language.([66bf341](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/66bf3417897a27d4a9894f79d3db6071f6609825))

- Keep HA integration chrome on the system language.([a3020dc](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a3020dc10ed07195b46701e0994af40905a73a4b))

- Merge pull request #165 from FABBricate-IT-Solutions/fix/live-story-joke-calendar([228964d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/228964d8b14665131f9151a478451d792801c9ec))

- Keep Guten Morgen from listing tomorrow's calendar.([b20a95b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b20a95ba86f32b7747c735fd811687eda68fde2d))

- Tell stories, list tomorrow, keep calendar titles.([6317f11](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6317f119d731b436beb87e7bcb2eda2a7695c24f))

- Merge pull request #164 from FABBricate-IT-Solutions/chore/release-2026.8.60([00c8158](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/00c8158a73e2388c69db77e76e9953e1c43b9021))

- Merge pull request #163 from FABBricate-IT-Solutions/fix/live-heat-not-session-volume([8d68136](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8d68136317959d617711363693cc2dc8d6d94890))

- Stop heat setpoints from becoming satellite volume.([6289a86](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6289a8678e09a029326d0e165e60eb42177d88d4))

- Merge pull request #162 from FABBricate-IT-Solutions/chore/release-2026.8.59([afe2016](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/afe2016d659048b4b031cd3b1de05c5875edc477))

- Merge pull request #161 from FABBricate-IT-Solutions/fix/live-heat-not-satellite-volume([f0c7a65](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f0c7a65cd523dec7801176e00b46376093be9591))

- Keep named-room music targeting off heat and volume parses.([d3add3a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d3add3aa3e3c658360c79b98150623ca03152b08))

- Merge pull request #160 from FABBricate-IT-Solutions/chore/release-2026.8.58([a1d6dd6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a1d6dd68e5030d8ccf46520ff4461693d1ee3e42))

- Merge pull request #158 from FABBricate-IT-Solutions/docs/runtime-architecture-map([147dabc](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/147dabc16a956afb8934e087b6b4e3317a3fa436))

- Merge pull request #159 from FABBricate-IT-Solutions/chore/release-2026.8.57([4c99aa7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4c99aa73d529b6c3ff24bf2c1c529ae5d5e76f73))

- Merge pull request #157 from FABBricate-IT-Solutions/fix/live-kitchen-named-room-not-satellite([e93524f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e93524f733803c31952720b491e9c70c156c5eea))

- Prefer the named-room music player over a global MASS satellite.([660d0aa](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/660d0aa44fc1a388b62e1444a20a218ac1a01861))

- Merge pull request #156 from FABBricate-IT-Solutions/chore/release-2026.8.56([41169c4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/41169c4d681ff81035cb3b4dfd8a1138784d3586))

- Merge pull request #155 from FABBricate-IT-Solutions/fix/live-kitchen-alexa-honest-tv([f3367db](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f3367db78a12e7a4ce4303fd286e70f4e5a40e4b))

- Merge pull request #154 from FABBricate-IT-Solutions/chore/release-2026.8.55([d1e2025](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d1e2025bf3c8a122b97fa22c6b501e48ba37698a))

- Merge pull request #153 from FABBricate-IT-Solutions/fix/live-heat-dim-kelvin-music-tv([99f0e4f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/99f0e4f5763bf434d59826e6e3df16216a02b642))

- Merge pull request #152 from FABBricate-IT-Solutions/chore/release-2026.8.54([8a5f724](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8a5f724f3eae7ee1d8237a8327b08a0ae0854267))

- Merge pull request #151 from FABBricate-IT-Solutions/fix/live-clock-tv-followup([1db0ddc](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1db0ddc5e45c6d1c19a0fd099c70f29a38eaa2ed))

- Merge pull request #148 from FABBricate-IT-Solutions/chore/release-2026.8.53([91b458c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/91b458c539a47d2613c661e98afe3805145d0df1))

- Merge pull request #149 from FABBricate-IT-Solutions/fix/release-cut-protected-main([0355ebc](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/0355ebc79a1d7b3311f24fb6bf4db561ae4eea9b))

- Merge pull request #147 from FABBricate-IT-Solutions/feat/conversation-suite([162b115](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/162b115d06bcf6ad035cb4f424380c0be65199c2))

- Merge pull request #146 from FABBricate-IT-Solutions/chore/release-2026.8.52([ef507be](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ef507bed8461c930e9b34889fa5d51b76ae517ae))

- Merge pull request #145 from FABBricate-IT-Solutions/fix/llm-story-context([afd3032](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/afd3032481135cd2997fad59d6798f12b5b0efd3))

- Merge pull request #144 from FABBricate-IT-Solutions/chore/release-2026.8.51([be0bbf4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/be0bbf4879351d1cf1af51876977b4fa074dc07a))

- Merge pull request #143 from FABBricate-IT-Solutions/fix/llm-chat-followup([08bf4d8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/08bf4d8ade981df90782a03f57f6088a0334f14a))

- Merge pull request #142 from FABBricate-IT-Solutions/chore/release-2026.8.50([db74e5a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/db74e5a2fb552a76e16dd09d39ee012c7b297afd))

- Merge pull request #141 from FABBricate-IT-Solutions/staging([01c20fb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/01c20fb91756ed85cc34dfa4fc39f270ae26d1ea))

- Merge pull request #140 from FABBricate-IT-Solutions/fix/followup-es-wieder-ein([fcb456d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fcb456de79d67950802c901265685542150ce3b1))

- Merge pull request #138 from FABBricate-IT-Solutions/staging([015c512](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/015c51201d6f420c9a4e5b446dfe6e078776c906))

- Merge pull request #137 from FABBricate-IT-Solutions/chore/remove-figma-code-connect([4801af1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4801af18e70189453c6f77be00cbfab127a8d2a9))

- Merge pull request #135 from FABBricate-IT-Solutions/staging([26dbf45](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/26dbf45348596f7c1819e36709282cfef0de2733))

- Merge pull request #134 from FABBricate-IT-Solutions/release/promote-2026.8.48([067e437](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/067e4374823361deecc875b8852877f7c863735d))

- sync main 2026.8.47 into staging([8995672](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8995672ee27e087f3f045654be61f08e211abda6))

- Merge pull request #133 from FABBricate-IT-Solutions/feat/operator-ui([6f3fcc7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6f3fcc7a762fcb5fa92e4b39eef040fc474467b0))

- keep 2026.8.47 over stale staging quiet-ack([2c932cf](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2c932cf527935f4933bf627576469379a0217fc1))

- Merge pull request #123 from FABBricate-IT-Solutions/feat/quiet-ack([1293ceb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1293ceb598e92ed874b2650997eaf3499218b3e5))

- Merge pull request #131 from FABBricate-IT-Solutions/feat/native-script-assist-langs([22790b6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/22790b67253bd0fb01cb4c19b9253164f2033fb9))

- Merge pull request #128 from FABBricate-IT-Solutions/feat/calendar-delete-move([9309f0f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9309f0f937be6817c97312e9330802678556bd9a))

- bump vite from 8.2.1 to 8.2.2 in /web in the npm-patch group (#127)([ce2e05d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ce2e05d1f07ab98ffdb3abd0fe78101ab9eac2e4))

- Merge pull request #124 from FABBricate-IT-Solutions/feat/quiet-ack-main([f6acd98](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f6acd98703604c3b9a0ce64b25afb4f809242556))

- Merge pull request #122 from FABBricate-IT-Solutions/docs/clarify-hacs-vs-app([81d6d1c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/81d6d1c4abd4344f2f2f98a72628b2b37b9d4972))

- Merge pull request #121 from FABBricate-IT-Solutions/fix/bundled-musl-engine([4539012](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4539012094d9e5386443f5e907dc6d53f4caebbd))

- Merge pull request #120 from FABBricate-IT-Solutions/fix/archive-klar-binary([2ca0d44](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2ca0d448f477265ef4cf0cb9c117c93d14852992))

- Merge pull request #118 from FABBricate-IT-Solutions/drop/armv7([569a6b8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/569a6b83bcdd547630e9ac8634434730318c816d))

- Merge pull request #117 from FABBricate-IT-Solutions/fix/tts-stream-umlaut([428a2ef](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/428a2ef773bcdbbe9f8860fa8cc10d8e91817155))

- Merge pull request #116 from FABBricate-IT-Solutions/release/promote-personality([a5c0a13](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a5c0a13ec1076449ec8df6c2532b9b7f4a18ba57))

- Merge remote-tracking branch 'origin/main' into release/promote-personality([21125cc](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/21125cc97e6e4926ae17e44f4915cc82705401e2))

- Merge pull request #114 from FABBricate-IT-Solutions/release/promote-nlu-rag([97f6031](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/97f603162ac57d1cfa04b4753ccef581e5bbb2f8))

- Merge remote-tracking branch 'origin/main' into release/promote-nlu-rag([616020b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/616020b3cc1ad42d7046c237100b01ae1d1f7f36))

- Merge pull request #112 from FABBricate-IT-Solutions/release/promote-wiedergabe([3c65d9b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3c65d9bcf0feef059b5d2ca5d1a111dd4e1f905c))

- Merge remote-tracking branch 'origin/main' into release/promote-wiedergabe([35b1aff](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/35b1affb4d92f6d080f5f8594494d57451cfe6e6))

- Merge pull request #110 from FABBricate-IT-Solutions/release/promote-staging([4cbc4fa](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4cbc4facb509107250789472d0e96010abd566f1))

- Merge remote-tracking branch 'origin/main' into release/promote-staging([4bf2dec](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4bf2dec4a89ff348bf228a1a9bf4652a49d5140d))

- bump uuid from 1.24.0 to 1.24.1 in the rust-patch group (#105)([828d1cb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/828d1cb462e21644b63ab3779cc88a3fe41399c1))

- Merge pull request #103 from FABBricate-IT-Solutions/release/promote-staging([4e5b3c6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4e5b3c682ee7f2dd3ca39a15ef0146dc6bfd58ce))

- main 2026.8.32 into staging for the stable cut([d572987](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d57298791c7c8fc72ca9af38d24b5355af106ab0))

- Merge pull request #97 from FABBricate-IT-Solutions/feat/simple-channel-switch-main([b106172](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b1061725570f205f4df3ff1b32baeff5faf5b089))

- Merge pull request #115 from FABBricate-IT-Solutions/feat/personality-refine-jarvis([4a23e27](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4a23e279e3d58e91cf77ef764cf298142df3215b))

- Merge pull request #113 from FABBricate-IT-Solutions/fix/nlu-rag-no-spoken-tools([0531b50](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/0531b502f04adf52d5be3e4db8c81fd18f1cc014))

- Merge pull request #111 from FABBricate-IT-Solutions/fix/wiedergabe-stopp([b55f9f4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b55f9f4a9e69859bf5a17a1ebd194e4e2780c9f8))

- Merge pull request #109 from FABBricate-IT-Solutions/feat/v2-locale-catalog([4e23f13](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4e23f135a0c8a2382026f1078afa072ca844a088))

- Merge pull request #101 from FABBricate-IT-Solutions/fix/options-labels-and-panel([10beb42](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/10beb425bf0353040b8bc43efdb677a800164a49))

- Merge pull request #100 from FABBricate-IT-Solutions/fix/lovelace-dashboard-id([d95790c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d95790cbb479656e41871f35a45129c9a2f23735))

- Merge pull request #99 from FABBricate-IT-Solutions/feat/channel-anytime-and-language([4da4fff](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4da4ffffcc4fe51c1044075156706c06752b5d8c))

- Merge pull request #98 from FABBricate-IT-Solutions/feat/simple-channel-switch([e02f1af](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e02f1afb1a97364afe5e1a219b7bbe45590f610c))

- Merge pull request #96 from FABBricate-IT-Solutions/fix/staging-rc-notes([3368cb1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3368cb17df6b449b13fdcf7624fe79f414a8aad6))

- Merge pull request #95 from FABBricate-IT-Solutions/fix/gitleaks-re2-regex([5043222](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/504322264c3f07586a8b1cb918289e0c5627198b))

- Merge pull request #94 from FABBricate-IT-Solutions/fix/staging-security-gates([ab3cac6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ab3cac67ac3f40cafda8db5c59fbff8e3f1d38ab))

- Merge pull request #93 from FABBricate-IT-Solutions/fix/staging-workflow-startup([f9ae579](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f9ae579e774098afc2d46596c65fb7f94654ea45))

- Merge pull request #92 from FABBricate-IT-Solutions/feat/staging-full-home-rc([c765d4c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c765d4c5c27ab1d7e215f46a1cc8f84f09b84370))

- Merge pull request #84 from FABBricate-IT-Solutions/release/2026.8.29([cb1e07f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cb1e07fda308a68e3f9857321d389c816843a2e0))

- Merge pull request #83 from FABBricate-IT-Solutions/fix/area-climate-fallback([d28d7b3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d28d7b3092f7da85f1234168c76f542f464482b9))

- Merge pull request #82 from FABBricate-IT-Solutions/release/2026.8.28([bc86da9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bc86da9d4da56b167716e8a2489fdc261e0ddb03))

- Merge pull request #81 from FABBricate-IT-Solutions/fix/live-query-sync([faf7cee](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/faf7ceeae83f57432d52d650eab64f5e4085b18d))

- Merge pull request #80 from FABBricate-IT-Solutions/release/2026.8.27([7b6d485](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/7b6d485bcabf64c93667097891fe2df97e335cc9))

- Merge pull request #79 from FABBricate-IT-Solutions/fix/accept-trace-tokens([0457662](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/045766211c711907793908d788794cf4a58924e9))

- Merge pull request #78 from FABBricate-IT-Solutions/release/2026.8.26([d6ed257](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d6ed257215b92ce3d57ddbba4d98faf94e4133b6))

- Merge pull request #77 from FABBricate-IT-Solutions/feat/v2-nlu-platform([24bcb17](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/24bcb17ed76c326971db80b9002c1a63eae47759))

- Merge pull request #76 from FABBricate-IT-Solutions/release/2026.8.25([86a05ce](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/86a05ce43e1cc37390acc8f82fe70616c0743edf))

- Merge pull request #75 from FABBricate-IT-Solutions/fix/music-assistant-hardening([4ff1deb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4ff1debc270605413e798a630acc6c9eb41c7ec3))

- Merge pull request #74 from FABBricate-IT-Solutions/release/2026.8.24([a612479](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a612479bec49fe9af8cfb9a11d46e009ff2f5e1e))

- Merge pull request #73 from FABBricate-IT-Solutions/feat/asr-fuzzy-matching([f428df7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f428df71421e0ed4b8164abd3116a76018fa8be2))

- Merge pull request #72 from FABBricate-IT-Solutions/release/2026.8.23([e69dfd9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e69dfd9d25b388e066acb8f20264a0dfea3bddd6))

- Merge pull request #71 from FABBricate-IT-Solutions/feat/music-assistant-voice-control([9ef246e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9ef246e6b4a65720561850442915bf7b2e104494))

- Merge pull request #70 from FABBricate-IT-Solutions/release/2026.8.22([9bc7d7a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9bc7d7ab209f3cb2ccaa7bd2e5caa343abb7d752))

- Merge pull request #69 from FABBricate-IT-Solutions/release/2026.8.21([a9049b9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a9049b951290253bb809839a727a147398e4607d))

- Merge pull request #68 from FABBricate-IT-Solutions/release/2026.8.20([0fd0584](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/0fd05840f5fd9c85d877db5b9d1329f04ccdd3c0))

- Merge pull request #67 from FABBricate-IT-Solutions/release/2026.8.19([537ef8d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/537ef8da733ce94c5fbba50a8b9c6a6877c319a6))

- Merge pull request #66 from FABBricate-IT-Solutions/refactor/rust-structure-docs([bc89637](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bc89637f56649d8b93f0e4cdb9c100dc2026913d))

- Merge branch 'main' into refactor/rust-structure-docs([13137cb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/13137cbed9640ee7fe9d345dbc9c45f61b9c1694))

- Merge pull request #58 from FABBricate-IT-Solutions/fix/auth-action-target-overlay([09eead6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/09eead67210fb3082e0de27d6fdfd3aa4c84c0e6))

- Merge pull request #56 from FABBricate-IT-Solutions/fix/addon-entity-display-names([f4d0080](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f4d0080392145a4d3a18220174266e26dc73dd0b))

- Merge pull request #55 from FABBricate-IT-Solutions/release/2026.8.13([b6acc30](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b6acc30b0969e16c59c5c6bfd43f02680686936e))

- Merge pull request #54 from FABBricate-IT-Solutions/fix/climate-speech-refine-voice([f98ee19](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f98ee19596636635e5dca16775f9320edf02ce1c))

- Merge pull request #53 from FABBricate-IT-Solutions/release/2026.8.12([cc174f9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cc174f9b17703d36080ff23111b76cfc5a4c35c3))

- Merge pull request #52 from FABBricate-IT-Solutions/fix/news-nudge-formal([f38c279](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f38c279d17936ca0fe4bb834f7db297b4bbfa360))

- Merge pull request #51 from FABBricate-IT-Solutions/release/2026.8.11([85ae9ac](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/85ae9ac4d5939a4288d0d358fc4ba8dc87e3d5ea))

- Merge pull request #50 from FABBricate-IT-Solutions/feat/llm-speech-refine([22f1232](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/22f12325e470862f13b20acc2299e9083683d99b))

- Merge pull request #49 from FABBricate-IT-Solutions/release/2026.8.10([35c646a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/35c646a9c9e8286982e9875e593fe0645c3b869e))

- Merge pull request #48 from FABBricate-IT-Solutions/feat/news-briefing([284689b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/284689b3d2f9686c6a897112c89c30a535457973))

- Merge pull request #47 from FABBricate-IT-Solutions/refactor/packs-and-home-policy([0ca5ff0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/0ca5ff0ac60c7542813d6784642e2113100a8e0a))

- Release 2026.8.3 (#39)([c752170](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c7521701e1f46880f7b38aec6456608f65033104))

- Potential fix for code scanning alert no. 8: Cache Poisoning via code injection (#38)([8107a9c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8107a9c049c51107d2da54918eb04e3e7173390e))

- bump tower-http from 0.6 to 0.7([3abad97](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3abad97e4ddde88df77c2ea6b615f0bbb33ecec7))

- Update dependabot.yml([3edeb08](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3edeb087198c5df40c29022235de65a652dc04b8))

- Publish Klar NLU with CI, security scans, and multi-arch builds.([e4801a5](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e4801a53878c5b65a8cf7f940a0f8283cc692e81))


### Refactor

- move area_slots so compound.rs stays under 500 lines([6ae422b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6ae422bd99c7497c4b464881faf8dc7cd1cfd7cc))

- move prefer.rs tests out so the 500-line gate stays green([7452627](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/74526273bc44c7993a979ffdb5974472f6ecb106))

- split media word helpers so parse stays under 500 lines([8121b64](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8121b643fa186ffc696b47d64776a5dc019e7000))

- reorganize Rust engine layers and docs([93cd147](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/93cd147a1af764ba034e6da7cbad3fc0ee9d451c))

- extract language packs and home policy from the parse pipeline([483d93e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/483d93e9379da6e1ff5c33afefe1b1c1c7d3838b))


### Styling

- rustfmt LLM usage types([b88f533](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b88f533a6b7f4127b5b26a4e48916301d6f4e29f))

- rustfmt trainer_reads and units([6957059](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/695705920d93bc4e9212086873775355ef3f0eba))

- use matches! for same satellite area hint([12be037](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/12be037af5a76aa9e57377138daee06068365022))

- rustfmt generated packs and NLU sources([02bb7ef](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/02bb7efb766d2c04615f8f414cbe2632c67b9fc2))

- rustfmt household weather calendar guard([a5fe09a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a5fe09a913ca74f80f66b5a59a556bf385261a87))

- rustfmt the floor-status parse test([7d4df2f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/7d4df2f915b8fa5893bd32d3531829bd25b1e201))

- rustfmt LLM and voice changes([3af48e5](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3af48e5ab4037f92ef8cd91151e0611cd2b43364))

- rustfmt the backup test fixture([7cfd534](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/7cfd53455621d2917d3ef98b3fa12ce67793361b))

- rustfmt leftover operator-gap sources([e4bcd73](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e4bcd73d747d4a7b7d21522107e6eb270e13ead8))

- keep parse module tests after public items([c763050](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c763050e655b6e2d95a0c07904659e33abb1161b))

- use is_ascii for match catalog contract check([0a2b10e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/0a2b10ec60c285b3254efc91a25cdf8c1c6e8b1f))

- rustfmt household weather calendar guard([b232309](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b2323093811c1da0201a16d600414e34b3331273))

- rustfmt the floor-status parse test([f79c53e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f79c53ef9602656e43bba303d77a1464c73768d6))

- rustfmt media helpers([23ac6a1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/23ac6a188888bd657ff31256bc26466cb278f04c))

- rustfmt climate speech tests([8dec09b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8dec09b6ffcb29540bdbca78237be4f6a30d7663))


### Testing

- load weather_forecast in the executor harness([ec9f62a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ec9f62a870d1ab196bdd1719de0948d51c72f48b))

- load dispatch_timer in the executor harness([23cc243](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/23cc243e2324c48d58d4a40db5b146baa9a9e21b))

- treat What's the weather as household, not OOD([802905d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/802905d4c52246c8f7c563be074a6b8c3125e568))

- mock entity_registry when loading dispatch([6342647](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6342647c26681b8e24628c03a40ab285e7d120a2))

- cover schalte das Wohnzimmerlicht an([fd455ea](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fd455ea5acb3a5af2b59a6a73f91fdf263b0ea6d))

<!-- generated by git-cliff -->

## [2026.10.3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.10.2-staging.26f701f...2026.10.3) - 2026-10-04



### Other

- Merge pull request #284 from FABBricate-IT-Solutions/staging([b1c467f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b1c467f12a1454713ac2e35874661c8a0c0ee0cd))

## [2026.10.1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.10.0...2026.10.1) - 2026-10-04



### Other

- bump brace-expansion from 5.0.9 to 5.0.12 in /web([a2efb85](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a2efb853c3f8b3a593186b94660c6017a02e3452))

- bump brace-expansion from 5.0.9 to 5.0.12 in /web([e17711a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e17711a4310f28867166be45d1d7ca6d8ce45c52))

- bump ip-address from 10.7.0 to 10.7.3 in /web([af5de6d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/af5de6dba1f500c567e619cc40610afef2744adb))

- bump ip-address from 10.7.0 to 10.7.3 in /web([e542fc4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e542fc40897dcfde13a759baa2606f7d22e4c326))

- bump fast-uri from 3.1.7 to 3.1.8 in /web([a7e4f4c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a7e4f4c2c4e30b1f72e1e217c8a76121f1bca49b))

- bump fast-uri from 3.1.7 to 3.1.8 in /web([70d1ce9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/70d1ce90312d009bcfc6bbe8005aed77066ccdc5))

## [2026.10.0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.9.11...2026.10.0) - 2026-10-04



### Other

- bump the npm-minor group in /web with 2 updates([2fb41d0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2fb41d0c65af4ff5b0207dc6ef720098d535bc27))

- bump the npm-minor group in /web with 2 updates([d1ca1e0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d1ca1e0690d82c1a7b9e29a2386e5d404f5cf424))

- bump vite from 8.3.0 to 8.3.1 in /web in the npm-patch group([cda77aa](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cda77aa6bcaf31f2515e261af0ddf3a8267182a2))

- bump vite from 8.3.0 to 8.3.1 in /web in the npm-patch group([5f1536e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5f1536e352ea0d5300e175e67f145762b16ebb73))

- bump thiserror from 2.0.20 to 2.0.21 in the rust-patch group([eb6b605](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/eb6b6059cedf7865a66ffb8d841e5c943cd00b33))

- bump thiserror from 2.0.20 to 2.0.21 in the rust-patch group([cbe6fbc](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cbe6fbcc0e4805598bebbc96cb838b7d15ca790a))

- Merge pull request #265 from FABBricate-IT-Solutions/dependabot/cargo/rust-patch-722c7a5dc4([58dc96a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/58dc96af1b0dce34dd8e72df6e4b6a5d9eb338f6))

- bump clap from 4.6.6 to 4.6.7 in the rust-patch group([032ead4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/032ead46e941b6aa40952cd328a39c8e03e8ca2a))

- Merge pull request #266 from FABBricate-IT-Solutions/dependabot/npm_and_yarn/web/npm-minor-7bee64aca0([da0793f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/da0793fd90807b05992483a549536d2b92022f28))

- bump the npm-minor group in /web with 2 updates([35b7b11](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/35b7b117224314bb79bdea9c921ba1e2687bdd6e))

## [2026.9.11](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.9.10...2026.9.11) - 2026-09-16



### Bug Fixes

- raise parse timeout and stop false mid-sentence status([c844436](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c8444365789b59585bb2bb75149dfa8320bc902a))

- raise parse timeout and stop mid-sentence status replay([1039fb1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1039fb190f27a53030f99279165f792049f7a9e5))


### Other

- Merge pull request #262 from FABBricate-IT-Solutions/dependabot/npm_and_yarn/web/npm-minor-d15a6bbb73([27e6479](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/27e64795529b379fb12a6e07e6701efbe9113981))

- merge main (rustls + parse fixes) into npm-minor([89fe881](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/89fe881472525ccfcd38df981392b917f43bf22c))

- Merge pull request #263 from FABBricate-IT-Solutions/fix/parse-timeout-and-false-status([e2dc377](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e2dc37722e63934bd0fe53e1d0b79beb016a545b))

- merge main into npm-minor; keep cn 0.2.6 and minor bumps([6c1139a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6c1139aec37198bc4bcee2441795d7333ff03357))

- Merge pull request #261 from FABBricate-IT-Solutions/dependabot/npm_and_yarn/web/npm-patch-5812b47994([fdbe4c5](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fdbe4c5e8732ae78bd8d338b04a515e410d4fced))

- bump cn from 0.2.5 to 0.2.6 in /web in the npm-patch group([91aa9b9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/91aa9b9a66adbf3e845718490b44395700989b0b))

- Merge pull request #260 from FABBricate-IT-Solutions/dependabot/cargo/rust-patch-98b7f37da0([12c17a2](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/12c17a2fdb52ab0bac2e19011d409d6a19334fce))

- bump uuid from 1.26.0 to 1.26.1 in the rust-patch group([379b00e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/379b00ec665be321545e4bcbda214ad1a47f27c5))

- bump the npm-minor group in /web with 6 updates([771e840](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/771e840867c4e631455da2f6e166d6f6e44b3419))

## [2026.9.10](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.9.9...2026.9.10) - 2026-09-12



### Bug Fixes

- keep hallway and timer phrases from matching weather stems([cd8a8e8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cd8a8e8633d4962f25fac7c654d52a1a3bf7fb18))

- drop banned bitte token from weather query stop list([6e34a59](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6e34a59cc0f1bf6c41efdec86b0b977814f854aa))

- keep shopping lists and OOD weather phrases out of weather lex([02c2ed3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/02c2ed3bec39026546f55ec503b4f66cdccd0a11))

- leave generated weather lists to the pack generator([b70aa0a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b70aa0aa6278f67c794467f355b7c9622795f2f9))

- use Range::contains for night hours([b29933a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b29933a6a8157f6f248e40a5dfa20b3dce1081c7))

- keep handwritten de and en packs under 500 lines([6c52d5e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6c52d5e3742a33b534d1033cdf13fccb61ceda12))


### Features

- **weather:** parse and speak forecast in every locale([2623e62](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2623e62cb762a79c322797cd728a2b6856b9f773))


### Other

- Merge pull request #258 from FABBricate-IT-Solutions/feat/weather-all-langs([8913939](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8913939292023fafdc8aa42a360e9ff6f64bb4d6))


### Testing

- load weather_forecast in the executor harness([ec9f62a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ec9f62a870d1ab196bdd1719de0948d51c72f48b))

## [2026.9.9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.9.5-staging.1e6593b...2026.9.9) - 2026-09-11



### Bug Fixes

- keep staging Lotse UI when promoting to main([a89fbc8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a89fbc824cc264bfcb8d925fa70da90ca275cbad))


### Other

- Merge pull request #255 from FABBricate-IT-Solutions/release/promote-2026.9.9([8891bd6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8891bd68c64565b519c239d1f7b9a95168a7d6b4))

- accept staging product over main 2026.9.8([4a9db2e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4a9db2ec054d3dd0c5e44f1f349c47e3ccc11ca0))

## [2026.9.8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.9.7...2026.9.8) - 2026-09-07



### Other

- Compact Lotse on mobile so the chat keeps the screen (#239)([412108a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/412108a46b719769ab5a9942dbdc5adf7c4f5590))

## [2026.9.7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.9.6...2026.9.7) - 2026-09-07



### Other

- bump recharts from 3.8.0 to 3.10.1 in /web in the npm-minor group (#236)([5796317](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5796317eb494e56bf3bf64df9d74dea24d195396))

- bump @types/react-dom from 19.2.5 to 19.2.7 in /web in the npm-patch group (#234)([2843919](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2843919682870b03538952dde82adfb47dc54771))

- bump the rust-patch group with 2 updates (#233)([64c715d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/64c715de603a22a551571da7def62edf96daada1))

## [2026.9.6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.9.5...2026.9.6) - 2026-09-06



### Bug Fixes

- add engineOffline to every Assist locale([eb9146f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/eb9146ff13591e4fae6e7ebbe7fec8f57da95538))

- fail closed when custom phrases cannot persist([9dbecdd](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9dbecdd91824ab28c60102501021be01277cac82))


### Other

- Merge pull request #231 from FABBricate-IT-Solutions/fix/custom-phrase-live-store([8be8509](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8be850902cd34588d8fad9bdce77efef4b825ed4))

## [2026.9.5](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.9.4...2026.9.5) - 2026-09-06



### Documentation

- credit Aquila MIT voice suite([ae99f65](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ae99f6515918f7c5957f5d26a405c4e9602ed0c8))


### Other

- Merge pull request #228 from FABBricate-IT-Solutions/docs/credit-aquila-suite-main([bb721c7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bb721c74a85972bd08bcf6e16a282df96419d2e3))

## [2026.9.4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.65-staging.8474bc4...2026.9.4) - 2026-09-06



### Bug Fixes

- keep staging Assist code when promoting to main([684a325](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/684a3254f2c9fde0635b1d677b2452dfc0cc99fc))


### Other

- Merge pull request #225 from FABBricate-IT-Solutions/release/promote-staging([136c27d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/136c27daa457fc74b465501f3b7cba70c7f69098))

- accept staging product over main 2026.9.3([84a77b9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/84a77b99b56feed645c120808896bea1ba0e2a6f))

## [2026.9.3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.9.2...2026.9.3) - 2026-09-05



### Bug Fixes

- apply Debian security updates in the runtime image([4c30cfe](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4c30cfe032286ea8f5373282d2283246d9b9c487))


### Other

- Merge pull request #195 from FABBricate-IT-Solutions/release/promote-image-security-updates([b17384b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b17384b2cace6cc055fe954eb3547b7a5b7ba40c))

## [2026.9.2](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.9.1...2026.9.2) - 2026-09-05



### Bug Fixes

- only skip household weather when a calendar noun is present([3d503d3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3d503d3d3359564d227e564e06fc6f3fe77daebe))

- keep Assist on the Lab plan and show pipeline settings([53fc5bc](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/53fc5bcbe0e9128995ff5f2ff97505fac67fee2f))


### Other

- Merge pull request #192 from FABBricate-IT-Solutions/release/promote-assist-follows-lab([94132aa](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/94132aae94bd4439b5bc2969eecb23bcba439d04))


### Styling

- rustfmt household weather calendar guard([a5fe09a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a5fe09a913ca74f80f66b5a59a556bf385261a87))

## [2026.9.1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.9.0...2026.9.1) - 2026-09-02



### Features

- speak named devices in floor and room status([095bac1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/095bac1f2d7f1a7118ad832304c43f91e09c940d))


### Other

- Merge pull request #189 from FABBricate-IT-Solutions/release/promote-named-room-status([72aeadb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/72aeadbdd84637f642e91c4461f3503ccb002cfa))


### Styling

- rustfmt the floor-status parse test([7d4df2f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/7d4df2f915b8fa5893bd32d3531829bd25b1e201))

## [2026.9.0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.67...2026.9.0) - 2026-09-02



### Features

- let users opt in to Assist tools on the chit-chat LLM([a87a2fa](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a87a2fae58fdac688bbe87ca07296fcabbca28f5))


### Other

- Merge pull request #186 from FABBricate-IT-Solutions/release/promote-allow-llm-tools([6c28793](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6c28793c83f7af6dd60319cbcb3b54e0c848eb4a))

## [2026.8.67](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.66...2026.8.67) - 2026-08-31



### Bug Fixes

- store stream-published flag on speech extra_data([cf6accc](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/cf6accca3328daa067b59b7819793256ffacf804))

- publish LLM tokens into Assist chat([47108f2](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/47108f216287227caf6e95fd9f69d815c6bf6e8c))


### Features

- stream LLM deltas into Assist chat and TTS([fb8d530](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fb8d530a0473a5c66035b50cdfc74406b6398dd5))


### Other

- Merge pull request #183 from FABBricate-IT-Solutions/release/promote-2026.9.0([3b3539b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3b3539bff51146bd8f8ae39e3d4fe0b59a7140ad))

## [2026.8.66](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.65...2026.8.66) - 2026-08-31



### Bug Fixes

- close Assist listen after execute([41491a3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/41491a39b666fe12e660efb15e6b3bc20d874e6c))


### Other

- Merge pull request #178 from FABBricate-IT-Solutions/fix/close-conversation-after-execute([219a432](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/219a43215b708aa17a584b1cb86c4ae0235bf253))

## [2026.8.65](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.64...2026.8.65) - 2026-08-31



### Bug Fixes

- use Option::map for native ceiling fixture tokens([703250e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/703250e13b11581df8e5b765253c49aed2068549))

- close per-language parity gaps and always test all locales([4aa8988](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4aa8988a47adafcbdd53ab419529b172fe480a01))


### Other

- Merge pull request #176 from FABBricate-IT-Solutions/fix/parity-all-langs-ci([a241e2b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a241e2bdd3c14f9039b6f81d73b6771c3a94feed))

## [2026.8.64](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.63...2026.8.64) - 2026-08-31



### Bug Fixes

- speak clarify and guards in the request locale, not German([0c5988b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/0c5988bf8e3ca6a371bfe41f8ef1bb02c4cd2e75))


### Other

- Merge pull request #174 from FABBricate-IT-Solutions/fix/locale-clarify-speech([5584f4b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5584f4b7122a237a6dbfb3f05ef3beba48859ec9))

- bump @types/react-dom in /web in the npm-patch group([d8c65ef](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d8c65efe8774e86a3303c1ae32e823780cfc768e))

- bump uuid from 1.24.1 to 1.26.0 in the rust-minor group([c744247](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c7442479d391bb0b7e1e0decb03cff7606bcb6ea))

## [2026.8.63](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.62...2026.8.63) - 2026-08-29



### Other

- Merge pull request #170 from FABBricate-IT-Solutions/fix/yarn-canned-if-permission([584f578](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/584f578837b07a38d3e38a0dd9a805b18d22ed43))

- If Gemma still offers a story or joke, speak a canned one instead of asking permission.([ea2fc4e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ea2fc4e875d8e275f9c7ee7de3f004736a27d00f))

## [2026.8.62](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.61...2026.8.62) - 2026-08-29



### Other

- Merge pull request #168 from FABBricate-IT-Solutions/fix/story-and-calendar-session([bec3e4f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bec3e4ff3a7ead096e51484ccd04d59bbc64e84d))

- Tell a requested story immediately and keep hyphenated calendar titles off the last kitchen player.([8265969](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/82659696bbe927d28344f0a3098c5bf6930aa080))

## [2026.8.61](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.59...2026.8.61) - 2026-08-29



### Other

- Merge pull request #165 from FABBricate-IT-Solutions/fix/live-story-joke-calendar([228964d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/228964d8b14665131f9151a478451d792801c9ec))

- Keep Guten Morgen from listing tomorrow's calendar.([b20a95b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b20a95ba86f32b7747c735fd811687eda68fde2d))

- Tell stories, list tomorrow, keep calendar titles.([6317f11](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6317f119d731b436beb87e7bcb2eda2a7695c24f))

- Merge pull request #164 from FABBricate-IT-Solutions/chore/release-2026.8.60([00c8158](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/00c8158a73e2388c69db77e76e9953e1c43b9021))

- Merge pull request #163 from FABBricate-IT-Solutions/fix/live-heat-not-session-volume([8d68136](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8d68136317959d617711363693cc2dc8d6d94890))

- Stop heat setpoints from becoming satellite volume.([6289a86](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6289a8678e09a029326d0e165e60eb42177d88d4))

## [2026.8.60](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.59...2026.8.60) - 2026-08-29



### Other

- Merge pull request #163 from FABBricate-IT-Solutions/fix/live-heat-not-session-volume([8d68136](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8d68136317959d617711363693cc2dc8d6d94890))

- Stop heat setpoints from becoming satellite volume.([6289a86](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6289a8678e09a029326d0e165e60eb42177d88d4))

## [2026.8.59](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.58...2026.8.59) - 2026-08-29



### Other

- Merge pull request #161 from FABBricate-IT-Solutions/fix/live-heat-not-satellite-volume([f0c7a65](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f0c7a65cd523dec7801176e00b46376093be9591))

- Keep named-room music targeting off heat and volume parses.([d3add3a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d3add3aa3e3c658360c79b98150623ca03152b08))

## [2026.8.58](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.57...2026.8.58) - 2026-08-29



### Documentation

- add an interactive runtime architecture map([e8aae11](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e8aae119fce178222c663ae0fff1546046d92cfd))


### Other

- Merge pull request #158 from FABBricate-IT-Solutions/docs/runtime-architecture-map([147dabc](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/147dabc16a956afb8934e087b6b4e3317a3fa436))

## [2026.8.57](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.56...2026.8.57) - 2026-08-29



### Other

- Merge pull request #157 from FABBricate-IT-Solutions/fix/live-kitchen-named-room-not-satellite([e93524f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e93524f733803c31952720b491e9c70c156c5eea))

- Prefer the named-room music player over a global MASS satellite.([660d0aa](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/660d0aa44fc1a388b62e1444a20a218ac1a01861))

## [2026.8.56](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.55...2026.8.56) - 2026-08-29



### Bug Fixes

- play kitchen Alexa and refuse non-TV living-room binds([9ac83a1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9ac83a18dfb73836c23b49961176a4876e661717))


### Other

- Merge pull request #155 from FABBricate-IT-Solutions/fix/live-kitchen-alexa-honest-tv([f3367db](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f3367db78a12e7a4ce4303fd286e70f4e5a40e4b))


### Refactor

- move area_slots so compound.rs stays under 500 lines([6ae422b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6ae422bd99c7497c4b464881faf8dc7cd1cfd7cc))

## [2026.8.55](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.54...2026.8.55) - 2026-08-29



### Bug Fixes

- apply heat, relative dim, Kelvin, kitchen play, and honest TV speech([34fdb07](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/34fdb0790f1d4bc98eff98e8090628674dd5fa82))


### Other

- Merge pull request #153 from FABBricate-IT-Solutions/fix/live-heat-dim-kelvin-music-tv([99f0e4f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/99f0e4f5763bf434d59826e6e3df16216a02b642))

## [2026.8.54](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.53...2026.8.54) - 2026-08-29



### Bug Fixes

- keep bare TV on the Fernseher alias, room TV on the living player([66230d3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/66230d3eae16ac957cf19ba8361ae0c97ab3713b))

- keep clock, living-room TV, and kitchen follow-up honest on Assist([278f4cf](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/278f4cfd85a9d2fcbe235df0f0d195060bc24039))


### Other

- Merge pull request #151 from FABBricate-IT-Solutions/fix/live-clock-tv-followup([1db0ddc](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1db0ddc5e45c6d1c19a0fd099c70f29a38eaa2ed))


### Refactor

- move prefer.rs tests out so the 500-line gate stays green([7452627](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/74526273bc44c7993a979ffdb5974472f6ecb106))


### Testing

- treat What's the weather as household, not OOD([802905d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/802905d4c52246c8f7c563be074a6b8c3125e568))

## [2026.8.53](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.52...2026.8.53) - 2026-08-29



### Bug Fixes

- restore last-light seed and stop media from stealing TV or scripts([e7493ed](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e7493edcf8eda9addda353ada0466e9b75e8bdbb))

- rustfmt the suite and keep action.rs under 500 lines([f190499](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f1904995466c378424546a86a1c7b0595ea60460))


### Features

- isolate Assist sessions and land the conversation suite([1111544](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1111544c0f01448aca2169b4ea5bd28255e56888))


### Other

- Merge pull request #147 from FABBricate-IT-Solutions/feat/conversation-suite([162b115](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/162b115d06bcf6ad035cb4f424380c0be65199c2))

## [2026.8.52](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.51...2026.8.52) - 2026-08-28



### Bug Fixes

- satisfy rustfmt, clippy, and the isolated-fallback session test([5748f16](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5748f16c961521b004b5ccd426ccfdd38a52c500))

- give the story LLM prior turns so egal stays on topic([c49a5fd](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c49a5fd272bf5cde73d8fe6ca5758d824ef0eca6))


### Other

- Merge pull request #145 from FABBricate-IT-Solutions/fix/llm-story-context([afd3032](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/afd3032481135cd2997fad59d6798f12b5b0efd3))

## [2026.8.51](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.50...2026.8.51) - 2026-08-28



### Bug Fixes

- keep LLM story replies in chat instead of living-room status([47893b3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/47893b3fdaa11cb87a7c0054d860094f779d2e06))


### Other

- Merge pull request #143 from FABBricate-IT-Solutions/fix/llm-chat-followup([08bf4d8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/08bf4d8ade981df90782a03f57f6088a0334f14a))

## [2026.8.50](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.49-staging.fcb456d...2026.8.50) - 2026-08-28



### Bug Fixes

- keep the last light so "schalte es wieder ein" works after a new wake ([#140](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/pull/140), [#141](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/pull/141))([484f98d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/484f98d304df69c9d4a4873a4c179c991b33d8ee))

### Other

- Merge pull request #141 from FABBricate-IT-Solutions/staging([01c20fb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/01c20fb91756ed85cc34dfa4fc39f270ae26d1ea))

## [2026.8.49](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.48-staging.4801af1...2026.8.49) - 2026-08-28



### Other

- Merge pull request #138 from FABBricate-IT-Solutions/staging([015c512](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/015c51201d6f420c9a4e5b446dfe6e078776c906))

## [2026.8.48](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.47...2026.8.48) - 2026-08-28

### Features

- localize the operator UI for every compiled Assist language ([#135](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/pull/135))([c0cbc09](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c0cbc0963c13faaca434c7ea990075171eeca7ef))
- operator UI follows the integration language instead of a second picker
- add SearchSelect pickers for phrases, policies, and routines
- add a six-step setup wizard overlay
- use hash routes and a rail as the default operator chrome
- persist journal tokens for a privacy-safe heard line
- teach a phrase from a miss on Home and Gespräche
- rewrite Graph as a floor/room/device map plus keyboard list
- restyle Lab to Klar tokens while keeping pipeline and raw JSON
- add a Klar light theme (same Plex, terracotta, and square chrome)
- rename NLU-RAG chrome to house context on miss (engine unchanged)

### Bug Fixes

- keep Supervisor-prefixed app hostnames (`xyz-klar-nlu`) instead of rewriting them to `klar-nlu`
- restore Lab Analyze for parse traces that include tokens and unknown fields
- hide dismissed Mapping leftover cards

## [2026.8.47](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.46...2026.8.47) - 2026-08-28



### Features

- parse Assist STT native script and keep LLM replies in-pack ([#131](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/pull/131))([082296a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/082296a6042aa68ee6f1f79e1dc0100393de8861))


### Bug Fixes

- treat ac as cooling and label parity fixtures more precisely ([e4ab033](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e4ab033fce3c3d951ec2a4fc73011def761b21b7))
- close native-script parity gaps for laundry, unlock, and lists ([4896458](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4896458ce112d8d598958d063b96992e75b05151))
- keep German home-graph tokens out of generated packs ([bed41bb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bed41bb5238d79a9d4d8e862cd104bc2285fb27e))
- keep music nouns off the TV pool and recover island ASR ([94f57d6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/94f57d66526a321a8d177586a38992909bb7c407))
- confine overlay, bundle, and journal files under the data dir ([84e7355](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/84e7355d38d215961546360dd31280422027bc38))


### Other

- require a green pipeline before any PR merge ([#130](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/pull/130))([4975f62](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4975f620fa2d6429ffca2be5c2298fdb1b7caf78))

## [2026.8.46](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.45...2026.8.46) - 2026-08-27



### Features

- list, create, delete, and move calendar events in 67 Assist languages. Follow-ups stay in Home Assistant, so “delete that” and “move it to Friday” work after a list without series, attendees, or reminders ([#128](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/pull/128))([2c57f4e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2c57f4e6caf2a39e51c768caea3563e2b38930b1))


### Other

- Merge pull request #128 from FABBricate-IT-Solutions/feat/calendar-delete-move([9309f0f](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9309f0f937be6817c97312e9330802678556bd9a))

## [2026.8.45](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.44...2026.8.45) - 2026-08-27



### Documentation

- bump rust from 1.97-bookworm to 1.98-bookworm (#125)([af96514](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/af9651497d102188391f16aa7246f6e5af380638))


### Other

- bump vite from 8.2.1 to 8.2.2 in /web in the npm-patch group (#127)([ce2e05d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ce2e05d1f07ab98ffdb3abd0fe78101ab9eac2e4))

## [2026.8.44](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.43...2026.8.44) - 2026-08-22



### Features

- localize the HA UI for every Assist locale([a8de462](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a8de46258c2393c2ba4f6c49e0787192e2d33e46))

- add a quiet chime switch for simple light replies([dccb80a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/dccb80a3cc14259c3c55d97e4cea6bfb84cccc19))


### Other

- Merge pull request #124 from FABBricate-IT-Solutions/feat/quiet-ack-main([f6acd98](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f6acd98703604c3b9a0ce64b25afb4f809242556))

## [2026.8.43](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.42...2026.8.43) - 2026-08-20



### Documentation

- spell out HACS vs App vs bundled engine([2125e2d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2125e2dbe6cd553b5765b03fa334f92563d52ba1))


### Other

- Merge pull request #122 from FABBricate-IT-Solutions/docs/clarify-hacs-vs-app([81d6d1c](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/81d6d1c4abd4344f2f2f98a72628b2b37b9d4972))

## [2026.8.42](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.41...2026.8.42) - 2026-08-20



### Bug Fixes

- run the bundled engine on Alpine Home Assistant Core([f91b0c6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f91b0c6e958eacf861b5c7f7b39e2603ee5ebe01))


### Other

- Merge pull request #121 from FABBricate-IT-Solutions/fix/bundled-musl-engine([4539012](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4539012094d9e5386443f5e907dc6d53f4caebbd))

## [2026.8.41](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.40...2026.8.41) - 2026-08-20



### Bug Fixes

- pack the engine tarball member as klar([3ae4060](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3ae406053dfec889cc31b6d78b4ffbfe1541d857))


### Other

- Merge pull request #120 from FABBricate-IT-Solutions/fix/archive-klar-binary([2ca0d44](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2ca0d448f477265ef4cf0cb9c117c93d14852992))

## [2026.8.40](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.39...2026.8.40) - 2026-08-19



### Bug Fixes

- keep compound.rs under the 500-line gate([92ce6e7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/92ce6e7dc9122cca1336f197e77aed9f372190b2))

- speak final TTS and stream it by sentence([6201129](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/620112940e02d0c20187f722cd5c11ac9cad56d4))

- match umlaut rooms like Küche to HA slugs([fff3d05](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fff3d053b1afbf9ddfafb2683ea18a0f4e05224d))


### Documentation

- show 67 languages and the follow-up banner([e9802c8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e9802c838e917c8539685a4c22a24b5da71ce76b))


### Miscellaneous

- stop shipping armv7 after Home Assistant dropped 32-bit([a262240](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a2622405d3c66895ec9b2ca4ccbafe1eb31e8287))


### Other

- Merge pull request #118 from FABBricate-IT-Solutions/drop/armv7([569a6b8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/569a6b83bcdd547630e9ac8634434730318c816d))

- Merge pull request #117 from FABBricate-IT-Solutions/fix/tts-stream-umlaut([428a2ef](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/428a2ef773bcdbbe9f8860fa8cc10d8e91817155))

## [2026.8.39](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.38...2026.8.39) - 2026-08-19



### Other

- Merge pull request #116 from FABBricate-IT-Solutions/release/promote-personality([a5c0a13](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a5c0a13ec1076449ec8df6c2532b9b7f4a18ba57))

- Merge remote-tracking branch 'origin/main' into release/promote-personality([21125cc](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/21125cc97e6e4926ae17e44f4915cc82705401e2))

## [2026.8.38](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.37...2026.8.38) - 2026-08-19



### Other

- Merge pull request #114 from FABBricate-IT-Solutions/release/promote-nlu-rag([97f6031](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/97f603162ac57d1cfa04b4753ccef581e5bbb2f8))

- Merge remote-tracking branch 'origin/main' into release/promote-nlu-rag([616020b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/616020b3cc1ad42d7046c237100b01ae1d1f7f36))

## [2026.8.37](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.36...2026.8.37) - 2026-08-19



### Other

- Merge pull request #112 from FABBricate-IT-Solutions/release/promote-wiedergabe([3c65d9b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3c65d9bcf0feef059b5d2ca5d1a111dd4e1f905c))

- Merge remote-tracking branch 'origin/main' into release/promote-wiedergabe([35b1aff](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/35b1affb4d92f6d080f5f8594494d57451cfe6e6))

## [2026.8.36](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.35...2026.8.36) - 2026-08-19



### Other

- Merge pull request #110 from FABBricate-IT-Solutions/release/promote-staging([4cbc4fa](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4cbc4facb509107250789472d0e96010abd566f1))

- Merge remote-tracking branch 'origin/main' into release/promote-staging([4bf2dec](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4bf2dec4a89ff348bf228a1a9bf4652a49d5140d))

## [2026.8.35](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.34...2026.8.35) - 2026-08-18



### Bug Fixes

- options flow 400 on Configure (#108)([1e75383](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1e753831d7c7d0e7a3409ffa9c2463affb794026))

## [2026.8.34](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.33...2026.8.34) - 2026-08-18



### Documentation

- bump rust from 1.85-bookworm to 1.97-bookworm (#104)([4d5bf80](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4d5bf804d2bc7685d84fcc815cb7fa6837237cc5))


### Other

- bump uuid from 1.24.0 to 1.24.1 in the rust-patch group (#105)([828d1cb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/828d1cb462e21644b63ab3779cc88a3fe41399c1))

## [2026.8.33](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.32...2026.8.33) - 2026-08-18



### Other

- Merge pull request #103 from FABBricate-IT-Solutions/release/promote-staging([4e5b3c6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4e5b3c682ee7f2dd3ca39a15ef0146dc6bfd58ce))

- main 2026.8.32 into staging for the stable cut([d572987](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d57298791c7c8fc72ca9af38d24b5355af106ab0))

## [2026.8.32](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.31...2026.8.32) - 2026-08-18



### Features

- add a Stable/Staging switch on main([bb4f8f1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bb4f8f13117b79d1477bc288cc85fadcd5fd9c19))


### Other

- Merge pull request #97 from FABBricate-IT-Solutions/feat/simple-channel-switch-main([b106172](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b1061725570f205f4df3ff1b32baeff5faf5b089))

## [2026.8.31](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.30...2026.8.31) - 2026-08-17



### Features

- phrase rules, journal tab, fuzzy compounds (#91)([c226a9d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c226a9dccb21e29bddc1429a2b40e89f462f8641))

## [2026.8.30](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.29...2026.8.30) - 2026-08-17



### Features

- policies, journal, NLU-RAG, and quieter UI (#88)([c651441](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c65144115799bc02ca34b26c0240581e35b87c04))


### Miscellaneous

- nextest, faster PR checks, auto-release on main (#90)([5b9c1fa](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5b9c1fac3bdcb89787be5803e5540ec6e4ec26fc))

- bump docker/setup-buildx-action from 3 to 4 (#87)([fa42574](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fa42574b82ac8871a32bb6c7e3cac2c4f68a23da))

- bump actions/setup-node from 6 to 7 (#86)([77aa0bd](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/77aa0bd91526c96524737acdfa38bfdd5f57a460))

- bump docker/login-action from 3 to 4 (#85)([2256dd3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2256dd3c79e41f4faf443c6025bbf3b072183563))

## [2026.8.29](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.28...2026.8.29) - 2026-08-17



### Bug Fixes

- speak room climate from HA state when area get fails([142a7c8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/142a7c8e1ae360c946623e6bffe627249ac31180))


### Other

- Merge pull request #83 from FABBricate-IT-Solutions/fix/area-climate-fallback([d28d7b3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d28d7b3092f7da85f1234168c76f542f464482b9))


### Testing

- mock entity_registry when loading dispatch([6342647](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6342647c26681b8e24628c03a40ab285e7d120a2))

## [2026.8.28](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.27...2026.8.28) - 2026-08-16



### Bug Fixes

- let HA sync homes and answer temperature queries([ce107ae](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ce107ae4a898325562fb419a89e657d6593a9b29))


### Other

- Merge pull request #81 from FABBricate-IT-Solutions/fix/live-query-sync([faf7cee](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/faf7ceeae83f57432d52d650eab64f5e4085b18d))

## [2026.8.27](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.26...2026.8.27) - 2026-08-16



### Bug Fixes

- accept V2 parse trace tokens from the engine([51126f4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/51126f4ad85c6c2f5a15ca67b385a489ebb73ee1))


### Other

- Merge pull request #79 from FABBricate-IT-Solutions/fix/accept-trace-tokens([0457662](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/045766211c711907793908d788794cf4a58924e9))

## [2026.8.26](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.25...2026.8.26) - 2026-08-16



### Bug Fixes

- match rustfmt 1.97 line wrapping([b616d1d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b616d1da3bd990f7949e818d0eacdab3a8ced9d0))

- satisfy clippy 1.97 some_filter([bfd8b3a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bfd8b3ad81743290d3e8ae9e709e2245ba43678a))


### Features

- [**breaking**] replace the parse contract with V2 ParseOutcome([5f45302](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5f45302e4ae0d864d04d5c4fff36c6e1b04e2cc9))


### Other

- Merge pull request #77 from FABBricate-IT-Solutions/feat/v2-nlu-platform([24bcb17](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/24bcb17ed76c326971db80b9002c1a63eae47759))

## [2026.8.25](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.24...2026.8.25) - 2026-08-16

### Bug Fixes

- harden Music Assistant targeting ([f995ccb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f995ccbcb7642f4e1e2b64b3d47bcf456ba33b83))

### Other

- Merge pull request #75 from FABBricate-IT-Solutions/fix/music-assistant-hardening ([4ff1deb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4ff1debc270605413e798a630acc6c9eb41c7ec3))

## [2026.8.24](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.23...2026.8.24) - 2026-08-16

### Features

- harden voice matching for ASR errors ([e99b683](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e99b6830008468f6392db9a9e18844f94ac99e9b))

### Other

- Merge pull request #73 from FABBricate-IT-Solutions/feat/asr-fuzzy-matching ([f428df7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f428df71421e0ed4b8164abd3116a76018fa8be2))

## [2026.8.23](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.22...2026.8.23) - 2026-08-16



### Bug Fixes

- satisfy clippy for media parsing([f38048d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f38048d75331b4e52b539214bbec0024985dcb47))

- format Music Assistant voice control changes([240e577](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/240e577aba55a4418ced07d3527e8ed0866552f7))


### Features

- add Music Assistant voice control([70a943b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/70a943b0670fbea0475012c7c0ae834f6ea54df5))


### Other

- Merge pull request #71 from FABBricate-IT-Solutions/feat/music-assistant-voice-control([9ef246e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/9ef246e6b4a65720561850442915bf7b2e104494))

## [2026.8.22](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.21...2026.8.22) - 2026-08-16

### Bug Fixes

- keep graph nodes inside a scrollable room-based layout
- allow authenticated Home Assistant ingress to save UI settings
- count live Klar NLU traffic even when support-bundle recording is off

## [2026.8.21](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.20...2026.8.21) - 2026-08-16

### Bug Fixes

- include the built React UI in release container images

## [2026.8.20](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.19...2026.8.20) - 2026-08-16

### Features

- add a React operator UI with dashboard, assignment graph, calibration inbox, and Home Assistant sidebar ingress
- record optional support bundles and export Assist traffic as a dataset
- improve German status parsing for dative and plural light forms

### Testing

- add Assist replay datasets for live apartment voice queries

## [2026.8.19](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.18...2026.8.19) - 2026-08-15



### Other

- Merge pull request #66 from FABBricate-IT-Solutions/refactor/rust-structure-docs([bc89637](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bc89637f56649d8b93f0e4cdb9c100dc2026913d))

- Merge branch 'main' into refactor/rust-structure-docs([13137cb](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/13137cbed9640ee7fe9d345dbc9c45f61b9c1694))

## [2026.8.18](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.17...2026.8.18) - 2026-08-15



### Bug Fixes

- let personality refine sound natural instead of stamping a cue([c37156e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/c37156e95706d672921fba0d655b95f22389af91))

## [2026.8.17](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.16...2026.8.17) - 2026-08-15



### Bug Fixes

- include LICENSE and third-party notices in release artifacts([eaf0d32](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/eaf0d3203a2e7e4932e230052690445e739e721e))

## [2026.8.16](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.15...2026.8.16) - 2026-08-15



### Bug Fixes

- unify room light targeting and harden the parse path([ff33d9b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ff33d9bedad485888dd9570a382a479aa715d47f))

## [2026.8.15](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.14...2026.8.15) - 2026-08-15



### Bug Fixes

- harden API auth and infer action from the resolved target([79dfa13](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/79dfa1331edefd147965cc092edce671f82cf2b5))


### Other

- Merge pull request #58 from FABBricate-IT-Solutions/fix/auth-action-target-overlay([09eead6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/09eead67210fb3082e0de27d6fdfd3aa4c84c0e6))


### Testing

- cover schalte das Wohnzimmerlicht an([fd455ea](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/fd455ea5acb3a5af2b59a6a73f91fdf263b0ea6d))

## [2026.8.14](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.13...2026.8.14) - 2026-08-15



### Bug Fixes

- speak HA display names and keep compound light status([517bb37](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/517bb3784f528610f52ee9a9a1b06d68b19e1f16))


### Other

- Merge pull request #56 from FABBricate-IT-Solutions/fix/addon-entity-display-names([f4d0080](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f4d0080392145a4d3a18220174266e26dc73dd0b))

## [2026.8.13](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.12...2026.8.13) - 2026-08-15



### Features

- refine NLU replies in each personality voice([1380e2e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/1380e2e6306dddcda5306fdcdd3b5d6d19c7f5c6))


### Other

- Merge pull request #54 from FABBricate-IT-Solutions/fix/climate-speech-refine-voice([f98ee19](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f98ee19596636635e5dca16775f9320edf02ce1c))


### Styling

- rustfmt climate speech tests([8dec09b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8dec09b6ffcb29540bdbca78237be4f6a30d7663))

## [2026.8.12](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.11...2026.8.12) - 2026-08-15



### Bug Fixes

- detect formal news follow-up prompts([af6dcde](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/af6dcde6e9fd3e94c92ebbe5aa51b25d1c6439ca))


### Other

- Merge pull request #52 from FABBricate-IT-Solutions/fix/news-nudge-formal([f38c279](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f38c279d17936ca0fe4bb834f7db297b4bbfa360))

## [2026.8.11](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.10...2026.8.11) - 2026-08-15



### Features

- refine NLU replies through the fallback LLM([5ec1b89](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/5ec1b89c5665426234b0c25d6ebf28ec5e8737f3))


### Other

- Merge pull request #50 from FABBricate-IT-Solutions/feat/llm-speech-refine([22f1232](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/22f12325e470862f13b20acc2299e9083683d99b))

## [2026.8.10](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.9...2026.8.10) - 2026-08-15



### Features

- route news questions through a briefing then the LLM([dec7875](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/dec78757648e80a6f1830e2786cc7603c7818576))


### Other

- Merge pull request #48 from FABBricate-IT-Solutions/feat/news-briefing([284689b](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/284689b3d2f9686c6a897112c89c30a535457973))

## [2026.8.9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.8...2026.8.9) - 2026-08-15



### Bug Fixes

- elide needless lifetime on fallback_climate([b934148](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b9341485a9aa8e483bcffbe11e6aee6ff0f766d1))


### Miscellaneous

- include ENGINE_VERSION in the release land commit([6c7bc7d](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/6c7bc7dd1578baa9b58bc54bdd70d66543e3fec8))


### Other

- Merge pull request #47 from FABBricate-IT-Solutions/refactor/packs-and-home-policy([0ca5ff0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/0ca5ff0ac60c7542813d6784642e2113100a8e0a))


### Refactor

- extract language packs and home policy from the parse pipeline([483d93e](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/483d93e9379da6e1ff5c33afefe1b1c1c7d3838b))

## [2026.8.8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.7...2026.8.8) - 2026-08-15

### Bug Fixes

- Pick the only matching Heizung or Klimaanlage when the sentence has no room and no alias

## [2026.8.7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.6...2026.8.7) - 2026-08-15

### Features

- Route casual and special speech to the LLM fallback even when that agent advertises Assist tools
- Distinguish Heizung and Klimaanlage by name, alias, and HA tags

### Bug Fixes

- Treat genitive room status (*Status der Küche*) as the area, not the kitchen lamp
- Set *Klimaanlage auf 20° / 20 Grad* on the AC instead of the bedroom heater

## [2026.8.6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.5...2026.8.6) - 2026-08-15

### Bug Fixes

- Start the GHCR add-on image through `klar-entry.sh` so HTTP and Wyoming bind `0.0.0.0` even when Supervisor passes extra args
- Allow parse and GET from the Supervisor network without a token so Assist reaches the add-on out of the box

## [2026.8.5](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.4...2026.8.5) - 2026-08-15

### Bug Fixes

- Skip Adaptive Lighting switches when expanding Licht, so room follow-ups do not flip adapt or sleep modes
- Take GitHub release notes from CHANGELOG.md instead of `git-cliff --latest` after a `chore(release):` squash

## [2026.8.4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/2026.8.3...2026.8.4) - 2026-08-15

### Security

- Require loopback or token for parse and GET APIs; bind localhost by default; keep addon ports off the host
- Fail engine download without a SHA-256 digest
- Skip LLM fallback when the agent advertises Assist tools
- Filter unexposed entities in resolve, compound, roles, timers, and follow-ups

### Features

- Speak clarify and vacuum replies from friendly names
- Reload the home graph when HA registries change
- Persist custom sentences in the overlay; cap sessions at 256

### Miscellaneous

- Split lang, parse, and registry modules under 500 lines
- Raise English smoke to 99%; add Wyoming, digest, speech, and fallback tests
- Wait for rustfmt and clippy before tagging a release

## [2026.8.3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/v2026.8.2...2026.8.3) - 2026-08-15



### Features

- role tags, natural speech, and CalVer tags without v([2a90d58](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2a90d58))

## [2026.8.2](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/v2026.8.1...v2026.8.2) - 2026-08-15



### Bug Fixes

- start release checks from the prepare job([94433cf](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/94433cf14971c61a5dfe0492643242ab725792c6))

- land release commits without an Actions pull request([4de314a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/4de314a631984ce1a41c3a99c8cece92c81084ae))

## [2026.8.1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/v2026.8.0...v2026.8.1) - 2026-08-15



### Miscellaneous

- run rustfmt in CI([77e0c95](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/77e0c95c7671af99e55f2b55ec99c943fe55d4e2))

## [2026.8.0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/v0.1.10...v2026.8.0) - 2026-08-15



### Bug Fixes

- store Assist personality in the Home Assistant integration (#30)([27b4846](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/27b48467b7e7accef7ffa5f9d47335e33eb22771))

- keep room-scoped all-lights and run the parsed entity (#29)([ad298e4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ad298e4d8f2ac3ddf1965e4d5e3191adb8f4c0ec))


### Miscellaneous

- switch releases to Home Assistant calendar versions (#31)([e099c83](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e099c8388927f995fa4ad63337c6f4617af91b32))

## [0.1.10](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/v0.1.9...v0.1.10) - 2026-08-15



### Bug Fixes

- keep und-names in questions and prefer the outlet (#27)([d8d5585](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/d8d5585027d21fb0d2636cfe6d4129ec61309b54))

## [0.1.9](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/v0.1.8...v0.1.9) - 2026-08-15



### Bug Fixes

- pass the device name so Assist can run entity-only intents (#26)([904cd85](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/904cd856aebd043a63dabc184333b9473497fd43))

- do not match aus to the Alles-aus scene (#24)([f3a3bd6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f3a3bd622bf668c70ee8c9a9d3205eb386a3d92b))

## [0.1.8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/v0.1.7...v0.1.8) - 2026-08-15



### Bug Fixes

- keep one target and replay pronoun follow-ups (#22)([50a2ca2](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/50a2ca285881d57f16f968917ad0d8d7472e828d))

## [0.1.7](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/v0.1.6...v0.1.7) - 2026-08-15



### Bug Fixes

- speak German states and keep the web UI personality on Assist (#20)([f322059](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f32205998c86a1d35e21d75cb1bac9084b686d18))

## [0.1.6](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/v0.1.5...v0.1.6) - 2026-08-15



### Features

- map leftover Assist devices in the web UI (#18)([bc85ce4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/bc85ce45a03bd40d942b2dc2d43c81487017e81c))

## [0.1.5](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/v0.1.4...v0.1.5) - 2026-08-15



### Bug Fixes

- inherit Hue room areas so Schlafzimmerlicht hits the Kugel([2ee34c8](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/2ee34c863db6d8e310eeff259131848056cd6597))

## [0.1.4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/v0.1.3...v0.1.4) - 2026-08-15



### Bug Fixes

- resolve live Wohnung lights, names, and English phrases([8fa3318](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/8fa331880af731590b7ffae678adfc222d35a972))

## [0.1.3](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/v0.1.2...v0.1.3) - 2026-08-15



### Bug Fixes

- cancel timers and speak climate temperature (#12)([3449b33](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3449b338232d885039cc8d26ce6382797a8979a4))

## [0.1.2](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/v0.1.1...v0.1.2) - 2026-08-15



### Bug Fixes

- start Assist timers and match the real shopping list (#10)([e3e6de2](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e3e6de2e16e0678681e1565f49169c2526765a5f))

## [0.1.1](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/compare/v0.1.0...v0.1.1) - 2026-08-15



### Bug Fixes

- German and English Assist speech and rooms (#8)([3b4da80](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3b4da808fbf07152b60f65bd800337d08621878b))

- bilingual Assist conversation agent (#6)([04a806a](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/04a806af3359c951bc9c8b23ba5cff316471f434))


### Features

- publish Docker images and a Home Assistant add-on repository([e62a715](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e62a71537fcea8551cb6ecab60b9f4956f7cfc9e))


### Miscellaneous

- open a release PR instead of pushing version bumps to main([f38a784](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/f38a784c1cdbe0acfee2ddfcd4fc52b0bc5b8352))

- add CODEOWNERS, a PR template, and read-only CI permissions([7429d26](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/7429d2609a968ba4059f335ebb6acd1677d33440))

## [0.1.0](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/releases/tag/v0.1.0) - 2026-08-14



### Documentation

- shrink the README logo so it fits the HACS info panel([ea8e596](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/ea8e5964c74c462a7394537a8a9920092d2ba4be))

- use a markdown image for the logo so HACS can render it([82b0cd4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/82b0cd4482ffe841886b6a192e612751c462e4c3))

- load the README logo from an absolute URL so HACS can show it([221c2c4](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/221c2c4b1961909e59167731c3ca20faed5b7608))


### Features

- start the Klar engine from the Home Assistant integration([b757353](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/b757353758d1dbe221477ef2b9f3b9aba72610f5))

- add HACS install for the Home Assistant integration([26e6916](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/26e6916b5aa494c2c0e8f495b2b9cc8f3d3e5a15))


### Miscellaneous

- bump checkout, artifact, and gh-release actions([dbf9171](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/dbf9171c913256658580bd20045168a568dc5959))

- generate changelogs and releases with git-cliff([a3cb586](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/a3cb5862c1a448f1312cd41b970e97bf5d222223))


### Other

- bump tower-http from 0.6 to 0.7([3abad97](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3abad97e4ddde88df77c2ea6b615f0bbb33ecec7))

- Update dependabot.yml([3edeb08](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/3edeb087198c5df40c29022235de65a652dc04b8))

- Publish Klar NLU with CI, security scans, and multi-arch builds.([e4801a5](https://github.com/FABBricate-IT-Solutions/klar-ha-nlu/commit/e4801a53878c5b65a8cf7f940a0f8283cc692e81))

<!-- generated by git-cliff -->
