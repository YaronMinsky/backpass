# Changelog

## [0.1.45](https://github.com/YaronMinsky/backpass/compare/backpass-v0.1.44...backpass-v0.1.45) (2026-11-24)


### Features

* add existing-skill extracts and memory moves ([#83](https://github.com/YaronMinsky/backpass/issues/83)) ([e40308e](https://github.com/YaronMinsky/backpass/commit/e40308ebbcd1ca78f9f40bbfe19bc8cf8a588d10))
* add user-level memory scope ([#101](https://github.com/YaronMinsky/backpass/issues/101)) ([6635611](https://github.com/YaronMinsky/backpass/commit/66356115242617775d068021c79568285df00f03))
* **apply:** keep reworded rejected edits suppressed and record optional reject reasons ([#162](https://github.com/YaronMinsky/backpass/issues/162)) ([ff8b305](https://github.com/YaronMinsky/backpass/commit/ff8b3056010c25c6f6b03eb5627aa2f40c0aa0b1))
* **apply:** unify funnel from findings to proposed edits ([#104](https://github.com/YaronMinsky/backpass/issues/104)) ([5097aab](https://github.com/YaronMinsky/backpass/commit/5097aab68689cdcc60b37b2c3029f945fe90f8bc))
* **apply:** visualize gap evidence funnel on review board ([#69](https://github.com/YaronMinsky/backpass/issues/69)) ([1ff7403](https://github.com/YaronMinsky/backpass/commit/1ff740363cdffab68b4e42e6cc2756fb96fe2a95))
* classify and balance interactive corpus sessions ([#85](https://github.com/YaronMinsky/backpass/issues/85)) ([131f4eb](https://github.com/YaronMinsky/backpass/commit/131f4ebfa5d2655c4c23ab96e0a3abf398b99d3b))
* **config:** add skillSearchPaths for read-only awareness of shared skill libraries ([#138](https://github.com/YaronMinsky/backpass/issues/138)) ([c409f50](https://github.com/YaronMinsky/backpass/commit/c409f5079143f536541c617996c0486e7748efeb))
* **discovery:** add Hermes transcript support ([#26](https://github.com/YaronMinsky/backpass/issues/26)) ([be2258b](https://github.com/YaronMinsky/backpass/commit/be2258b6766a7b5dbdc618ac3df8c636c76c3238))
* **discovery:** add opt-in OMP session discovery to the Pi adapter ([#151](https://github.com/YaronMinsky/backpass/issues/151)) ([20c90ca](https://github.com/YaronMinsky/backpass/commit/20c90ca969022d1b83c47b30c0d2ae759e60518d))
* **discovery:** collect sessions from remote machines over SSH ([#124](https://github.com/YaronMinsky/backpass/issues/124)) ([409fd11](https://github.com/YaronMinsky/backpass/commit/409fd117b81a44000dad234268a8a7e13c8c7219))
* **discovery:** support additional OpenCode stores and 2.x transcripts ([#181](https://github.com/YaronMinsky/backpass/issues/181)) ([26dc892](https://github.com/YaronMinsky/backpass/commit/26dc8926bf9112b88dedf4f3784eeec540999da0))
* initial commit ([ea50345](https://github.com/YaronMinsky/backpass/commit/ea50345f607e978761903740afe82a9dd3e2409b))
* judge gap identity and safeguard instruction removals ([#64](https://github.com/YaronMinsky/backpass/issues/64)) ([e11c9ba](https://github.com/YaronMinsky/backpass/commit/e11c9bab7e12d7ab7957e5780de254e09d7ae07e))
* let runs target one memory file or skill ([#108](https://github.com/YaronMinsky/backpass/issues/108)) ([461ee31](https://github.com/YaronMinsky/backpass/commit/461ee31666b0f327e2a7b5bb6e6841ffe37d7874))
* **prompts:** make gap domain a causal test and soften the extraction nudge ([#67](https://github.com/YaronMinsky/backpass/issues/67)) ([df5a8cd](https://github.com/YaronMinsky/backpass/commit/df5a8cdc8edcb75f571c5c1d96e047f510129493))
* report cross-surface skill duplication ([#81](https://github.com/YaronMinsky/backpass/issues/81)) ([d5ce349](https://github.com/YaronMinsky/backpass/commit/d5ce34999d7f90c8cddae3c43a54921faa3015ab))
* split oversized paragraphs for precise attribution ([#88](https://github.com/YaronMinsky/backpass/issues/88)) ([bf378cd](https://github.com/YaronMinsky/backpass/commit/bf378cd4b061fbf975bb72cbc4745c901bba6841))
* **status:** show each nested memory file's sampled-session reach ([#209](https://github.com/YaronMinsky/backpass/issues/209)) ([f20b28b](https://github.com/YaronMinsky/backpass/commit/f20b28b15c8b176d6bb98721c6b30725c1a0d310)), closes [#191](https://github.com/YaronMinsky/backpass/issues/191)
* support explicit per-edit decisions in backpass apply ([#182](https://github.com/YaronMinsky/backpass/issues/182)) ([1df44c9](https://github.com/YaronMinsky/backpass/commit/1df44c95aaead578eb7d7cc13c932f7e54005a2a))
* train named nested memory files in monorepos ([#159](https://github.com/YaronMinsky/backpass/issues/159)) ([76c6b1c](https://github.com/YaronMinsky/backpass/commit/76c6b1c2acf38066765bbb6a11da2604c39fb273))
* treat project skills as improvable memory ([#72](https://github.com/YaronMinsky/backpass/issues/72)) ([f559a22](https://github.com/YaronMinsky/backpass/commit/f559a224024e46e98c3514c689e6c440de572eae))


### Bug Fixes

* **acpx:** fall through the agent ladder on clean-exit empty output ([#122](https://github.com/YaronMinsky/backpass/issues/122)) ([b867d11](https://github.com/YaronMinsky/backpass/commit/b867d1102f78cd7a6d2424a73819754d5758819e))
* **acpx:** report acpx budget kills as timeouts, not empty-output ([#145](https://github.com/YaronMinsky/backpass/issues/145)) ([5e45872](https://github.com/YaronMinsky/backpass/commit/5e45872485641844a4599591fd1fd079a436099f))
* **acpx:** retry timed-out adapter verification instead of aborting the run ([#168](https://github.com/YaronMinsky/backpass/issues/168)) ([aa44b04](https://github.com/YaronMinsky/backpass/commit/aa44b04e13f91940b607c909ef4e5f3562b676d0))
* **acpx:** send --agent session prompts through the prompt subcommand ([#100](https://github.com/YaronMinsky/backpass/issues/100)) ([fda7649](https://github.com/YaronMinsky/backpass/commit/fda7649b5c9fb8a0e83821a8fd578e412ad9bed1))
* **acpx:** stop discarding stderr on empty-output classification ([#131](https://github.com/YaronMinsky/backpass/issues/131)) ([e1df26d](https://github.com/YaronMinsky/backpass/commit/e1df26dbfd8d186ad95fe9ed5b811019c27e5c40))
* **acpx:** surface opencode stderr on exec and session-prompt failures ([#109](https://github.com/YaronMinsky/backpass/issues/109)) ([8f37c36](https://github.com/YaronMinsky/backpass/commit/8f37c36284f658b4cc770725365beb74233b2a5e))
* **acpx:** treat a model the adapter turns down as model-unavailable ([#219](https://github.com/YaronMinsky/backpass/issues/219)) ([02c8796](https://github.com/YaronMinsky/backpass/commit/02c879606f9bd0e146e4cb303e778973de9e3c00))
* **agents:** treat "does not support this model" as model-unavailable ([#185](https://github.com/YaronMinsky/backpass/issues/185)) ([7d927fc](https://github.com/YaronMinsky/backpass/commit/7d927fcac7ff21b517e28cf35775976335c49a7a))
* allow acpx adapters to finish cold starts ([#110](https://github.com/YaronMinsky/backpass/issues/110)) ([f145d5e](https://github.com/YaronMinsky/backpass/commit/f145d5e3e5010e8de72d3b913d35912be4b18b27))
* **analyze:** discard evidence quotes that do not appear in the distilled trace ([#118](https://github.com/YaronMinsky/backpass/issues/118)) ([3cb35be](https://github.com/YaronMinsky/backpass/commit/3cb35bef8affcd640c89268ae11cb8739939d321))
* **apply:** compare skillsDir by resolved logical path and drop placeholder failure locations ([#133](https://github.com/YaronMinsky/backpass/issues/133)) ([b76f54c](https://github.com/YaronMinsky/backpass/commit/b76f54cf851bbe86c4ee25363a371037d773f356))
* **apply:** open the review surface in the browser, announce waits once, and strip the quoted URL ([#18](https://github.com/YaronMinsky/backpass/issues/18)) ([a718b60](https://github.com/YaronMinsky/backpass/commit/a718b60f21595d5fdd5f8aee64a8cef7bac562a9))
* **apply:** prevent partial writes from stale proposals ([#47](https://github.com/YaronMinsky/backpass/issues/47)) ([443809b](https://github.com/YaronMinsky/backpass/commit/443809b173645bd6b67fe4f80e7f114a20fdc3b3))
* **apply:** refuse a proposal made under a different budget ([#210](https://github.com/YaronMinsky/backpass/issues/210)) ([e10cd7d](https://github.com/YaronMinsky/backpass/commit/e10cd7df6da83d07b2e34a6e2e67543ec2efe44b))
* **apply:** reopen ended Lavish review sessions ([#45](https://github.com/YaronMinsky/backpass/issues/45)) ([6493b81](https://github.com/YaronMinsky/backpass/commit/6493b81cd06b0272d67340e894f7b534088e0e75))
* **apply:** revalidate accepted edit subsets ([#38](https://github.com/YaronMinsky/backpass/issues/38)) ([d4f321c](https://github.com/YaronMinsky/backpass/commit/d4f321ced28bc1dd1d1b1613c57f24fa2de9897f))
* **apply:** stop replacement-token expansion from corrupting apply.html ([#60](https://github.com/YaronMinsky/backpass/issues/60)) ([a2a9ae3](https://github.com/YaronMinsky/backpass/commit/a2a9ae3f32292354be60d12dc076137260b0a675))
* **config:** preserve global agent pins after init ([#137](https://github.com/YaronMinsky/backpass/issues/137)) ([a36196d](https://github.com/YaronMinsky/backpass/commit/a36196da88ab9492cd0c2ae39fe91dd7f27d9cf3))
* correct synthesis orchestration and apply rollback ([#52](https://github.com/YaronMinsky/backpass/issues/52)) ([c4bccc0](https://github.com/YaronMinsky/backpass/commit/c4bccc008d88ee4adb3148f1fb5fa6c62bbab392))
* count only fold-issued sources toward session floors ([#105](https://github.com/YaronMinsky/backpass/issues/105)) ([9223fe6](https://github.com/YaronMinsky/backpass/commit/9223fe6f465998100d03446f6294ad2e2d0a0ecf))
* decide gap cluster domains after grouping ([#87](https://github.com/YaronMinsky/backpass/issues/87)) ([eaf2a6a](https://github.com/YaronMinsky/backpass/commit/eaf2a6a80ed6d355f3e79b48ac85444701f1920d))
* deduplicate symlinked skills in the analysis index ([#231](https://github.com/YaronMinsky/backpass/issues/231)) ([bf57333](https://github.com/YaronMinsky/backpass/commit/bf573333286e597619bd5cc5dd09d8f2cc3a1730))
* **discovery:** associate sessions in repos with separate git directories ([#206](https://github.com/YaronMinsky/backpass/issues/206)) ([98d184f](https://github.com/YaronMinsky/backpass/commit/98d184f774e977439010288ace2415ee937edf1b))
* **discovery:** discover BB-managed Pi sessions ([#58](https://github.com/YaronMinsky/backpass/issues/58)) ([7795c59](https://github.com/YaronMinsky/backpass/commit/7795c59d9c2c16c52468bd838c86701ffac1ebad))
* **discovery:** find sessions in sibling clones ([#84](https://github.com/YaronMinsky/backpass/issues/84)) ([d56661d](https://github.com/YaronMinsky/backpass/commit/d56661db225f2f5b74ce26c07f012920cc98e521))
* **discovery:** include Hermes TUI sessions with absolute cwd ([#146](https://github.com/YaronMinsky/backpass/issues/146)) ([3d64e83](https://github.com/YaronMinsky/backpass/commit/3d64e83b747779acb3bfcbeb06324ee7d90b16cb))
* **discovery:** recover Hermes v26 CLI sessions ([#28](https://github.com/YaronMinsky/backpass/issues/28)) ([ca98dce](https://github.com/YaronMinsky/backpass/commit/ca98dce535b9b0d87188de1c37496713569886f0))
* **discovery:** scan CLAUDE_CONFIG_DIR alongside the default claude store ([#41](https://github.com/YaronMinsky/backpass/issues/41)) ([a0014bc](https://github.com/YaronMinsky/backpass/commit/a0014bc7d8154c146826db6c680e63cb3a66c9e8))
* enable synthesis harness write access ([#82](https://github.com/YaronMinsky/backpass/issues/82)) ([a006b64](https://github.com/YaronMinsky/backpass/commit/a006b6436bef76562c2cdf75e392e49c56e95b22))
* isolate SQLite session raw transcripts and reclaim expired files ([#178](https://github.com/YaronMinsky/backpass/issues/178)) ([aab9419](https://github.com/YaronMinsky/backpass/commit/aab941902d4549d94dac42279351c812741a5925))
* keep EOF-reaching mixed removals merged ([#65](https://github.com/YaronMinsky/backpass/issues/65)) ([e1a7302](https://github.com/YaronMinsky/backpass/commit/e1a73023e54f2c2676905127262cee804d8ad4d5))
* keep harness model and effort overrides invocation-scoped ([#49](https://github.com/YaronMinsky/backpass/issues/49)) ([9a821f7](https://github.com/YaronMinsky/backpass/commit/9a821f7d514e84cf584adc751cbba166aef932d5))
* make transcript sampling deterministic and sticky ([#62](https://github.com/YaronMinsky/backpass/issues/62)) ([7516b00](https://github.com/YaronMinsky/backpass/commit/7516b000f292cfcf0246950716d2077a57d32401))
* mark successfully applied proposals to prevent replay ([#241](https://github.com/YaronMinsky/backpass/issues/241)) ([fa3bac5](https://github.com/YaronMinsky/backpass/commit/fa3bac53b162f457dc03cc9988abaaa0311c7980))
* **memory:** recognize CLAUDE.md symlinks as pointers ([#217](https://github.com/YaronMinsky/backpass/issues/217)) ([dd38ec5](https://github.com/YaronMinsky/backpass/commit/dd38ec5bdc36c4bc07795684fa714f846baa370b))
* **memory:** stop treating thematic breaks as instruction units ([#213](https://github.com/YaronMinsky/backpass/issues/213)) ([2a12aaf](https://github.com/YaronMinsky/backpass/commit/2a12aaf7fb71a9e873f5ea8c0579d7d33e1b2000))
* preserve evidence cache correctness across memory targets ([#238](https://github.com/YaronMinsky/backpass/issues/238)) ([cf170fb](https://github.com/YaronMinsky/backpass/commit/cf170fb55f11424d52e08f8cb48ea897dee0884b))
* preserve stable evidence session identities ([#106](https://github.com/YaronMinsky/backpass/issues/106)) ([4b57403](https://github.com/YaronMinsky/backpass/commit/4b574033a8be60ae39eccc8abd168637ca3d092c))
* prevent false session matches from Windows paths on POSIX ([#173](https://github.com/YaronMinsky/backpass/issues/173)) ([a26758c](https://github.com/YaronMinsky/backpass/commit/a26758c19559232b9bd0b36f95a974f33cb9bb80))
* **prompts:** classify orchestrator repo gaps as project ([#78](https://github.com/YaronMinsky/backpass/issues/78)) ([6180c82](https://github.com/YaronMinsky/backpass/commit/6180c82e2d80ce8db717546cd431c2fbb346ba21))
* recognize acpx exit code 3 as a timeout ([#177](https://github.com/YaronMinsky/backpass/issues/177)) ([1de342a](https://github.com/YaronMinsky/backpass/commit/1de342a7a5ed06c1039e79804c5ef918d4fac4f7))
* recognize CLAUDE.md import pointers with leading headings ([#240](https://github.com/YaronMinsky/backpass/issues/240)) ([9af07e4](https://github.com/YaronMinsky/backpass/commit/9af07e47e1bc4338ed8abd4f7a6cdaa16d966e11))
* redact standalone apikey_ credentials ([#147](https://github.com/YaronMinsky/backpass/issues/147)) ([#242](https://github.com/YaronMinsky/backpass/issues/242)) ([4b2782b](https://github.com/YaronMinsky/backpass/commit/4b2782ba33dd3014d38a4ca3c095a2574ae3d537))
* **redact:** stop secret redaction from eating benign tool arguments ([#153](https://github.com/YaronMinsky/backpass/issues/153)) ([0e533fb](https://github.com/YaronMinsky/backpass/commit/0e533fb8462d6278d7dce4404d4fd2e70a014b2a))
* report prompt size when synthesis fails ([#243](https://github.com/YaronMinsky/backpass/issues/243)) ([ec7c492](https://github.com/YaronMinsky/backpass/commit/ec7c492dc51c8bde96371f0ca45d57bb5e495f99))
* require corroboration for every always-loaded edit ([#103](https://github.com/YaronMinsky/backpass/issues/103)) ([7c74389](https://github.com/YaronMinsky/backpass/commit/7c7438932953c81250661184bc0e51226c9c8108))
* resolve ambiguous model ids by provider auth type ([#90](https://github.com/YaronMinsky/backpass/issues/90)) ([05fb335](https://github.com/YaronMinsky/backpass/commit/05fb3350c8639cfebbbcc284faab8315f73c21e3))
* retain completed analysis after acpx permission denials ([#245](https://github.com/YaronMinsky/backpass/issues/245)) ([a3d9b40](https://github.com/YaronMinsky/backpass/commit/a3d9b4086f0857239158b8a6726383807f1ef501))
* retry transient harness capability probes ([#80](https://github.com/YaronMinsky/backpass/issues/80)) ([e75ea17](https://github.com/YaronMinsky/backpass/commit/e75ea17dd3c2122281ba00253c471dac61e4a6d9))
* run first Claude analysis call alone before fan-out ([#226](https://github.com/YaronMinsky/backpass/issues/226)) ([3f8f953](https://github.com/YaronMinsky/backpass/commit/3f8f9530ac9942b3b01c9644b542607e7a63376d))
* scope evidence reuse to the current memory hash ([#54](https://github.com/YaronMinsky/backpass/issues/54)) ([6b1beae](https://github.com/YaronMinsky/backpass/commit/6b1beae1de3eac5544e261bfbc83ef1309d7bbfb))
* select OpenCode variants via session-local ACP effort ([#73](https://github.com/YaronMinsky/backpass/issues/73)) ([2fc5893](https://github.com/YaronMinsky/backpass/commit/2fc58936641afa6aa18a33e871b81c5ca592aa4c))
* **skills:** honor configured Claude skills directory ([#96](https://github.com/YaronMinsky/backpass/issues/96)) ([86547fa](https://github.com/YaronMinsky/backpass/commit/86547fa181180e3f1931bf57df973b45f781d376))
* **skills:** parse YAML block-scalar descriptions correctly ([#94](https://github.com/YaronMinsky/backpass/issues/94)) ([b63799a](https://github.com/YaronMinsky/backpass/commit/b63799a4716ffdf5bd2c06f72547c3e51f1f5f17))
* **skills:** preserve real Claude skills directories ([#136](https://github.com/YaronMinsky/backpass/issues/136)) ([2145152](https://github.com/YaronMinsky/backpass/commit/214515284fcb1771933ba8fe099dc366c09236c5))
* **skills:** see and stage skills that are symlinked into the loaded directory ([#113](https://github.com/YaronMinsky/backpass/issues/113)) ([f0648df](https://github.com/YaronMinsky/backpass/commit/f0648df60586c63f77bfe672dc3d5d0246beadc2))
* **state:** skip unverifiable POSIX mode check for Windows user-profile state dirs ([#195](https://github.com/YaronMinsky/backpass/issues/195)) ([b6b9c08](https://github.com/YaronMinsky/backpass/commit/b6b9c08bed278bbc1d705e6a2a467553cb0f0647))
* stop scheduling analysis after a fatal worker error ([#180](https://github.com/YaronMinsky/backpass/issues/180)) ([f21f1dd](https://github.com/YaronMinsky/backpass/commit/f21f1ddd0c0c5ea9f20611b1656e571ba0465295))
* **subprocess:** launch windows npm shims through the command interpreter ([#93](https://github.com/YaronMinsky/backpass/issues/93)) ([088b84c](https://github.com/YaronMinsky/backpass/commit/088b84c9feb8f483d4f9673fce87675bcd08117f))
* **synthesize:** count stray edit-turn writes as touched ([#132](https://github.com/YaronMinsky/backpass/issues/132)) ([822f802](https://github.com/YaronMinsky/backpass/commit/822f80248339c66484a074ce3fa3cc2afb6221d1))
* **synthesize:** report a mid-run change to a watched repo file as observed ([#224](https://github.com/YaronMinsky/backpass/issues/224)) ([d0224f7](https://github.com/YaronMinsky/backpass/commit/d0224f7f7b135bbf4fe7be6738c37a716d6f7453))
* **workspace:** keep VCS internals and binary files out of the staging copy ([#220](https://github.com/YaronMinsky/backpass/issues/220)) ([d445d77](https://github.com/YaronMinsky/backpass/commit/d445d77aaf293f7a1a47a210daddb30327d3d246))

## [0.1.44](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.43...backpass-v0.1.44) (2026-11-02)


### Bug Fixes

* preserve evidence cache correctness across memory targets ([#238](https://github.com/kunchenguid/backpass/issues/238)) ([641b30f](https://github.com/kunchenguid/backpass/commit/641b30fadf9ba75d52524c79213f556083dfc22f))

## [0.1.43](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.42...backpass-v0.1.43) (2026-10-30)


### Bug Fixes

* mark successfully applied proposals to prevent replay ([#241](https://github.com/kunchenguid/backpass/issues/241)) ([0c864ce](https://github.com/kunchenguid/backpass/commit/0c864ce29e355590a4ccea6eea79e5c3147b302b))
* retain completed analysis after acpx permission denials ([#245](https://github.com/kunchenguid/backpass/issues/245)) ([1ae68b8](https://github.com/kunchenguid/backpass/commit/1ae68b8f7e5134ee31edce39751927dc3e0ec290))

## [0.1.42](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.41...backpass-v0.1.42) (2026-10-29)


### Bug Fixes

* recognize CLAUDE.md import pointers with leading headings ([#240](https://github.com/kunchenguid/backpass/issues/240)) ([df9cdce](https://github.com/kunchenguid/backpass/commit/df9cdcebab3fd4520a2a0d09bc696d9438f3cb24))
* redact standalone apikey_ credentials ([#147](https://github.com/kunchenguid/backpass/issues/147)) ([#242](https://github.com/kunchenguid/backpass/issues/242)) ([24f8283](https://github.com/kunchenguid/backpass/commit/24f8283930119250593dd70e6d62d67f4c8801bc))
* report prompt size when synthesis fails ([#243](https://github.com/kunchenguid/backpass/issues/243)) ([a2d710b](https://github.com/kunchenguid/backpass/commit/a2d710b5c6fe9ba529ebd5c2356a73689a38f28e))

## [0.1.41](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.40...backpass-v0.1.41) (2026-10-26)


### Bug Fixes

* **synthesize:** report a mid-run change to a watched repo file as observed ([#224](https://github.com/kunchenguid/backpass/issues/224)) ([1a1a175](https://github.com/kunchenguid/backpass/commit/1a1a17531de333d8095a944baa884a0896d5672d))

## [0.1.40](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.39...backpass-v0.1.40) (2026-10-25)


### Bug Fixes

* deduplicate symlinked skills in the analysis index ([#231](https://github.com/kunchenguid/backpass/issues/231)) ([9ded619](https://github.com/kunchenguid/backpass/commit/9ded6192cd7eae8c63e40559b7832774b3bac2fb))

## [0.1.39](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.38...backpass-v0.1.39) (2026-10-23)


### Bug Fixes

* run first Claude analysis call alone before fan-out ([#226](https://github.com/kunchenguid/backpass/issues/226)) ([3882b86](https://github.com/kunchenguid/backpass/commit/3882b86d84017bcdbf5e2cbe2e8c1fa9abeb3126))

## [0.1.38](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.37...backpass-v0.1.38) (2026-10-21)


### Bug Fixes

* **workspace:** keep VCS internals and binary files out of the staging copy ([#220](https://github.com/kunchenguid/backpass/issues/220)) ([46a2169](https://github.com/kunchenguid/backpass/commit/46a21696be63197815346d01f6d4e116c16b4c10))

## [0.1.37](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.36...backpass-v0.1.37) (2026-10-20)


### Bug Fixes

* **acpx:** treat a model the adapter turns down as model-unavailable ([#219](https://github.com/kunchenguid/backpass/issues/219)) ([3986087](https://github.com/kunchenguid/backpass/commit/398608764b6a7d40de142eafbf2e568921406fa9))

## [0.1.36](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.35...backpass-v0.1.36) (2026-10-16)


### Bug Fixes

* **memory:** recognize CLAUDE.md symlinks as pointers ([#217](https://github.com/kunchenguid/backpass/issues/217)) ([8f1eda3](https://github.com/kunchenguid/backpass/commit/8f1eda38d27eab2466b920a5100e84c8b639a719))

## [0.1.35](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.34...backpass-v0.1.35) (2026-10-16)


### Features

* **status:** show each nested memory file's sampled-session reach ([#209](https://github.com/kunchenguid/backpass/issues/209)) ([8bb390b](https://github.com/kunchenguid/backpass/commit/8bb390b044d791c9acd890ca8a231d540e9f73d7)), closes [#191](https://github.com/kunchenguid/backpass/issues/191)


### Bug Fixes

* **apply:** refuse a proposal made under a different budget ([#210](https://github.com/kunchenguid/backpass/issues/210)) ([f24dbab](https://github.com/kunchenguid/backpass/commit/f24dbab3539f7a8fa5b2c410c32978b9396cfe2f))
* **memory:** stop treating thematic breaks as instruction units ([#213](https://github.com/kunchenguid/backpass/issues/213)) ([d605c97](https://github.com/kunchenguid/backpass/commit/d605c97ce3e8f08b9e2915a7421956216fd1d768))

## [0.1.34](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.33...backpass-v0.1.34) (2026-10-13)


### Bug Fixes

* **discovery:** associate sessions in repos with separate git directories ([#206](https://github.com/kunchenguid/backpass/issues/206)) ([29c46e7](https://github.com/kunchenguid/backpass/commit/29c46e7209fbfd5a8739d343163b8250d67b14c6))

## [0.1.33](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.32...backpass-v0.1.33) (2026-10-12)


### Features

* **discovery:** add opt-in OMP session discovery to the Pi adapter ([#151](https://github.com/kunchenguid/backpass/issues/151)) ([9a4a773](https://github.com/kunchenguid/backpass/commit/9a4a773c0eaebfdb3ea4950a8a0f53d447ad8b60))

## [0.1.32](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.31...backpass-v0.1.32) (2026-09-30)


### Bug Fixes

* prevent false session matches from Windows paths on POSIX ([#173](https://github.com/kunchenguid/backpass/issues/173)) ([a1bd0af](https://github.com/kunchenguid/backpass/commit/a1bd0af00ced5af1ed995b71f7ef650156fbfb69))
* recognize acpx exit code 3 as a timeout ([#177](https://github.com/kunchenguid/backpass/issues/177)) ([4c1a8a8](https://github.com/kunchenguid/backpass/commit/4c1a8a82ae03d2ac9759acead7b856c491c03818))

## [0.1.31](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.30...backpass-v0.1.31) (2026-09-30)


### Features

* **discovery:** support additional OpenCode stores and 2.x transcripts ([#181](https://github.com/kunchenguid/backpass/issues/181)) ([04ac5ef](https://github.com/kunchenguid/backpass/commit/04ac5efa89ef466debad07612428ba4c5f61e65c))
* support explicit per-edit decisions in backpass apply ([#182](https://github.com/kunchenguid/backpass/issues/182)) ([d1e7550](https://github.com/kunchenguid/backpass/commit/d1e755072013801fed95ed1f1be799e328a46eb3))


### Bug Fixes

* **agents:** treat "does not support this model" as model-unavailable ([#185](https://github.com/kunchenguid/backpass/issues/185)) ([e6c2ffd](https://github.com/kunchenguid/backpass/commit/e6c2ffdacbb4c291f8b4322d7bcad2398fc1324f))
* isolate SQLite session raw transcripts and reclaim expired files ([#178](https://github.com/kunchenguid/backpass/issues/178)) ([19bd9f3](https://github.com/kunchenguid/backpass/commit/19bd9f33c3682b325de8c93bc54c19e9c6945418))
* **state:** skip unverifiable POSIX mode check for Windows user-profile state dirs ([#195](https://github.com/kunchenguid/backpass/issues/195)) ([b0e6706](https://github.com/kunchenguid/backpass/commit/b0e6706e72e7fcc45866508a4b3bef6860a01f06))
* stop scheduling analysis after a fatal worker error ([#180](https://github.com/kunchenguid/backpass/issues/180)) ([1418cbd](https://github.com/kunchenguid/backpass/commit/1418cbdb4d83d21b3dfdff42f018a4bc207db3fc))

## [0.1.30](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.29...backpass-v0.1.30) (2026-09-28)


### Bug Fixes

* **acpx:** retry timed-out adapter verification instead of aborting the run ([#168](https://github.com/kunchenguid/backpass/issues/168)) ([fd29d96](https://github.com/kunchenguid/backpass/commit/fd29d96ab8fb3aa1decb2c664fd4d32b8d7a90b1))

## [0.1.29](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.28...backpass-v0.1.29) (2026-09-28)


### Features

* **apply:** keep reworded rejected edits suppressed and record optional reject reasons ([#162](https://github.com/kunchenguid/backpass/issues/162)) ([9e2f0ce](https://github.com/kunchenguid/backpass/commit/9e2f0ce5279fc4f6300e4e6b182441074d7f5f71))
* train named nested memory files in monorepos ([#159](https://github.com/kunchenguid/backpass/issues/159)) ([87a79fb](https://github.com/kunchenguid/backpass/commit/87a79fb6f9cd6754203b4584978687e06f824e02))


### Bug Fixes

* **discovery:** include Hermes TUI sessions with absolute cwd ([#146](https://github.com/kunchenguid/backpass/issues/146)) ([0cdf949](https://github.com/kunchenguid/backpass/commit/0cdf949cac77b4cdf870c30fa98c2038753db23e))

## [0.1.28](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.27...backpass-v0.1.28) (2026-09-25)


### Bug Fixes

* **redact:** stop secret redaction from eating benign tool arguments ([#153](https://github.com/kunchenguid/backpass/issues/153)) ([7bd9150](https://github.com/kunchenguid/backpass/commit/7bd9150cf281cb56fc8e7cae1441a7a7fd26f042))

## [0.1.27](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.26...backpass-v0.1.27) (2026-09-24)


### Bug Fixes

* **acpx:** report acpx budget kills as timeouts, not empty-output ([#145](https://github.com/kunchenguid/backpass/issues/145)) ([b295a2d](https://github.com/kunchenguid/backpass/commit/b295a2d1d999fa5272e498176dd2cfce752e094b))

## [0.1.26](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.25...backpass-v0.1.26) (2026-09-21)


### Features

* **config:** add skillSearchPaths for read-only awareness of shared skill libraries ([#138](https://github.com/kunchenguid/backpass/issues/138)) ([2bade32](https://github.com/kunchenguid/backpass/commit/2bade325f15b0fb0ed087245e045a6979961f738))

## [0.1.25](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.24...backpass-v0.1.25) (2026-09-18)


### Bug Fixes

* **skills:** preserve real Claude skills directories ([#136](https://github.com/kunchenguid/backpass/issues/136)) ([158dcd6](https://github.com/kunchenguid/backpass/commit/158dcd6343291d90f4eb3119402aa58dcf128326))

## [0.1.24](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.23...backpass-v0.1.24) (2026-09-16)


### Bug Fixes

* **config:** preserve global agent pins after init ([#137](https://github.com/kunchenguid/backpass/issues/137)) ([7d92241](https://github.com/kunchenguid/backpass/commit/7d922418138ea7089c5469130fa94ecbde2e87b4))

## [0.1.23](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.22...backpass-v0.1.23) (2026-09-16)


### Bug Fixes

* **acpx:** stop discarding stderr on empty-output classification ([#131](https://github.com/kunchenguid/backpass/issues/131)) ([4f5a684](https://github.com/kunchenguid/backpass/commit/4f5a684a4f3130ab5676b1ba26ec9928eca92287))
* **apply:** compare skillsDir by resolved logical path and drop placeholder failure locations ([#133](https://github.com/kunchenguid/backpass/issues/133)) ([dc4124d](https://github.com/kunchenguid/backpass/commit/dc4124d342d18a4ea523483eb3bdd7d0c693424c))
* **synthesize:** count stray edit-turn writes as touched ([#132](https://github.com/kunchenguid/backpass/issues/132)) ([dbaeced](https://github.com/kunchenguid/backpass/commit/dbaeced54538bb5bdd8e27c59f5eb8307e4f1109))

## [0.1.22](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.21...backpass-v0.1.22) (2026-09-13)


### Features

* **discovery:** collect sessions from remote machines over SSH ([#124](https://github.com/kunchenguid/backpass/issues/124)) ([fa712a0](https://github.com/kunchenguid/backpass/commit/fa712a07e928ae392f1c489788387a3fe4724e81))

## [0.1.21](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.20...backpass-v0.1.21) (2026-09-12)


### Bug Fixes

* **acpx:** fall through the agent ladder on clean-exit empty output ([#122](https://github.com/kunchenguid/backpass/issues/122)) ([764ed95](https://github.com/kunchenguid/backpass/commit/764ed9551ec68dc88b7b6a424e028d1a4c122b29))

## [0.1.20](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.19...backpass-v0.1.20) (2026-09-10)


### Bug Fixes

* **analyze:** discard evidence quotes that do not appear in the distilled trace ([#118](https://github.com/kunchenguid/backpass/issues/118)) ([7d171f7](https://github.com/kunchenguid/backpass/commit/7d171f750003fb7921824c88a652ed766aff83ce))

## [0.1.19](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.18...backpass-v0.1.19) (2026-09-07)


### Bug Fixes

* **skills:** see and stage skills that are symlinked into the loaded directory ([#113](https://github.com/kunchenguid/backpass/issues/113)) ([4e67dcd](https://github.com/kunchenguid/backpass/commit/4e67dcd7e3d5e17f9fb84deee45d65d4763de954))

## [0.1.18](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.17...backpass-v0.1.18) (2026-09-04)


### Features

* add user-level memory scope ([#101](https://github.com/kunchenguid/backpass/issues/101)) ([be2633a](https://github.com/kunchenguid/backpass/commit/be2633a6ab3552582b8e30bc418a86e5a61e44a7))
* **apply:** unify funnel from findings to proposed edits ([#104](https://github.com/kunchenguid/backpass/issues/104)) ([aa714d1](https://github.com/kunchenguid/backpass/commit/aa714d1d5debe9b1ea39818245411a2563eac3de))
* let runs target one memory file or skill ([#108](https://github.com/kunchenguid/backpass/issues/108)) ([5392421](https://github.com/kunchenguid/backpass/commit/5392421a7a5e892025e10e7f49721c77e0a1f43b))


### Bug Fixes

* **acpx:** send --agent session prompts through the prompt subcommand ([#100](https://github.com/kunchenguid/backpass/issues/100)) ([d9610ea](https://github.com/kunchenguid/backpass/commit/d9610eaae2bfb23fca92804ea468b2d1cf579a81))
* **acpx:** surface opencode stderr on exec and session-prompt failures ([#109](https://github.com/kunchenguid/backpass/issues/109)) ([e167503](https://github.com/kunchenguid/backpass/commit/e167503bfa58d583f815c00742f98973721e1ac7))
* allow acpx adapters to finish cold starts ([#110](https://github.com/kunchenguid/backpass/issues/110)) ([46a80e1](https://github.com/kunchenguid/backpass/commit/46a80e1415c1a8aa156c53f5a077ff37e380a755))
* count only fold-issued sources toward session floors ([#105](https://github.com/kunchenguid/backpass/issues/105)) ([093921b](https://github.com/kunchenguid/backpass/commit/093921bf2f72b9383af34feef2836caf6285ac37))
* preserve stable evidence session identities ([#106](https://github.com/kunchenguid/backpass/issues/106)) ([c4eb1fa](https://github.com/kunchenguid/backpass/commit/c4eb1fa505d0146b0853ff7d160cd88926cd7216))
* require corroboration for every always-loaded edit ([#103](https://github.com/kunchenguid/backpass/issues/103)) ([e63f555](https://github.com/kunchenguid/backpass/commit/e63f555c175911a521b3a34652a6c049f1378bb9))
* **skills:** honor configured Claude skills directory ([#96](https://github.com/kunchenguid/backpass/issues/96)) ([b20c40c](https://github.com/kunchenguid/backpass/commit/b20c40c0e2578ae3f0f7e0af45a4468a9a2e7e20))

## [0.1.17](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.16...backpass-v0.1.17) (2026-08-31)


### Bug Fixes

* **skills:** parse YAML block-scalar descriptions correctly ([#94](https://github.com/kunchenguid/backpass/issues/94)) ([e957398](https://github.com/kunchenguid/backpass/commit/e957398734211ce4939a9de055862c1ce96a246b))

## [0.1.16](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.15...backpass-v0.1.16) (2026-08-31)


### Bug Fixes

* resolve ambiguous model ids by provider auth type ([#90](https://github.com/kunchenguid/backpass/issues/90)) ([698d57f](https://github.com/kunchenguid/backpass/commit/698d57f79c471d86ab1cb3c44a36408daaeecb72))
* select OpenCode variants via session-local ACP effort ([#73](https://github.com/kunchenguid/backpass/issues/73)) ([80b6834](https://github.com/kunchenguid/backpass/commit/80b683400a107d4e2dee88b5bfcaec410690a391))
* **subprocess:** launch windows npm shims through the command interpreter ([#93](https://github.com/kunchenguid/backpass/issues/93)) ([9ea9da2](https://github.com/kunchenguid/backpass/commit/9ea9da2c606288e2e98afe88d249f12c96d3583c))

## [0.1.15](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.14...backpass-v0.1.15) (2026-08-30)


### Features

* add existing-skill extracts and memory moves ([#83](https://github.com/kunchenguid/backpass/issues/83)) ([8527339](https://github.com/kunchenguid/backpass/commit/8527339a2c73cb3b3b399d88ca7c964f02274929))
* classify and balance interactive corpus sessions ([#85](https://github.com/kunchenguid/backpass/issues/85)) ([f887a32](https://github.com/kunchenguid/backpass/commit/f887a320aeb5764e928b6f2fceb1f85142424eb7))
* report cross-surface skill duplication ([#81](https://github.com/kunchenguid/backpass/issues/81)) ([13f05f8](https://github.com/kunchenguid/backpass/commit/13f05f83b5882de433c579eab05431028fde6071))
* split oversized paragraphs for precise attribution ([#88](https://github.com/kunchenguid/backpass/issues/88)) ([8c040dc](https://github.com/kunchenguid/backpass/commit/8c040dcbc52d8dc20a9d2036c6f6684655c785b8))
* treat project skills as improvable memory ([#72](https://github.com/kunchenguid/backpass/issues/72)) ([d8cbdb6](https://github.com/kunchenguid/backpass/commit/d8cbdb68ca20a9ad6626810e0c24a576e43223c7))


### Bug Fixes

* decide gap cluster domains after grouping ([#87](https://github.com/kunchenguid/backpass/issues/87)) ([71a96c8](https://github.com/kunchenguid/backpass/commit/71a96c826f0ddd2ac2ecdaff327ce350d4019d51))
* **discovery:** find sessions in sibling clones ([#84](https://github.com/kunchenguid/backpass/issues/84)) ([6cbb5b2](https://github.com/kunchenguid/backpass/commit/6cbb5b2c7e1acf56990507d8cd39545683b63046))
* enable synthesis harness write access ([#82](https://github.com/kunchenguid/backpass/issues/82)) ([698b0b8](https://github.com/kunchenguid/backpass/commit/698b0b8fb0f97444f8355264206f1f153dcae8a6))
* **prompts:** classify orchestrator repo gaps as project ([#78](https://github.com/kunchenguid/backpass/issues/78)) ([7b1a915](https://github.com/kunchenguid/backpass/commit/7b1a915aa757a632b8ae053eca773ab79158c17b))
* retry transient harness capability probes ([#80](https://github.com/kunchenguid/backpass/issues/80)) ([658c2e9](https://github.com/kunchenguid/backpass/commit/658c2e9621c43b82e0c7b43c462ac137f91562e4))

## [0.1.14](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.13...backpass-v0.1.14) (2026-08-29)


### Features

* **apply:** visualize gap evidence funnel on review board ([#69](https://github.com/kunchenguid/backpass/issues/69)) ([627b6d3](https://github.com/kunchenguid/backpass/commit/627b6d39cd372038b6d8db667d84cbf4fc4efb01))

## [0.1.13](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.12...backpass-v0.1.13) (2026-08-29)


### Features

* **prompts:** make gap domain a causal test and soften the extraction nudge ([#67](https://github.com/kunchenguid/backpass/issues/67)) ([4ae93a6](https://github.com/kunchenguid/backpass/commit/4ae93a6aa00cab2ad128ae0cb342f8f39e06b7b7))

## [0.1.12](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.11...backpass-v0.1.12) (2026-08-28)


### Features

* judge gap identity and safeguard instruction removals ([#64](https://github.com/kunchenguid/backpass/issues/64)) ([85d5105](https://github.com/kunchenguid/backpass/commit/85d51055568cd106f516acca0df5f20603ede939))


### Bug Fixes

* keep EOF-reaching mixed removals merged ([#65](https://github.com/kunchenguid/backpass/issues/65)) ([8b5f625](https://github.com/kunchenguid/backpass/commit/8b5f6252c728f6181d56f889b699b2a890cf2471))
* make transcript sampling deterministic and sticky ([#62](https://github.com/kunchenguid/backpass/issues/62)) ([d177b06](https://github.com/kunchenguid/backpass/commit/d177b06a5fa6767391f17a26efeab862b4bc258a))

## [0.1.11](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.10...backpass-v0.1.11) (2026-08-28)


### Bug Fixes

* **apply:** stop replacement-token expansion from corrupting apply.html ([#60](https://github.com/kunchenguid/backpass/issues/60)) ([f5d3c3a](https://github.com/kunchenguid/backpass/commit/f5d3c3addec9d3b9b900ab000da7fb01019a3187))

## [0.1.10](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.9...backpass-v0.1.10) (2026-08-28)


### Bug Fixes

* **discovery:** discover BB-managed Pi sessions ([#58](https://github.com/kunchenguid/backpass/issues/58)) ([450c1a2](https://github.com/kunchenguid/backpass/commit/450c1a20ecb1a4655c56adcbea20c5f12b9d98f2))

## [0.1.9](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.8...backpass-v0.1.9) (2026-08-28)


### Bug Fixes

* scope evidence reuse to the current memory hash ([#54](https://github.com/kunchenguid/backpass/issues/54)) ([2fc6dbf](https://github.com/kunchenguid/backpass/commit/2fc6dbf48648f921879935a521535f55d77205e4))

## [0.1.8](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.7...backpass-v0.1.8) (2026-08-27)


### Bug Fixes

* correct synthesis orchestration and apply rollback ([#52](https://github.com/kunchenguid/backpass/issues/52)) ([8466e65](https://github.com/kunchenguid/backpass/commit/8466e65b59874ea5ab045664591244296b6d9518))
* keep harness model and effort overrides invocation-scoped ([#49](https://github.com/kunchenguid/backpass/issues/49)) ([c6d9ba8](https://github.com/kunchenguid/backpass/commit/c6d9ba8179e16fb9f720213afd705b5acb2ec88f))

## [0.1.7](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.6...backpass-v0.1.7) (2026-08-27)


### Bug Fixes

* **apply:** prevent partial writes from stale proposals ([#47](https://github.com/kunchenguid/backpass/issues/47)) ([2f0df29](https://github.com/kunchenguid/backpass/commit/2f0df29e3394a8321502e79774b04024fe84419b))

## [0.1.6](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.5...backpass-v0.1.6) (2026-08-26)


### Bug Fixes

* **apply:** reopen ended Lavish review sessions ([#45](https://github.com/kunchenguid/backpass/issues/45)) ([b0d92bc](https://github.com/kunchenguid/backpass/commit/b0d92bcb4f17175b9fcb24787ac1304991392d23))

## [0.1.5](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.4...backpass-v0.1.5) (2026-08-25)


### Bug Fixes

* **discovery:** scan CLAUDE_CONFIG_DIR alongside the default claude store ([#41](https://github.com/kunchenguid/backpass/issues/41)) ([8d0b423](https://github.com/kunchenguid/backpass/commit/8d0b423a164bcd691b9ae6ac6fbcf3f1435aff3e))

## [0.1.4](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.3...backpass-v0.1.4) (2026-08-25)


### Bug Fixes

* **apply:** revalidate accepted edit subsets ([#38](https://github.com/kunchenguid/backpass/issues/38)) ([1f473f2](https://github.com/kunchenguid/backpass/commit/1f473f22c30128cb4b2c27f7fe0e7910f9c6787c))

## [0.1.3](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.2...backpass-v0.1.3) (2026-08-23)


### Bug Fixes

* **discovery:** recover Hermes v26 CLI sessions ([#28](https://github.com/kunchenguid/backpass/issues/28)) ([37457f9](https://github.com/kunchenguid/backpass/commit/37457f96c0907c746b983c511f0b4ba158834c7b))

## [0.1.2](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.1...backpass-v0.1.2) (2026-08-23)


### Features

* **discovery:** add Hermes transcript support ([#26](https://github.com/kunchenguid/backpass/issues/26)) ([0445c33](https://github.com/kunchenguid/backpass/commit/0445c330701fc82686c1113483ea35c9226da1e1))

## [0.1.1](https://github.com/kunchenguid/backpass/compare/backpass-v0.1.0...backpass-v0.1.1) (2026-08-23)


### Features

* initial commit ([df73d32](https://github.com/kunchenguid/backpass/commit/df73d3255b0a78b4d5ada0f3f733c4a131cb59ae))


### Bug Fixes

* **apply:** open the review surface in the browser, announce waits once, and strip the quoted URL ([#18](https://github.com/kunchenguid/backpass/issues/18)) ([b922b9e](https://github.com/kunchenguid/backpass/commit/b922b9e4a57cee592684c8146f5ffbab6ab5fce7))
