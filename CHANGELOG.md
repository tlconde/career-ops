# Changelog

## [1.12.0](https://github.com/tlconde/career-ops/compare/career-ops-v1.11.0...career-ops-v1.12.0) (2026-06-17)


### Features

* adapt contacto mode by contact type (recruiter/HM/peer/interviewer) ([40cc702](https://github.com/tlconde/career-ops/commit/40cc702dd6a087814c48af2da7117054bc9a743a))
* add --min-score flag to batch runner ([#249](https://github.com/tlconde/career-ops/issues/249)) ([06405bf](https://github.com/tlconde/career-ops/commit/06405bfe9a914aaab9c429f852e1b130700a9482))
* add {{PHONE}} placeholder to CV template ([#287](https://github.com/tlconde/career-ops/issues/287)) ([19b4148](https://github.com/tlconde/career-ops/commit/19b4148c1d8c4a7f8264b75ecfd07616388980b1))
* add Block G — posting legitimacy assessment ([fa8b84e](https://github.com/tlconde/career-ops/commit/fa8b84e0d58ed8683f2e84a2eabc93becf7dcbf7))
* add Claude Code plugin manifests (path-stable) ([0c7a606](https://github.com/tlconde/career-ops/commit/0c7a6066b4cf49537d25a2fb73bacdf33ba421df))
* add first-class OpenCode support alongside Claude Code ([#707](https://github.com/tlconde/career-ops/issues/707)) ([482e6c6](https://github.com/tlconde/career-ops/commit/482e6c6e10f4e4a0ddb7df2d77976d37095c57c9))
* add follow-up cadence tracker mode ([3217e77](https://github.com/tlconde/career-ops/commit/3217e77ef83e0aaec50f507d4337c92012c35139))
* add Gemini CLI native integration and evaluator script  ([#349](https://github.com/tlconde/career-ops/issues/349)) ([fa477e8](https://github.com/tlconde/career-ops/commit/fa477e85746ab91e11f790b880529b3f0080bb59))
* add Gemini CLI native integration and evaluator script (closes [#344](https://github.com/tlconde/career-ops/issues/344)) ([fa477e8](https://github.com/tlconde/career-ops/commit/fa477e85746ab91e11f790b880529b3f0080bb59))
* add GitHub Actions CI + auto-labeler + welcome bot + /run skill ([d8eda9b](https://github.com/tlconde/career-ops/commit/d8eda9b90fbdb77bc4f770667ad57fa2e3a0ee39))
* add LaTeX/Overleaf CV export mode with pdflatex compilation ([#362](https://github.com/tlconde/career-ops/issues/362)) ([db18a62](https://github.com/tlconde/career-ops/commit/db18a629c5c2db50ecc1ffa44c9af180cdff7ff1))
* add LaTeX/Overleaf CV export mode with pdflatex compilation (closes [#47](https://github.com/tlconde/career-ops/issues/47)) ([db18a62](https://github.com/tlconde/career-ops/commit/db18a629c5c2db50ecc1ffa44c9af180cdff7ff1))
* add Nix flake devshell with Playwright support ([a364046](https://github.com/tlconde/career-ops/commit/a364046f37337477c4e59bf3cede2407f176c16f))
* add npx career-ops scaffolder for one-command install ([#856](https://github.com/tlconde/career-ops/issues/856)) ([d527ead](https://github.com/tlconde/career-ops/commit/d527eadebdf176be598ec929776a2c48e3108854)), closes [#855](https://github.com/tlconde/career-ops/issues/855)
* add OpenCode slash commands for career-ops ([#67](https://github.com/tlconde/career-ops/issues/67)) ([92137d4](https://github.com/tlconde/career-ops/commit/92137d4e1fd878d6ed7f53f115aa13ecae254e08))
* add scan.mjs — zero-token portal scanner ([a7cd72c](https://github.com/tlconde/career-ops/commit/a7cd72c905b8814a4fc6b8d7d2c54e7d14c272a4))
* add structured machine summaries to evaluations ([#444](https://github.com/tlconde/career-ops/issues/444)) ([76c9ffe](https://github.com/tlconde/career-ops/commit/76c9ffea72b757527a70751b780ac0ebe33e3b5e))
* add Ukrainian language and market support ([#323](https://github.com/tlconde/career-ops/issues/323)) ([1768ce9](https://github.com/tlconde/career-ops/commit/1768ce9b61ecd73c350f89931f685ec6cfb792c7))
* add writing-samples folder for AI-detection-evading voice calibration ([46c3b45](https://github.com/tlconde/career-ops/commit/46c3b45ff2ef050aeb3ba22056a403bad50e3eed))
* **apply:** add preflight liveness and role-match gate ([#887](https://github.com/tlconde/career-ops/issues/887)) ([711f87c](https://github.com/tlconde/career-ops/commit/711f87c1c057378044cbb222cb8efa7d0baf83c5))
* **batch:** add --model flag to batch-runner.sh ([#504](https://github.com/tlconde/career-ops/issues/504)) ([fc6478d](https://github.com/tlconde/career-ops/commit/fc6478d6b96668344d1cd20f46ae35c51a03c997))
* **batch:** pause batch runner on Claude session limits ([#874](https://github.com/tlconde/career-ops/issues/874)) ([d9efb5b](https://github.com/tlconde/career-ops/commit/d9efb5b77e6b8e9aec2bdff69cb245db28646e73))
* **cover:** add cover letter generation mode ([#807](https://github.com/tlconde/career-ops/issues/807)) ([f7ded81](https://github.com/tlconde/career-ops/commit/f7ded815924a404c473943fd141e909b7f9c7f1e))
* **cover:** add optional salutation/greeting to cover letters ([#1010](https://github.com/tlconde/career-ops/issues/1010)) ([f038542](https://github.com/tlconde/career-ops/commit/f038542ac9af2aa83aca98524387c61b4d96bc80))
* **cover:** load _profile.md so personalization governs the letter ([#1012](https://github.com/tlconde/career-ops/issues/1012)) ([4337481](https://github.com/tlconde/career-ops/commit/433748166281a6d21f488cb195a064decc365a62))
* **cv:** add build-cv-latex.mjs structured JSON to LaTeX renderer ([#905](https://github.com/tlconde/career-ops/issues/905)) ([8b86e87](https://github.com/tlconde/career-ops/commit/8b86e871df2d74333a2980e1bb0abe3cc83a0233))
* **cv:** add cv.output_format to route between html and latex generation ([0828783](https://github.com/tlconde/career-ops/commit/082878305bda01df085fe1988cc0ac293d243f76))
* **dashboard:** /-key live search across pipeline rows ([#526](https://github.com/tlconde/career-ops/issues/526)) ([862d6a0](https://github.com/tlconde/career-ops/commit/862d6a0bdb5582e25bfb26418d5f0a94b0faf76f))
* **dashboard:** add Catppuccin Latte light theme with auto-detection ([67b695b](https://github.com/tlconde/career-ops/commit/67b695b15ac6ac5eb2230b308f3b92ddc3966f3e))
* **dashboard:** add manual refresh shortcut ([#246](https://github.com/tlconde/career-ops/issues/246)) ([b448784](https://github.com/tlconde/career-ops/commit/b4487840d88b9fefe606fe42c7bf843ecb8d7f62))
* **dashboard:** add progress analytics screen ([78997fa](https://github.com/tlconde/career-ops/commit/78997fad9f31d3962a901dffb7ee2b8ffa4c9218))
* **dashboard:** add rejected and discarded pipeline tabs ([222167c](https://github.com/tlconde/career-ops/commit/222167c8f57696839eda06a85cbba2d7e309b03c))
* **dashboard:** add vim motions to pipeline screen ([#262](https://github.com/tlconde/career-ops/issues/262)) ([1e6b1c8](https://github.com/tlconde/career-ops/commit/1e6b1c8e52689de9ef1f5a794db8df6542537e0a))
* **dashboard:** aligned tables and markdown syntax rendering in viewer ([ff821c3](https://github.com/tlconde/career-ops/commit/ff821c3424a008b9e17a4cbc6a59e2c233ad5f47))
* **dashboard:** keep discard reason visible in pipeline preview ([#914](https://github.com/tlconde/career-ops/issues/914)) ([0d13871](https://github.com/tlconde/career-ops/commit/0d13871f63db5b3d5021fd4f47edef0de6db2d09))
* **dashboard:** show tracker IDs in pipeline list ([e572033](https://github.com/tlconde/career-ops/commit/e572033eb1c6864836fa751f0c9205d15d8240c3))
* **dashboard:** sortable Location, Pay, and Last-contact columns in pipeline view ([#798](https://github.com/tlconde/career-ops/issues/798)) ([ce9ff8f](https://github.com/tlconde/career-ops/commit/ce9ff8fad5faa1acab4d03ef6bae6ff866c02c6a))
* dockerize project for hosts blocked from native Playwright install ([#625](https://github.com/tlconde/career-ops/issues/625)) ([5a2eea8](https://github.com/tlconde/career-ops/commit/5a2eea8a10a2d14e77684cb4fcfccc01c9df7342))
* **doctor:** adopt doctor --json as the single onboarding state source ([#888](https://github.com/tlconde/career-ops/issues/888)) ([25739bb](https://github.com/tlconde/career-ops/commit/25739bb863cffa63abdfa4d8ad4b827a9ebd11c3))
* **doctor:** warn when Playwright MCP tools are not configured ([#938](https://github.com/tlconde/career-ops/issues/938)) ([22cb7f7](https://github.com/tlconde/career-ops/commit/22cb7f7b7acb1b812cace8846fa8e015c5f41c6d))
* expand portals.example.yml with 8 dev-tools companies + 23 search queries ([#140](https://github.com/tlconde/career-ops/issues/140)) ([ccc4b7f](https://github.com/tlconde/career-ops/commit/ccc4b7f4c238b80f875796cadced3f02dc8cac9c))
* **followup:** read cadence settings from profile.yml ([#889](https://github.com/tlconde/career-ops/issues/889)) ([0bc06a6](https://github.com/tlconde/career-ops/commit/0bc06a65c9cb37eb740696ed19ae68b32169f524))
* **i18n:** add full Arabic language support and modes ([#764](https://github.com/tlconde/career-ops/issues/764)) ([bd89967](https://github.com/tlconde/career-ops/commit/bd899670c6689cff64e6363adb1e373b5c557edc))
* **i18n:** add Japanese README + language modes for Japan market ([8496c2d](https://github.com/tlconde/career-ops/commit/8496c2d22871ec596d879256751eb25411229197))
* **i18n:** add Turkish (TR) language modes ([#341](https://github.com/tlconde/career-ops/issues/341)) ([4b5822c](https://github.com/tlconde/career-ops/commit/4b5822cad2097e9f70df2bef78f8eee378bea89d))
* **interview-prep:** split prep by interviewer audience ([#489](https://github.com/tlconde/career-ops/issues/489)) ([3256ecf](https://github.com/tlconde/career-ops/commit/3256ecf92433df822a7f9ab50ee93a75f3380e28))
* **latex:** add tectonic engine auto-detect with pdflatex fallback ([0b41f2f](https://github.com/tlconde/career-ops/commit/0b41f2f16e246e8eab9509c126167d5420ee99e3))
* make PDF auto-generation configurable via auto_pdf_score_threshold ([#715](https://github.com/tlconde/career-ops/issues/715)) ([4f96524](https://github.com/tlconde/career-ops/commit/4f96524d84c67d6ae33146fbd33d1bc63170d908))
* **modes:** add interactive interview onboarding subcommand ([#909](https://github.com/tlconde/career-ops/issues/909)) ([a794f75](https://github.com/tlconde/career-ops/commit/a794f753614382ff9103db2cbfab11691a32dc32))
* multi-CLI support via open agent skill standard ([#572](https://github.com/tlconde/career-ops/issues/572)) ([ccfc2d2](https://github.com/tlconde/career-ops/commit/ccfc2d2e0499bdb18cbebcc6ea8ff31212b3e434))
* **pdf:** render Japanese CVs with a lang="ja" CJK font fallback ([#1053](https://github.com/tlconde/career-ops/issues/1053)) ([1eefe97](https://github.com/tlconde/career-ops/commit/1eefe971aba50c2e36516b89232172764b8abe22))
* **portals:** add Canada/Vancouver and automation companies to example template ([6846a50](https://github.com/tlconde/career-ops/commit/6846a50dfa6526857ff7430ed3dd7dfbe04d33c6))
* **scan:** add --rediscover-404 fallback for moved tracked postings ([#808](https://github.com/tlconde/career-ops/issues/808)) ([ca05e94](https://github.com/tlconde/career-ops/commit/ca05e94bb7c9a7bfb65110687b9f8892911e2e24))
* **scan:** add --verify flag to drop expired postings before pipeline append ([#487](https://github.com/tlconde/career-ops/issues/487)) ([47a98af](https://github.com/tlconde/career-ops/commit/47a98afbfe15d042ea15c67442674871cd239295))
* **scan:** add configurable salary filtering to the zero-token scanner ([#677](https://github.com/tlconde/career-ops/issues/677)) ([577eec8](https://github.com/tlconde/career-ops/commit/577eec8471574d76ca4b35ba08cb2e0fed963dc1))
* **scan:** add local-parser provider and agent skip rules ([#595](https://github.com/tlconde/career-ops/issues/595)) ([ff7b0a2](https://github.com/tlconde/career-ops/commit/ff7b0a2b36313f31db30210861c53d95fbbefdb4))
* **scan:** add optional always_allow tier to location_filter ([#652](https://github.com/tlconde/career-ops/issues/652)) ([3c7bfc7](https://github.com/tlconde/career-ops/commit/3c7bfc761536168dda4d14532ed05dcbbcb8a267)), closes [#650](https://github.com/tlconde/career-ops/issues/650)
* **scan:** add portals.yml schema validator ([#886](https://github.com/tlconde/career-ops/issues/886)) ([3a90f4b](https://github.com/tlconde/career-ops/commit/3a90f4b7573d25a096e0c3ee714563de17428923))
* **scan:** add scan-ats-full.mjs — reverse-discover jobs from public ATS APIs ([#746](https://github.com/tlconde/career-ops/issues/746)) ([050c38c](https://github.com/tlconde/career-ops/commit/050c38c11a8dd1c1b1bed0a8884358b26ed9adf8))
* **scan:** add scan-history TTL and recheck policy ([#895](https://github.com/tlconde/career-ops/issues/895)) ([0279eb2](https://github.com/tlconde/career-ops/commit/0279eb24ff995e97ee617899049000f7d44b18ef))
* **scan:** add SolidJobs provider and job_boards support ([#853](https://github.com/tlconde/career-ops/issues/853)) ([ff5b311](https://github.com/tlconde/career-ops/commit/ff5b31170c952987b49c149cfedd49a62b46b7b5))
* **scan:** add Workable, SmartRecruiters, Recruitee ATS parsers ([#653](https://github.com/tlconde/career-ops/issues/653)) ([bd724a0](https://github.com/tlconde/career-ops/commit/bd724a014500de51fdacf0730c522517d465f0e3)), closes [#651](https://github.com/tlconde/career-ops/issues/651)
* **scan:** optional location_filter in portals.yml + persist location to scan-history ([#570](https://github.com/tlconde/career-ops/issues/570)) ([bc73cd3](https://github.com/tlconde/career-ops/commit/bc73cd34491df2d744355e329b3e47a209d84d31))
* **tracker:** map tracker columns by header name ([#954](https://github.com/tlconde/career-ops/issues/954)) ([c0ae92b](https://github.com/tlconde/career-ops/commit/c0ae92b77db78f5d43a8acdcd5183924f9c0ec6d))
* **tracker:** SQLite derived index over applications.md — phase 1 ([#919](https://github.com/tlconde/career-ops/issues/919)) ([6ed5373](https://github.com/tlconde/career-ops/commit/6ed53735b74a1e0fbc4b541668c40a82636e2b76))


### Bug Fixes

* 10 bug fixes — resource leaks, command injection, Unicode, navigation ([43cdb93](https://github.com/tlconde/career-ops/commit/43cdb93f0dc24fe034bf5e8f0e79b297769d3790))
* add data/ fallback to UpdateApplicationStatus ([#55](https://github.com/tlconde/career-ops/issues/55)) ([fcf051e](https://github.com/tlconde/career-ops/commit/fcf051e3bf4d4b1da924518ded31c7e139be5174))
* add stopword filtering and overlap ratio to roleMatch ([#248](https://github.com/tlconde/career-ops/issues/248)) ([41233db](https://github.com/tlconde/career-ops/commit/41233db55ba5e9e8fbc5f9b4c29ae3ebf73a63b7))
* align portals.example.yml indentation for new companies ([f5be20a](https://github.com/tlconde/career-ops/commit/f5be20a9519bf0f9c4b9cde5419e90e7fadab3fd))
* **apply:** preserve form field contracts ([#821](https://github.com/tlconde/career-ops/issues/821)) ([bd0eaf2](https://github.com/tlconde/career-ops/commit/bd0eaf269582b23a047a6f74d3e5653e75620ce1))
* **batch:** append profile context to worker prompts ([#815](https://github.com/tlconde/career-ops/issues/815)) ([98d07de](https://github.com/tlconde/career-ops/commit/98d07dedee7a24a539fc344877d1725ccfb569dc))
* **batch:** isolate workers from inherited MCP to prevent parallel deadlock ([#809](https://github.com/tlconde/career-ops/issues/809)) ([17b06fa](https://github.com/tlconde/career-ops/commit/17b06faefcd4a8dbcf6e84db39b1178f6219ea6d))
* **batch:** stop after min-score skip instead of falling through to completed ([#873](https://github.com/tlconde/career-ops/issues/873)) ([0265c8b](https://github.com/tlconde/career-ops/commit/0265c8b08547ee52aa57866b58ba5bab3a02e24e))
* **batch:** wait and retry batch workers on rate limits ([#816](https://github.com/tlconde/career-ops/issues/816)) ([5acaa8c](https://github.com/tlconde/career-ops/commit/5acaa8c5863e8329d66248bafd096e4771d08227)), closes [#505](https://github.com/tlconde/career-ops/issues/505)
* **batch:** workers read modes/_profile.md and config/profile.yml ([#537](https://github.com/tlconde/career-ops/issues/537)) ([cc060d3](https://github.com/tlconde/career-ops/commit/cc060d358693e092b8e7bf4119fcafad928a86fd)), closes [#534](https://github.com/tlconde/career-ops/issues/534)
* **ci:** correct first-interaction@v3 input names ([e09598c](https://github.com/tlconde/career-ops/commit/e09598c98ff17b4b06966c1aa1c85847639f883f))
* **ci:** gracefully handle missing dependency graph in dependency-review ([#343](https://github.com/tlconde/career-ops/issues/343)) ([acac8ee](https://github.com/tlconde/career-ops/commit/acac8ee50d9a4f839af068f3801446ce9b4342bc))
* **ci:** gracefully handle missing dependency graph in dependency-review workflow ([#352](https://github.com/tlconde/career-ops/issues/352)) ([acac8ee](https://github.com/tlconde/career-ops/commit/acac8ee50d9a4f839af068f3801446ce9b4342bc))
* **ci:** use pull_request_target for labeler on fork PRs ([#260](https://github.com/tlconde/career-ops/issues/260)) ([1f1bb2a](https://github.com/tlconde/career-ops/commit/1f1bb2abb3fde2ce8c86e773e987fce44b30ee37))
* correct _shared.md → _profile.md reference in CUSTOMIZATION.md (closes [#137](https://github.com/tlconde/career-ops/issues/137)) ([2dc5aa7](https://github.com/tlconde/career-ops/commit/2dc5aa76ffee780435caa1019aa75cf94ecb196f))
* correct dashboard launch path in docs ([#80](https://github.com/tlconde/career-ops/issues/80)) ([62996d8](https://github.com/tlconde/career-ops/commit/62996d8cb785072b12d7ac47070f57ae61590609))
* **cv:** align certification org column width across rows ([#931](https://github.com/tlconde/career-ops/issues/931)) ([6fb904f](https://github.com/tlconde/career-ops/commit/6fb904f08ef554468b2b0d7f42266ce1de285dff))
* **dashboard:** report last-contact in calendar days, not hours-since-midnight ([#1057](https://github.com/tlconde/career-ops/issues/1057)) ([32d893d](https://github.com/tlconde/career-ops/commit/32d893dbdf85c673d53674a562d5ec6ec7356e59))
* **dashboard:** resolve tracker-relative report links against the tracker directory ([#780](https://github.com/tlconde/career-ops/issues/780)) ([485c5a4](https://github.com/tlconde/career-ops/commit/485c5a4882ac2ce2ccce59e7d973c72dc02ac1ed)), closes [#779](https://github.com/tlconde/career-ops/issues/779)
* **dashboard:** show dates in pipeline list ([#298](https://github.com/tlconde/career-ops/issues/298)) ([e291cd0](https://github.com/tlconde/career-ops/commit/e291cd0933c013168359a01b39b5fd04947b9b52))
* **dashboard:** width-aware Markdown rendering with table wrapping in viewer ([#513](https://github.com/tlconde/career-ops/issues/513)) ([0c0a918](https://github.com/tlconde/career-ops/commit/0c0a918b6b231e0897e62d5696bc2fa3a5a6e726))
* **deps:** update dotenv to v17 ([#499](https://github.com/tlconde/career-ops/issues/499)) ([d841afc](https://github.com/tlconde/career-ops/commit/d841afcb1d82c7141119180dfdbcc5f56d0583f4))
* **deps:** update npm dependencies to v1.61.0 ([#1023](https://github.com/tlconde/career-ops/issues/1023)) ([de2b598](https://github.com/tlconde/career-ops/commit/de2b598d3986c0a3cfd12e9e2087a263e8da558f))
* **doctor:** single source of truth for onboarding state via doctor --json ([#765](https://github.com/tlconde/career-ops/issues/765)) ([8118855](https://github.com/tlconde/career-ops/commit/8118855b953e3d5c57daa98d8a20292ff739071e))
* ensure data/ and output/ dirs exist before writing in scripts ([#261](https://github.com/tlconde/career-ops/issues/261)) ([8768d0b](https://github.com/tlconde/career-ops/commit/8768d0b6ef651f6ec2cb8e5010bd47bce80ff1ea))
* **eval:** gate dead links before evaluation in oferta and auto-pipeline ([#937](https://github.com/tlconde/career-ops/issues/937)) ([648c7ed](https://github.com/tlconde/career-ops/commit/648c7edeb0598b3bef74b891e635eb3776984908))
* filter expired WebSearch links before they reach the pipeline ([#57](https://github.com/tlconde/career-ops/issues/57)) ([83f5072](https://github.com/tlconde/career-ops/commit/83f5072227a6d3d34053395f84a336b5232ef835))
* **flake:** declare systems so the devShell resolves on macOS ([#848](https://github.com/tlconde/career-ops/issues/848)) ([9ee7418](https://github.com/tlconde/career-ops/commit/9ee7418a4a12830465e8e128db4ab564a0028555)), closes [#334](https://github.com/tlconde/career-ops/issues/334)
* **gemini-eval:** include profile.yml and _profile.md in evaluation ([#618](https://github.com/tlconde/career-ops/issues/618)) ([46f4a60](https://github.com/tlconde/career-ops/commit/46f4a606865f839fa05740cd18506b2c657962fc)), closes [#617](https://github.com/tlconde/career-ops/issues/617)
* **gemini-eval:** redact API key from error logs, harden summary parsing ([#582](https://github.com/tlconde/career-ops/issues/582)) ([6c1b843](https://github.com/tlconde/career-ops/commit/6c1b8437acb3276b9c34304f436770f224a03e2e))
* **gemini-eval:** switch default model to non-deprecated endpoint, surface 429 guidance ([#615](https://github.com/tlconde/career-ops/issues/615)) ([0563eeb](https://github.com/tlconde/career-ops/commit/0563eeb5ca181116d3c1765035807b99d57f48bd)), closes [#614](https://github.com/tlconde/career-ops/issues/614)
* **gemini:** auto-merge Gemini evals into the tracker instead of a manual-edit reminder ([#820](https://github.com/tlconde/career-ops/issues/820)) ([cdc305f](https://github.com/tlconde/career-ops/commit/cdc305f6f3a687aaa441fcd40ca4cc9c2ba1e4de))
* **generate-pdf:** inline local fonts as data: URLs so they actually embed ([#952](https://github.com/tlconde/career-ops/issues/952)) ([1eac723](https://github.com/tlconde/career-ops/commit/1eac723a3e082b62553d8ad4dc6b8aecc5b703da))
* improve default PDF readability ([#85](https://github.com/tlconde/career-ops/issues/85)) ([2c2cdcb](https://github.com/tlconde/career-ops/commit/2c2cdcbc732269f9b4231cb77cc8d5387a908efb))
* **latex:** language-agnostic section validation + CJK guard ([#1054](https://github.com/tlconde/career-ops/issues/1054)) ([efaec72](https://github.com/tlconde/career-ops/commit/efaec7203925c29d7e5be5a81d4dd606fd792c76))
* liveness checks ignore nav/footer Apply text, expired signals win ([9bf01e2](https://github.com/tlconde/career-ops/commit/9bf01e20d44361742b82b76ea3ce4225911b97f6))
* **liveness:** detect closed postings with applications-closed banner variants ([8866a68](https://github.com/tlconde/career-ops/commit/8866a6829b55b2ca458979731ac735857df39473))
* **liveness:** stop false-expiring postings behind anti-bot walls ([#783](https://github.com/tlconde/career-ops/issues/783)) ([a4cff42](https://github.com/tlconde/career-ops/commit/a4cff426d9ab1b40bba27af63e94273316542cc7))
* make tracker report links relative to the tracker file ([#760](https://github.com/tlconde/career-ops/issues/760)) ([#761](https://github.com/tlconde/career-ops/issues/761)) ([3279e9f](https://github.com/tlconde/career-ops/commit/3279e9fb9468d16a7ffd313156692836df9365cd))
* **manifest:** align plugin.json skills field with Claude Code plugin schema ([#612](https://github.com/tlconde/career-ops/issues/612)) ([5d8d9fb](https://github.com/tlconde/career-ops/commit/5d8d9fb228e72160e930c7d4b6ad89d0b4341be6))
* **merge-tracker:** filter seniority and location stopwords + require overlap ratio in roleFuzzyMatch ([cd954de](https://github.com/tlconde/career-ops/commit/cd954de8c712e44f20e696fc9457b37c5a92b9b8))
* **merge-tracker:** preserve short specialty acronyms, require non-baseline overlap ([#634](https://github.com/tlconde/career-ops/issues/634)) ([f935bef](https://github.com/tlconde/career-ops/commit/f935bef3496bf6b5bcc131e5c89fb72689f9b2b9)), closes [#633](https://github.com/tlconde/career-ops/issues/633)
* **merge-tracker:** require company match on exact entry-number dedup ([#867](https://github.com/tlconde/career-ops/issues/867)) ([b2b9f81](https://github.com/tlconde/career-ops/commit/b2b9f816f564a580b592834bd9ce2931c7918957))
* **merge-tracker:** serialize concurrent tracker merges with a filesystem lock ([#941](https://github.com/tlconde/career-ops/issues/941)) ([b026c93](https://github.com/tlconde/career-ops/commit/b026c93280cd2cb547751174036c927756fcdbdc))
* **merge-tracker:** use token-union ratio in roleFuzzyMatch to stop cross-role dedup ([#793](https://github.com/tlconde/career-ops/issues/793)) ([1c61e84](https://github.com/tlconde/career-ops/commit/1c61e84f2f4491d0c135b4aeabce3801e6e60ef1)), closes [#751](https://github.com/tlconde/career-ops/issues/751)
* **modes:** make /career-ops deep respect user language, not JD language ([#568](https://github.com/tlconde/career-ops/issues/568)) ([4aa4f1c](https://github.com/tlconde/career-ops/commit/4aa4f1c92fbcb615ea23d1035cf9db0aa0a99dca))
* **patterns:** parse header-style and Detected-archetype formats in analyze-patterns ([#723](https://github.com/tlconde/career-ops/issues/723)) ([3333e2f](https://github.com/tlconde/career-ops/commit/3333e2fc45d0b613f2c0dc9f77df1d4c0d644d8a))
* **pdf:** don't spell out ambiguous ¥ currency symbol ([d17a43b](https://github.com/tlconde/career-ops/commit/d17a43bbbfd7ca471084c2d6730b017c06332738))
* **pdf:** normalize arrows, middots, and currency symbols for ATS extraction ([#731](https://github.com/tlconde/career-ops/issues/731)) ([a0929ee](https://github.com/tlconde/career-ops/commit/a0929ee5cbd1e758ee02e29e5dd519c0b4aa5eff)), closes [#730](https://github.com/tlconde/career-ops/issues/730)
* **pdf:** reject CV section ordering that diverges from cv.md source ([#817](https://github.com/tlconde/career-ops/issues/817)) ([204ac63](https://github.com/tlconde/career-ops/commit/204ac637a8d996cba47944f4b51ab97d1b4954a3))
* **pdf:** wait for load instead of networkidle during render ([#929](https://github.com/tlconde/career-ops/issues/929)) ([5e55ff8](https://github.com/tlconde/career-ops/commit/5e55ff87ec2be70be97014944bd432f6eb623280))
* **pipeline:** atomic report-number reservation for parallel workers ([#803](https://github.com/tlconde/career-ops/issues/803)) ([c2f3321](https://github.com/tlconde/career-ops/commit/c2f33217a2aa7fa861860aef441fb6ab5f64c025))
* **portals:** update Weights & Biases entry to CoreWeave acquisition ([#493](https://github.com/tlconde/career-ops/issues/493)) ([caffa89](https://github.com/tlconde/career-ops/commit/caffa89f54f997919091dbeddeeefc46bb8142b0))
* **pt:** restore diacritical marks in PT-BR modes ([#358](https://github.com/tlconde/career-ops/issues/358)) ([93f9955](https://github.com/tlconde/career-ops/commit/93f9955647f380acc3ad4099c431817b37972f90))
* **pt:** restore diacritical marks in PT-BR modes ([#359](https://github.com/tlconde/career-ops/issues/359)) ([93f9955](https://github.com/tlconde/career-ops/commit/93f9955647f380acc3ad4099c431817b37972f90))
* register the career-ops skill in Claude Code via user_invocable key ([#801](https://github.com/tlconde/career-ops/issues/801)) ([45a14d3](https://github.com/tlconde/career-ops/commit/45a14d3893f7ce1b5975ce1938160754dc81828f)), closes [#763](https://github.com/tlconde/career-ops/issues/763)
* **release:** auto-sync VERSION via release-please generic extra-file ([97e38f3](https://github.com/tlconde/career-ops/commit/97e38f3b0394be033c20bc8ae3af9f60d057c201))
* **release:** sync VERSION and package.json via release-please-config ([ea551a5](https://github.com/tlconde/career-ops/commit/ea551a5675b6fd750ef298da084800a5ce9fa9fd))
* **release:** sync VERSION file to 1.7.0 ([44774d1](https://github.com/tlconde/career-ops/commit/44774d1ba2b7bb2d8cf1a8a9b596e9d1cfff563e))
* **release:** sync VERSION file to 1.7.1 ([989c030](https://github.com/tlconde/career-ops/commit/989c030f944df8a5dc0394717fa894a8ef949b7b))
* **release:** sync VERSION file to 1.8.0 ([838c894](https://github.com/tlconde/career-ops/commit/838c89419a87706374c2f895898798c4243f5db3))
* **release:** sync VERSION file to 1.9.0 ([85bc34c](https://github.com/tlconde/career-ops/commit/85bc34c0ffb494f25547c022b0038c7a3096f0c9))
* remove story-bank.md from git tracking ([#944](https://github.com/tlconde/career-ops/issues/944)) ([20ab796](https://github.com/tlconde/career-ops/commit/20ab7960e020bd7665bcfa92b54f7837a00bc09b))
* remove wellfound, lever and remotefront from portals.example.yml ([#286](https://github.com/tlconde/career-ops/issues/286)) ([a100887](https://github.com/tlconde/career-ops/commit/a1008875ab10b510af23b81211c87c267b1a62e6))
* replace grep -P with POSIX-compatible grep in batch-runner.sh ([e309567](https://github.com/tlconde/career-ops/commit/e3095678fd0d0f22ac529cf4e5c496e9cd38fd5c))
* **scaffolder:** don't pre-create user config so agent onboarding triggers ([#858](https://github.com/tlconde/career-ops/issues/858)) ([46f4eab](https://github.com/tlconde/career-ops/commit/46f4eabff375bdc72727745c3435c03ab7883cbe)), closes [#855](https://github.com/tlconde/career-ops/issues/855)
* **scan:** bootstrap providers/ on update + harden greenhouse detect() ([#696](https://github.com/tlconde/career-ops/issues/696)) ([37ccd25](https://github.com/tlconde/career-ops/commit/37ccd25dcb6fbbc2ea2d849198cc3c070d8aafcc))
* **scan:** raise Ashby provider timeout + add backoff retry ([#755](https://github.com/tlconde/career-ops/issues/755)) ([9357ed1](https://github.com/tlconde/career-ops/commit/9357ed123c9207b19fe4394b88ef48a2fb86e3ae))
* **scan:** surface websearch-handoff companies in the run summary ([#814](https://github.com/tlconde/career-ops/issues/814)) ([31251bb](https://github.com/tlconde/career-ops/commit/31251bb54ae694c2f577e6cf626e3a928309cd45)), closes [#747](https://github.com/tlconde/career-ops/issues/747)
* **scan:** validate Greenhouse URL hostname against allowlist to prevent SSRF ([#602](https://github.com/tlconde/career-ops/issues/602)) ([2398fd6](https://github.com/tlconde/career-ops/commit/2398fd6d34ade0198cce2e6539471ab0ba823c2a))
* scope npm package as @santifer/career-ops ([#857](https://github.com/tlconde/career-ops/issues/857)) ([f355ca7](https://github.com/tlconde/career-ops/commit/f355ca7eaf94d71a686df597fd612f8fd963a89c))
* **security:** close SSRF guard bypasses in liveness-browser ([#917](https://github.com/tlconde/career-ops/issues/917)) ([a52f0fc](https://github.com/tlconde/career-ops/commit/a52f0fc2c17977d1354fe18d3dbb57eafcc21f32))
* **skill:** surface latex mode in command menus ([#928](https://github.com/tlconde/career-ops/issues/928)) ([e6e27dd](https://github.com/tlconde/career-ops/commit/e6e27dd740c5d0b83a97bb1fdfc1cc92add3e6e5))
* **templates:** align CV certification rows on a 3-column grid ([#638](https://github.com/tlconde/career-ops/issues/638)) ([163ad9b](https://github.com/tlconde/career-ops/commit/163ad9b4d914aeb9d668cb755f91e9439947dbe3))
* test-all.mjs scans only git-tracked files, avoids false positives ([9fc3ba2](https://github.com/tlconde/career-ops/commit/9fc3ba23e8fcd663f83b0bac62417401c4da7bda))
* **tests:** run tracker-mutating scripts with --dry-run in script checks ([#925](https://github.com/tlconde/career-ops/issues/925)) ([f15b1f6](https://github.com/tlconde/career-ops/commit/f15b1f64d19e9dec4073b17f79167e3713757d5b))
* **tracker:** prevent dedup from deleting distinct same-company roles ([#950](https://github.com/tlconde/career-ops/issues/950)) ([3f1d788](https://github.com/tlconde/career-ops/commit/3f1d78875fbd46e98dc1d6f7dd01c7105a13a599))
* **update-system:** add tracker-links.mjs to SYSTEM_PATHS ([a3b57b1](https://github.com/tlconde/career-ops/commit/a3b57b1a4bbfceec917cb783b0b796c29dcb5b81))
* **update-system:** allow writing-samples/README.md as system-owned file ([#562](https://github.com/tlconde/career-ops/issues/562)) ([b0dd0f7](https://github.com/tlconde/career-ops/commit/b0dd0f701b0f268a2106cb0aa00c210d329ff516))
* **update-system:** apply() safety violation reverts cleanly and releases lock ([#484](https://github.com/tlconde/career-ops/issues/484)) ([df6d42c](https://github.com/tlconde/career-ops/commit/df6d42c74f469a996b7133a7a2ff95650b134014))
* **update-system:** bootstrap .agents/ for v1.6→v1.7 migration ([#654](https://github.com/tlconde/career-ops/issues/654)) ([706dd34](https://github.com/tlconde/career-ops/commit/706dd346c535fb5de05eb54170f88e63fb4f69df))
* **update-system:** bootstrap liveness-browser.mjs for v1.7→v1.8 upgrades ([#725](https://github.com/tlconde/career-ops/issues/725)) ([90e456d](https://github.com/tlconde/career-ops/commit/90e456d2b07814b6ad710ea703cebdc720067611)), closes [#704](https://github.com/tlconde/career-ops/issues/704)
* **update-system:** cross-check GitHub Releases API when VERSION file is stale ([68f2ca7](https://github.com/tlconde/career-ops/commit/68f2ca76b975e72b83f167a5206d988b98bf0657))
* **update-system:** defensive VERSION parsing for release-please marker ([#547](https://github.com/tlconde/career-ops/issues/547)) ([7e23a1a](https://github.com/tlconde/career-ops/commit/7e23a1ae7f91b0ac4adb4d9c549887d472ca3177))
* **update-system:** expand SYSTEM_PATHS to cover all language modes and current scripts ([769538e](https://github.com/tlconde/career-ops/commit/769538eeaf7399ca86a8f2858d1300e964ce03bc))
* **update-system:** include .agents/ in SYSTEM_PATHS ([#600](https://github.com/tlconde/career-ops/issues/600)) ([2169d9c](https://github.com/tlconde/career-ops/commit/2169d9c441548da394cd955cec051c2bbe086aca))
* **update-system:** rollback() removes paths absent from backup branch ([#483](https://github.com/tlconde/career-ops/issues/483)) ([9240a8e](https://github.com/tlconde/career-ops/commit/9240a8e3ca7f2f4d16ae96477cb3bf36fa397cf1))
* **update:** bootstrap tracker-links.mjs and scaffolder/ for v1.8.x to v1.9.0 upgrades ([#921](https://github.com/tlconde/career-ops/issues/921)) ([1148740](https://github.com/tlconde/career-ops/commit/11487403e06a8f5f74a7affde6c58689a6f1240c))
* **update:** distribute missing modes, locales and CLI configs via update-system ([#868](https://github.com/tlconde/career-ops/issues/868)) ([db4a513](https://github.com/tlconde/career-ops/commit/db4a513ed6dca00243e12a8cab4e2723963920b5))
* **update:** distribute missing runtime paths ([#991](https://github.com/tlconde/career-ops/issues/991)) ([af48199](https://github.com/tlconde/career-ops/commit/af481998786cc7275784fdc3702a0272da922545))
* **update:** match Release Please component-prefixed tags in version check ([#926](https://github.com/tlconde/career-ops/issues/926)) ([cf6de5a](https://github.com/tlconde/career-ops/commit/cf6de5a32ade1b6e9753e73d4332ea7a0ceb5357))
* **update:** rebuild dashboard binary after Go source changes ([#953](https://github.com/tlconde/career-ops/issues/953)) ([c5a9f75](https://github.com/tlconde/career-ops/commit/c5a9f755c5288a63cfd2443ed10035816551bf1c))
* **update:** run curl version checks concurrently in check() ([#896](https://github.com/tlconde/career-ops/issues/896)) ([b805397](https://github.com/tlconde/career-ops/commit/b8053975e2a5fa6b7a02cbd5862450e8708f0918))
* **update:** timestamp backup branches and roll back to the newest ([#813](https://github.com/tlconde/career-ops/issues/813)) ([f598231](https://github.com/tlconde/career-ops/commit/f598231f02ec26a536290ae86485af8f6915e570)), closes [#733](https://github.com/tlconde/career-ops/issues/733)
* **update:** use curl in check() so updates work inside the Claude Code sandbox ([#802](https://github.com/tlconde/career-ops/issues/802)) ([6ef6c35](https://github.com/tlconde/career-ops/commit/6ef6c355c2e8742962d0099ccd4ebdbd49601f70)), closes [#754](https://github.com/tlconde/career-ops/issues/754)
* **update:** use target updater manifest during apply ([#983](https://github.com/tlconde/career-ops/issues/983)) ([4e4eaef](https://github.com/tlconde/career-ops/commit/4e4eaef33cf9b64166591684a405b147d1b276ae))
* use candidate name from profile.yml in PDF filename ([e2754b3](https://github.com/tlconde/career-ops/commit/e2754b3edc096a57cb3a9ebc8efda87751dbec27))
* use execFileSync to prevent shell injection in test-all.mjs ([354d85f](https://github.com/tlconde/career-ops/commit/354d85fdbfe522ef329da259ebb3f724030f2c21))
* use fileURLToPath for cross platform compatible paths in tracker scripts ([#32](https://github.com/tlconde/career-ops/issues/32)) ([#58](https://github.com/tlconde/career-ops/issues/58)) ([6748504](https://github.com/tlconde/career-ops/commit/6748504af3a198246012d43e701cbe4fa01493d7))
* use hi@santifer.io in English README ([7ca2004](https://github.com/tlconde/career-ops/commit/7ca2004c7c3260fb7aeec72a1ff136e884516979))


### Performance Improvements

* compress hero banner from 5.7MB to 671KB ([28de18f](https://github.com/tlconde/career-ops/commit/28de18f7d96113fa045762ee8273ae8cca76a856))

## [1.11.0](https://github.com/santifer/career-ops/compare/career-ops-v1.10.0...career-ops-v1.11.0) (2026-06-15)


### Features

* add first-class OpenCode support alongside Claude Code ([#707](https://github.com/santifer/career-ops/issues/707)) ([2710fbe](https://github.com/santifer/career-ops/commit/2710fbe9b31cd0c6d1a8765cd5e04c255ede4ca3))
* **cover:** add optional salutation/greeting to cover letters ([#1010](https://github.com/santifer/career-ops/issues/1010)) ([99346c1](https://github.com/santifer/career-ops/commit/99346c148fbd19e4040be457f860b27fe678e8d7))
* **cover:** load _profile.md so personalization governs the letter ([#1012](https://github.com/santifer/career-ops/issues/1012)) ([dff56d3](https://github.com/santifer/career-ops/commit/dff56d3903c85251e6fdd008feb02ba464a5d0dc))
* **doctor:** warn when Playwright MCP tools are not configured ([#938](https://github.com/santifer/career-ops/issues/938)) ([0222224](https://github.com/santifer/career-ops/commit/0222224c108c210d715ef4f5cac42a2edac24809))
* **tracker:** map tracker columns by header name ([#954](https://github.com/santifer/career-ops/issues/954)) ([57b34c0](https://github.com/santifer/career-ops/commit/57b34c07e01cd106528936398507e1b4552ca295))
* **tracker:** SQLite derived index over applications.md — phase 1 ([#919](https://github.com/santifer/career-ops/issues/919)) ([5465f16](https://github.com/santifer/career-ops/commit/5465f162bb71dec8a25391265bdd498db2d6b512))


### Bug Fixes

* **cv:** align certification org column width across rows ([#931](https://github.com/santifer/career-ops/issues/931)) ([e27b051](https://github.com/santifer/career-ops/commit/e27b051eaf1d96ea56ebbeabd7535d19225922d2))
* **deps:** update npm dependencies to v1.61.0 ([#1023](https://github.com/santifer/career-ops/issues/1023)) ([5407247](https://github.com/santifer/career-ops/commit/54072470ab440b1b358a18ab6de9672cc4cb5649))
* **eval:** gate dead links before evaluation in oferta and auto-pipeline ([#937](https://github.com/santifer/career-ops/issues/937)) ([ebf9a13](https://github.com/santifer/career-ops/commit/ebf9a13762f5bbb2e0d9bdf17c7f0b96e32c4e94))
* **generate-pdf:** inline local fonts as data: URLs so they actually embed ([#952](https://github.com/santifer/career-ops/issues/952)) ([08d1e9a](https://github.com/santifer/career-ops/commit/08d1e9a504cfa8198fb1c84ee824b80de2324df8))
* **merge-tracker:** serialize concurrent tracker merges with a filesystem lock ([#941](https://github.com/santifer/career-ops/issues/941)) ([0d57994](https://github.com/santifer/career-ops/commit/0d579944d99276cf85d0d2280cc2697ee7a95140))
* **pdf:** wait for load instead of networkidle during render ([#929](https://github.com/santifer/career-ops/issues/929)) ([fd2ce04](https://github.com/santifer/career-ops/commit/fd2ce043713874f354980dca0e5778272cdb96a0))
* remove story-bank.md from git tracking ([#944](https://github.com/santifer/career-ops/issues/944)) ([67662b9](https://github.com/santifer/career-ops/commit/67662b9dad68175a06c631baac523437a93d44f2))
* **skill:** surface latex mode in command menus ([#928](https://github.com/santifer/career-ops/issues/928)) ([2803348](https://github.com/santifer/career-ops/commit/2803348129078960d752c34e75bf253cd32aec06))
* **tests:** run tracker-mutating scripts with --dry-run in script checks ([#925](https://github.com/santifer/career-ops/issues/925)) ([1acf27d](https://github.com/santifer/career-ops/commit/1acf27d2d154b8d12c246c8c5fed443dec08384b))
* **tracker:** prevent dedup from deleting distinct same-company roles ([#950](https://github.com/santifer/career-ops/issues/950)) ([98b32a4](https://github.com/santifer/career-ops/commit/98b32a445abe1bb464dbc15ebb1c450a82772564))
* **update:** distribute missing runtime paths ([#991](https://github.com/santifer/career-ops/issues/991)) ([85ae717](https://github.com/santifer/career-ops/commit/85ae717b8dd331a87ffb58f66181465f4509a17c))
* **update:** match Release Please component-prefixed tags in version check ([#926](https://github.com/santifer/career-ops/issues/926)) ([6f0e289](https://github.com/santifer/career-ops/commit/6f0e2890e91b178cdc82a403427152247516e559))
* **update:** rebuild dashboard binary after Go source changes ([#953](https://github.com/santifer/career-ops/issues/953)) ([5382d37](https://github.com/santifer/career-ops/commit/5382d37f65dde222d73ce059f804be9f4853d922))
* **update:** use target updater manifest during apply ([#983](https://github.com/santifer/career-ops/issues/983)) ([539e47b](https://github.com/santifer/career-ops/commit/539e47bdc59462c883964549a01e312d58e996e1))

## [1.10.0](https://github.com/santifer/career-ops/compare/career-ops-v1.9.0...career-ops-v1.10.0) (2026-06-11)


### Features

* **apply:** add preflight liveness and role-match gate ([#887](https://github.com/santifer/career-ops/issues/887)) ([42bb9ab](https://github.com/santifer/career-ops/commit/42bb9ab1aa73397d88a6759def9d4579c979eac3))
* **batch:** pause batch runner on Claude session limits ([#874](https://github.com/santifer/career-ops/issues/874)) ([ae6beec](https://github.com/santifer/career-ops/commit/ae6beec28b83fb184325f3fd261816684613b3ae))
* **cover:** add cover letter generation mode ([#807](https://github.com/santifer/career-ops/issues/807)) ([493f822](https://github.com/santifer/career-ops/commit/493f82268608b447fab2a4b5f60d8ee169bc2679))
* **cv:** add build-cv-latex.mjs structured JSON to LaTeX renderer ([#905](https://github.com/santifer/career-ops/issues/905)) ([b4af01f](https://github.com/santifer/career-ops/commit/b4af01f0858ecd707bcd168b3771a6d3cd76f2ba))
* **dashboard:** keep discard reason visible in pipeline preview ([#914](https://github.com/santifer/career-ops/issues/914)) ([3200dfe](https://github.com/santifer/career-ops/commit/3200dfe34805b5e5f2cfc1850da31bdad1c627fa))
* **dashboard:** sortable Location, Pay, and Last-contact columns in pipeline view ([#798](https://github.com/santifer/career-ops/issues/798)) ([265a95b](https://github.com/santifer/career-ops/commit/265a95befd4f5d0b42ecee104446129898f4ad0c))
* dockerize project for hosts blocked from native Playwright install ([#625](https://github.com/santifer/career-ops/issues/625)) ([66404a8](https://github.com/santifer/career-ops/commit/66404a81a617ad0b076df2a8607aad03996124a7))
* **doctor:** adopt doctor --json as the single onboarding state source ([#888](https://github.com/santifer/career-ops/issues/888)) ([35e2124](https://github.com/santifer/career-ops/commit/35e212429ec98442d83fe47b08636c5688f90055))
* **followup:** read cadence settings from profile.yml ([#889](https://github.com/santifer/career-ops/issues/889)) ([8050c37](https://github.com/santifer/career-ops/commit/8050c37870fe2e3fe14c1da836f00d1a7a8819fe))
* **i18n:** add full Arabic language support and modes ([#764](https://github.com/santifer/career-ops/issues/764)) ([333bb81](https://github.com/santifer/career-ops/commit/333bb81bcc4e3d7e93928ba1b6d155110ce79cd7))
* **modes:** add interactive interview onboarding subcommand ([#909](https://github.com/santifer/career-ops/issues/909)) ([46a5c59](https://github.com/santifer/career-ops/commit/46a5c5914aab6389ab51d4d393d5575a06f229e6))
* **scan:** add --rediscover-404 fallback for moved tracked postings ([#808](https://github.com/santifer/career-ops/issues/808)) ([7096dbc](https://github.com/santifer/career-ops/commit/7096dbc31067963f0a08d95185f7a2b4c5539f91))
* **scan:** add configurable salary filtering to the zero-token scanner ([#677](https://github.com/santifer/career-ops/issues/677)) ([a6ea02e](https://github.com/santifer/career-ops/commit/a6ea02ea354de05f6cb50a6c578fab3e1c5c0dd8))
* **scan:** add portals.yml schema validator ([#886](https://github.com/santifer/career-ops/issues/886)) ([3340695](https://github.com/santifer/career-ops/commit/33406955e5c619c088a0e3063b6e08d445dc1105))
* **scan:** add scan-ats-full.mjs — reverse-discover jobs from public ATS APIs ([#746](https://github.com/santifer/career-ops/issues/746)) ([7801dc7](https://github.com/santifer/career-ops/commit/7801dc7ecdc1ef1a3385fe6eb0797bb03cf6d047))
* **scan:** add scan-history TTL and recheck policy ([#895](https://github.com/santifer/career-ops/issues/895)) ([1db4cf2](https://github.com/santifer/career-ops/commit/1db4cf2072bdb235bb423b61d2d4da4773c9fa49))
* **scan:** add SolidJobs provider and job_boards support ([#853](https://github.com/santifer/career-ops/issues/853)) ([79862a9](https://github.com/santifer/career-ops/commit/79862a9e0ed0938576e91f6785c7fbc5dc2c4d7c))


### Bug Fixes

* **apply:** preserve form field contracts ([#821](https://github.com/santifer/career-ops/issues/821)) ([2b38fd0](https://github.com/santifer/career-ops/commit/2b38fd09e59e5b709069a1f504f3a8553a1cc0f7))
* **batch:** append profile context to worker prompts ([#815](https://github.com/santifer/career-ops/issues/815)) ([4989afc](https://github.com/santifer/career-ops/commit/4989afc112e9fa052b3d489cb5ba198ee0a552ee))
* **batch:** isolate workers from inherited MCP to prevent parallel deadlock ([#809](https://github.com/santifer/career-ops/issues/809)) ([c8c0dbd](https://github.com/santifer/career-ops/commit/c8c0dbd5f96874530f70a2e490f261ee5eaa3ed0))
* **batch:** stop after min-score skip instead of falling through to completed ([#873](https://github.com/santifer/career-ops/issues/873)) ([888ca31](https://github.com/santifer/career-ops/commit/888ca3139411feb5282a3a2ec53c5f8a8390f0e4))
* **dashboard:** resolve tracker-relative report links against the tracker directory ([#780](https://github.com/santifer/career-ops/issues/780)) ([858fc93](https://github.com/santifer/career-ops/commit/858fc9334f38f8767ec3d93cdac4bdb5e754aeff)), closes [#779](https://github.com/santifer/career-ops/issues/779)
* **doctor:** single source of truth for onboarding state via doctor --json ([#765](https://github.com/santifer/career-ops/issues/765)) ([eb536c4](https://github.com/santifer/career-ops/commit/eb536c49580ba17a9e63064f3893248a4c58c576))
* **flake:** declare systems so the devShell resolves on macOS ([#848](https://github.com/santifer/career-ops/issues/848)) ([e5f0903](https://github.com/santifer/career-ops/commit/e5f09038e7cd9135db535927db219813d94a71ce)), closes [#334](https://github.com/santifer/career-ops/issues/334)
* **liveness:** stop false-expiring postings behind anti-bot walls ([#783](https://github.com/santifer/career-ops/issues/783)) ([a667c33](https://github.com/santifer/career-ops/commit/a667c337acc4b68e3e937fd4ce5280bb77b3ce4a))
* **merge-tracker:** require company match on exact entry-number dedup ([#867](https://github.com/santifer/career-ops/issues/867)) ([10ad2de](https://github.com/santifer/career-ops/commit/10ad2de161f7d45ee51e7895c4a47aa556207cb3))
* **merge-tracker:** use token-union ratio in roleFuzzyMatch to stop cross-role dedup ([#793](https://github.com/santifer/career-ops/issues/793)) ([cfa7505](https://github.com/santifer/career-ops/commit/cfa750573a8dfbcc3b825311e6c910d51719e54f)), closes [#751](https://github.com/santifer/career-ops/issues/751)
* **patterns:** parse header-style and Detected-archetype formats in analyze-patterns ([#723](https://github.com/santifer/career-ops/issues/723)) ([abf603c](https://github.com/santifer/career-ops/commit/abf603c885eab6b3741b0cf41297ac2b9a960cc4))
* **pdf:** reject CV section ordering that diverges from cv.md source ([#817](https://github.com/santifer/career-ops/issues/817)) ([9f6acc2](https://github.com/santifer/career-ops/commit/9f6acc2acf5e77ab504990bb483d0e2c29c9b313))
* **pipeline:** atomic report-number reservation for parallel workers ([#803](https://github.com/santifer/career-ops/issues/803)) ([c42368c](https://github.com/santifer/career-ops/commit/c42368c189b611044a666d7d11fe81ba5a78c6ad))
* **release:** auto-sync VERSION via release-please generic extra-file ([214f5f8](https://github.com/santifer/career-ops/commit/214f5f8a7ca06f8b1225aed49709022e4c9f32e8))
* **release:** sync VERSION file to 1.9.0 ([461e3d9](https://github.com/santifer/career-ops/commit/461e3d91f6a48419c5b51fa17e6765bf8d174a3c))
* **security:** close SSRF guard bypasses in liveness-browser ([#917](https://github.com/santifer/career-ops/issues/917)) ([1f525c4](https://github.com/santifer/career-ops/commit/1f525c4e4a661c1153b526e3e210a444007e388e))
* **update:** bootstrap tracker-links.mjs and scaffolder/ for v1.8.x to v1.9.0 upgrades ([#921](https://github.com/santifer/career-ops/issues/921)) ([1d3a18b](https://github.com/santifer/career-ops/commit/1d3a18be5822fe40feb3e5629890a3eb7d752bcf))
* **update:** run curl version checks concurrently in check() ([#896](https://github.com/santifer/career-ops/issues/896)) ([8f0ed38](https://github.com/santifer/career-ops/commit/8f0ed384245f8f859da08e188d873367ffc394f6))
* **update:** use curl in check() so updates work inside the Claude Code sandbox ([#802](https://github.com/santifer/career-ops/issues/802)) ([8cac7f3](https://github.com/santifer/career-ops/commit/8cac7f33deeba69674682c5d77883b0e5b3eaba2)), closes [#754](https://github.com/santifer/career-ops/issues/754)

## [1.9.0](https://github.com/santifer/career-ops/compare/career-ops-v1.8.0...career-ops-v1.9.0) (2026-06-09)


### Features

* add npx career-ops scaffolder for one-command install ([#856](https://github.com/santifer/career-ops/issues/856)) ([ce4fa58](https://github.com/santifer/career-ops/commit/ce4fa5825c74c50506e5cdb5018d79840e2e2fe5)), closes [#855](https://github.com/santifer/career-ops/issues/855)
* add structured machine summaries to evaluations ([#444](https://github.com/santifer/career-ops/issues/444)) ([19a1820](https://github.com/santifer/career-ops/commit/19a1820f99e05db68508a2b769379384636a9e83))
* add Ukrainian language and market support ([#323](https://github.com/santifer/career-ops/issues/323)) ([06d70d3](https://github.com/santifer/career-ops/commit/06d70d30b26754228e7560e6477f94e8d5360874))
* **batch:** add --model flag to batch-runner.sh ([#504](https://github.com/santifer/career-ops/issues/504)) ([44def35](https://github.com/santifer/career-ops/commit/44def35c23c43e91d9633951d90f4ff50773c931))
* **dashboard:** /-key live search across pipeline rows ([#526](https://github.com/santifer/career-ops/issues/526)) ([433f34f](https://github.com/santifer/career-ops/commit/433f34f20aec61c68fda5dd9274a06919d0d7fc2))
* **i18n:** add Turkish (TR) language modes ([#341](https://github.com/santifer/career-ops/issues/341)) ([e87eb57](https://github.com/santifer/career-ops/commit/e87eb576df3aa394a7e28acd9f04a805ca0ca696))
* **interview-prep:** split prep by interviewer audience ([#489](https://github.com/santifer/career-ops/issues/489)) ([d86b86c](https://github.com/santifer/career-ops/commit/d86b86c93ada6cd8d74213357a1566f17dccd280))
* make PDF auto-generation configurable via auto_pdf_score_threshold ([#715](https://github.com/santifer/career-ops/issues/715)) ([fdbf4e1](https://github.com/santifer/career-ops/commit/fdbf4e13ef6143294b22cc42fb3e03294905880c))
* **scan:** add --verify flag to drop expired postings before pipeline append ([#487](https://github.com/santifer/career-ops/issues/487)) ([82f0c2e](https://github.com/santifer/career-ops/commit/82f0c2ef9ee2155cf70300c2f64e15eeaf40a69e))
* **scan:** add local-parser provider and agent skip rules ([#595](https://github.com/santifer/career-ops/issues/595)) ([b3ef0ae](https://github.com/santifer/career-ops/commit/b3ef0ae3d7ca9ebffc1d8a524408c5dfa42e3446))
* **scan:** add optional always_allow tier to location_filter ([#652](https://github.com/santifer/career-ops/issues/652)) ([d152da3](https://github.com/santifer/career-ops/commit/d152da36e7625c229d15f6f2ef92ab43d4398cc8)), closes [#650](https://github.com/santifer/career-ops/issues/650)
* **scan:** add Workable, SmartRecruiters, Recruitee ATS parsers ([#653](https://github.com/santifer/career-ops/issues/653)) ([ea7b2a6](https://github.com/santifer/career-ops/commit/ea7b2a673eab73e258f33f64fcb0844df0b36d9d)), closes [#651](https://github.com/santifer/career-ops/issues/651)


### Bug Fixes

* **batch:** wait and retry batch workers on rate limits ([#816](https://github.com/santifer/career-ops/issues/816)) ([f498ccf](https://github.com/santifer/career-ops/commit/f498ccf5e1027032de8402715e1483d780a7ad84)), closes [#505](https://github.com/santifer/career-ops/issues/505)
* **dashboard:** width-aware Markdown rendering with table wrapping in viewer ([#513](https://github.com/santifer/career-ops/issues/513)) ([dc3a247](https://github.com/santifer/career-ops/commit/dc3a247733d9fb7eb7159836bed743a587231192))
* **gemini:** auto-merge Gemini evals into the tracker instead of a manual-edit reminder ([#820](https://github.com/santifer/career-ops/issues/820)) ([6efac1a](https://github.com/santifer/career-ops/commit/6efac1a27b64e546a9a3ef31b25478cce571a365))
* make tracker report links relative to the tracker file ([#760](https://github.com/santifer/career-ops/issues/760)) ([#761](https://github.com/santifer/career-ops/issues/761)) ([c0d42cd](https://github.com/santifer/career-ops/commit/c0d42cda026d902dfc226364e018a8fd5c8d94b3))
* **pdf:** don't spell out ambiguous ¥ currency symbol ([4c415a9](https://github.com/santifer/career-ops/commit/4c415a9128c2ecaf2150e6e484324bc53a524dc6))
* **pdf:** normalize arrows, middots, and currency symbols for ATS extraction ([#731](https://github.com/santifer/career-ops/issues/731)) ([f164eba](https://github.com/santifer/career-ops/commit/f164ebadbb1430af8bdc541e1af70af52d05c81e)), closes [#730](https://github.com/santifer/career-ops/issues/730)
* register the career-ops skill in Claude Code via user_invocable key ([#801](https://github.com/santifer/career-ops/issues/801)) ([3ddb00c](https://github.com/santifer/career-ops/commit/3ddb00ce14cd7dd7af42410e4f3f3a1311ef787d)), closes [#763](https://github.com/santifer/career-ops/issues/763)
* **release:** sync VERSION file to 1.8.0 ([541917f](https://github.com/santifer/career-ops/commit/541917f627f3f328e5411a54685f5e8706761499))
* **scaffolder:** don't pre-create user config so agent onboarding triggers ([#858](https://github.com/santifer/career-ops/issues/858)) ([cd827be](https://github.com/santifer/career-ops/commit/cd827bed557b96ab2dba7a0496c73827ba51277a)), closes [#855](https://github.com/santifer/career-ops/issues/855)
* **scan:** bootstrap providers/ on update + harden greenhouse detect() ([#696](https://github.com/santifer/career-ops/issues/696)) ([4b12081](https://github.com/santifer/career-ops/commit/4b120817fc1a07d4664ff764bf2a1c51e443b524))
* **scan:** raise Ashby provider timeout + add backoff retry ([#755](https://github.com/santifer/career-ops/issues/755)) ([1aa6c63](https://github.com/santifer/career-ops/commit/1aa6c63a34b448414826d0c7a7cfa161583c256f))
* **scan:** surface websearch-handoff companies in the run summary ([#814](https://github.com/santifer/career-ops/issues/814)) ([137c7b3](https://github.com/santifer/career-ops/commit/137c7b3f3149f2aac9a2c7c1e9120c90d073d79b)), closes [#747](https://github.com/santifer/career-ops/issues/747)
* scope npm package as @santifer/career-ops ([#857](https://github.com/santifer/career-ops/issues/857)) ([87ef561](https://github.com/santifer/career-ops/commit/87ef561b63ca7221ed0476326a96c41421f01103))
* **update-system:** add tracker-links.mjs to SYSTEM_PATHS ([8287cf4](https://github.com/santifer/career-ops/commit/8287cf4eaa00ae40bb236020e9d2892c0d539f76))
* **update-system:** apply() safety violation reverts cleanly and releases lock ([#484](https://github.com/santifer/career-ops/issues/484)) ([980153c](https://github.com/santifer/career-ops/commit/980153c315ec3fbbe6f9195c77d2f865b5a2e1a0))
* **update-system:** bootstrap liveness-browser.mjs for v1.7→v1.8 upgrades ([#725](https://github.com/santifer/career-ops/issues/725)) ([1ea95f2](https://github.com/santifer/career-ops/commit/1ea95f293e742945fb4ba9befee4db8c50df6d2f)), closes [#704](https://github.com/santifer/career-ops/issues/704)
* **update-system:** rollback() removes paths absent from backup branch ([#483](https://github.com/santifer/career-ops/issues/483)) ([f94a3be](https://github.com/santifer/career-ops/commit/f94a3be25890d83ee2664175bbe1bebf1f3eb033))
* **update:** distribute missing modes, locales and CLI configs via update-system ([#868](https://github.com/santifer/career-ops/issues/868)) ([03b2c94](https://github.com/santifer/career-ops/commit/03b2c948cf5340f1c31a7711e8858fe0d30b86fd))
* **update:** timestamp backup branches and roll back to the newest ([#813](https://github.com/santifer/career-ops/issues/813)) ([1717f9c](https://github.com/santifer/career-ops/commit/1717f9c3167cee942c99ca290cdf58398e466863)), closes [#733](https://github.com/santifer/career-ops/issues/733)

## [1.8.0](https://github.com/santifer/career-ops/compare/career-ops-v1.7.1...career-ops-v1.8.0) (2026-05-15)


### Features

* **scan:** optional location_filter in portals.yml + persist location to scan-history ([#570](https://github.com/santifer/career-ops/issues/570)) ([d692647](https://github.com/santifer/career-ops/commit/d692647c253a0bf92a4f9f3b8043afe2c8161853))


### Bug Fixes

* **batch:** workers read modes/_profile.md and config/profile.yml ([#537](https://github.com/santifer/career-ops/issues/537)) ([150e223](https://github.com/santifer/career-ops/commit/150e223ba679246a378e7815da95b6b6d1c5e6ad)), closes [#534](https://github.com/santifer/career-ops/issues/534)
* **deps:** update dotenv to v17 ([#499](https://github.com/santifer/career-ops/issues/499)) ([ce1330e](https://github.com/santifer/career-ops/commit/ce1330efc45e9da462e81ccce3d5f27db9f8a623))
* **gemini-eval:** include profile.yml and _profile.md in evaluation ([#618](https://github.com/santifer/career-ops/issues/618)) ([73dc603](https://github.com/santifer/career-ops/commit/73dc6038d2e723997426d73d3a0c5040c48dd033)), closes [#617](https://github.com/santifer/career-ops/issues/617)
* **gemini-eval:** redact API key from error logs, harden summary parsing ([#582](https://github.com/santifer/career-ops/issues/582)) ([fdca4de](https://github.com/santifer/career-ops/commit/fdca4ded87e1dbde0571fe740da061da491f46c7))
* **gemini-eval:** switch default model to non-deprecated endpoint, surface 429 guidance ([#615](https://github.com/santifer/career-ops/issues/615)) ([dd3e036](https://github.com/santifer/career-ops/commit/dd3e0366d26719af7be234786a16512f46ac9e85)), closes [#614](https://github.com/santifer/career-ops/issues/614)
* **manifest:** align plugin.json skills field with Claude Code plugin schema ([#612](https://github.com/santifer/career-ops/issues/612)) ([a77d3f6](https://github.com/santifer/career-ops/commit/a77d3f6aa3f5c278665c95c5a12048e4df66d337))
* **merge-tracker:** preserve short specialty acronyms, require non-baseline overlap ([#634](https://github.com/santifer/career-ops/issues/634)) ([5ed3b3d](https://github.com/santifer/career-ops/commit/5ed3b3d7ea693547153ef734ab5f6016414c3301)), closes [#633](https://github.com/santifer/career-ops/issues/633)
* **modes:** make /career-ops deep respect user language, not JD language ([#568](https://github.com/santifer/career-ops/issues/568)) ([e5f0508](https://github.com/santifer/career-ops/commit/e5f0508b94299a0e6b46918ecca2f483de0a58c6))
* **portals:** update Weights & Biases entry to CoreWeave acquisition ([#493](https://github.com/santifer/career-ops/issues/493)) ([1411cdc](https://github.com/santifer/career-ops/commit/1411cdc461de05a6772c854188053bcaeeb4ee32))
* **release:** sync VERSION file to 1.7.1 ([2ebfcab](https://github.com/santifer/career-ops/commit/2ebfcabdb4cf7973e279e56f8eae001a8dadc5ed))
* **scan:** validate Greenhouse URL hostname against allowlist to prevent SSRF ([#602](https://github.com/santifer/career-ops/issues/602)) ([988f7bb](https://github.com/santifer/career-ops/commit/988f7bb2a642f91d6cce1e2fc94f08658b72e099))
* **templates:** align CV certification rows on a 3-column grid ([#638](https://github.com/santifer/career-ops/issues/638)) ([082cd11](https://github.com/santifer/career-ops/commit/082cd11c32b917fe3aeef709ff4f386371af3e64))
* **update-system:** allow writing-samples/README.md as system-owned file ([#562](https://github.com/santifer/career-ops/issues/562)) ([207fd07](https://github.com/santifer/career-ops/commit/207fd076da3b2a30f0384fdb19312078ebdcf71f))
* **update-system:** bootstrap .agents/ for v1.6→v1.7 migration ([#654](https://github.com/santifer/career-ops/issues/654)) ([4714504](https://github.com/santifer/career-ops/commit/47145048716d3716a2f1cb0b46377a88e5df73c0))
* **update-system:** defensive VERSION parsing for release-please marker ([#547](https://github.com/santifer/career-ops/issues/547)) ([bf84886](https://github.com/santifer/career-ops/commit/bf848860cb2c7976f6e77e1b5d7b60ed5e9d0d14))

## [1.7.1](https://github.com/santifer/career-ops/compare/career-ops-v1.7.0...career-ops-v1.7.1) (2026-05-12)


### Bug Fixes

* **release:** sync VERSION file to 1.7.0 ([8e554cc](https://github.com/santifer/career-ops/commit/8e554cc4437c3a58e813378abb9b35e2e08a007e))
* **update-system:** include .agents/ in SYSTEM_PATHS ([#600](https://github.com/santifer/career-ops/issues/600)) ([3a71469](https://github.com/santifer/career-ops/commit/3a714695c63ca01a6581b4307885be2055319784))

## [1.7.0](https://github.com/santifer/career-ops/compare/career-ops-v1.6.0...career-ops-v1.7.0) (2026-05-06)


### Features

* adapt contacto mode by contact type (recruiter/HM/peer/interviewer) ([9fd5a90](https://github.com/santifer/career-ops/commit/9fd5a90896f20020f48455cd079b64fed491b89f))
* add --min-score flag to batch runner ([#249](https://github.com/santifer/career-ops/issues/249)) ([cb0c7f7](https://github.com/santifer/career-ops/commit/cb0c7f7d7d3b9f3f1c3dc75ccac0a08d2737c01e))
* add {{PHONE}} placeholder to CV template ([#287](https://github.com/santifer/career-ops/issues/287)) ([e71595f](https://github.com/santifer/career-ops/commit/e71595f8ba134971ecf1cc3c3420d9caf21eed43))
* add Block G — posting legitimacy assessment ([3a636ac](https://github.com/santifer/career-ops/commit/3a636ac586659bb798ef46a0a9798478a1e28b0a))
* add Claude Code plugin manifests (path-stable) ([62b767d](https://github.com/santifer/career-ops/commit/62b767dcc56e4c875ed70bf4fe799c254ecf8eea))
* add follow-up cadence tracker mode ([4308c37](https://github.com/santifer/career-ops/commit/4308c375033c6df430308235f4324658a8353b81))
* add Gemini CLI native integration and evaluator script  ([#349](https://github.com/santifer/career-ops/issues/349)) ([0853486](https://github.com/santifer/career-ops/commit/0853486d2c01a35adafea2cc6b6d8c429b843588))
* add Gemini CLI native integration and evaluator script (closes [#344](https://github.com/santifer/career-ops/issues/344)) ([0853486](https://github.com/santifer/career-ops/commit/0853486d2c01a35adafea2cc6b6d8c429b843588))
* add GitHub Actions CI + auto-labeler + welcome bot + /run skill ([2ddf22a](https://github.com/santifer/career-ops/commit/2ddf22a6a2731b38bcaed5786c4855c4ab9fe722))
* add LaTeX/Overleaf CV export mode with pdflatex compilation ([#362](https://github.com/santifer/career-ops/issues/362)) ([b824953](https://github.com/santifer/career-ops/commit/b824953d0e3b7f8c6105dfcce7e17257c95ce6cd))
* add LaTeX/Overleaf CV export mode with pdflatex compilation (closes [#47](https://github.com/santifer/career-ops/issues/47)) ([b824953](https://github.com/santifer/career-ops/commit/b824953d0e3b7f8c6105dfcce7e17257c95ce6cd))
* add Nix flake devshell with Playwright support ([c579fcd](https://github.com/santifer/career-ops/commit/c579fcddebf793f00cfad8534fd74085c09017fb))
* add OpenCode slash commands for career-ops ([#67](https://github.com/santifer/career-ops/issues/67)) ([93caaed](https://github.com/santifer/career-ops/commit/93caaed49cbc9f3214f9beb66fb2281c3f2370e6))
* add scan.mjs — zero-token portal scanner ([8c19b2b](https://github.com/santifer/career-ops/commit/8c19b2b59f7087689e004f3d48e912f291911373))
* add writing-samples folder for AI-detection-evading voice calibration ([9ae201d](https://github.com/santifer/career-ops/commit/9ae201d0682a17e7006ed7902b42db8234212e97))
* **cv:** add cv.output_format to route between html and latex generation ([b82bb5f](https://github.com/santifer/career-ops/commit/b82bb5fb7c86ab3074a54eaf0f3186f81d41f417))
* **dashboard:** add Catppuccin Latte light theme with auto-detection ([ff686c8](https://github.com/santifer/career-ops/commit/ff686c8af97a7bf93565fe8eeac677f998cc9ece))
* **dashboard:** add manual refresh shortcut ([#246](https://github.com/santifer/career-ops/issues/246)) ([4b5093a](https://github.com/santifer/career-ops/commit/4b5093a8ef1733c449ec0821f722f996625fcb84))
* **dashboard:** add progress analytics screen ([623c837](https://github.com/santifer/career-ops/commit/623c837bf3155fd5b7413554240071d40585dd7e))
* **dashboard:** add rejected and discarded pipeline tabs ([7d05967](https://github.com/santifer/career-ops/commit/7d05967389fb6185f0d6e566a4ba583ee3824e1e))
* **dashboard:** add vim motions to pipeline screen ([#262](https://github.com/santifer/career-ops/issues/262)) ([d149e54](https://github.com/santifer/career-ops/commit/d149e541402db0c88161a71c73899cd1836a1b2d))
* **dashboard:** aligned tables and markdown syntax rendering in viewer ([dbd1d3f](https://github.com/santifer/career-ops/commit/dbd1d3f7177358d0384d6e661d1b0dfc1f60bd4e))
* **dashboard:** show tracker IDs in pipeline list ([8d289c6](https://github.com/santifer/career-ops/commit/8d289c64e31f81cf447f75105b500d1feca21058))
* expand portals.example.yml with 8 dev-tools companies + 23 search queries ([#140](https://github.com/santifer/career-ops/issues/140)) ([b7f555d](https://github.com/santifer/career-ops/commit/b7f555d7b9a7b23c875fa0d35584df534961dabe))
* **i18n:** add Japanese README + language modes for Japan market ([20a2c81](https://github.com/santifer/career-ops/commit/20a2c817486968ca42a534aa86838c797d599c10))
* **latex:** add tectonic engine auto-detect with pdflatex fallback ([4b71b2c](https://github.com/santifer/career-ops/commit/4b71b2cbf4fd49d3882cdd8767e31727337fab34))
* multi-CLI support via open agent skill standard ([#572](https://github.com/santifer/career-ops/issues/572)) ([7605a5e](https://github.com/santifer/career-ops/commit/7605a5ed68d0fd559374afec1cd8798c487e3ead))
* **portals:** add Canada/Vancouver and automation companies to example template ([590ba6e](https://github.com/santifer/career-ops/commit/590ba6e1b4b9d2d9d03893b7f5fdae920d4f9a0b))


### Bug Fixes

* 10 bug fixes — resource leaks, command injection, Unicode, navigation ([cb01a2c](https://github.com/santifer/career-ops/commit/cb01a2c2e3b7fc334b1c4594749ea40b0da8fc62))
* add data/ fallback to UpdateApplicationStatus ([#55](https://github.com/santifer/career-ops/issues/55)) ([3512b8e](https://github.com/santifer/career-ops/commit/3512b8ef4eb8ca967bc967664f8798af42b58a52))
* add stopword filtering and overlap ratio to roleMatch ([#248](https://github.com/santifer/career-ops/issues/248)) ([4da772d](https://github.com/santifer/career-ops/commit/4da772d3a4996bc9ecbe2d384d1e9d2ed75b9819))
* align portals.example.yml indentation for new companies ([26a6751](https://github.com/santifer/career-ops/commit/26a675173e64dac09fd1524ff9a7c7061520e057))
* **ci:** correct first-interaction@v3 input names ([c5196a8](https://github.com/santifer/career-ops/commit/c5196a8dd8ff05da51c72ea151f67e481f12c329))
* **ci:** gracefully handle missing dependency graph in dependency-review ([#343](https://github.com/santifer/career-ops/issues/343)) ([7c5fecb](https://github.com/santifer/career-ops/commit/7c5fecb00d60521f77b33724eb345a28257d8832))
* **ci:** gracefully handle missing dependency graph in dependency-review workflow ([#352](https://github.com/santifer/career-ops/issues/352)) ([7c5fecb](https://github.com/santifer/career-ops/commit/7c5fecb00d60521f77b33724eb345a28257d8832))
* **ci:** use pull_request_target for labeler on fork PRs ([#260](https://github.com/santifer/career-ops/issues/260)) ([2ecf572](https://github.com/santifer/career-ops/commit/2ecf57206c2eb6e35e2a843d6b8365f7a04c53d6))
* correct _shared.md → _profile.md reference in CUSTOMIZATION.md (closes [#137](https://github.com/santifer/career-ops/issues/137)) ([a91e264](https://github.com/santifer/career-ops/commit/a91e264b6ea047a76d8c033aa564fe01b8f9c1d9))
* correct dashboard launch path in docs ([#80](https://github.com/santifer/career-ops/issues/80)) ([2b969ee](https://github.com/santifer/career-ops/commit/2b969eea5f6bbc8f29b9e42bedb59312379e9f02))
* **dashboard:** show dates in pipeline list ([#298](https://github.com/santifer/career-ops/issues/298)) ([e5e2a6c](https://github.com/santifer/career-ops/commit/e5e2a6cffe9a5b9f3cec862df25410d02ecc9aa4))
* ensure data/ and output/ dirs exist before writing in scripts ([#261](https://github.com/santifer/career-ops/issues/261)) ([4b834f6](https://github.com/santifer/career-ops/commit/4b834f6f7f8f1b647a6bf76e43b017dcbe9cd52f))
* filter expired WebSearch links before they reach the pipeline ([#57](https://github.com/santifer/career-ops/issues/57)) ([ce1c5a3](https://github.com/santifer/career-ops/commit/ce1c5a3c7eea6ebce2c90aebba59d6e26b790d3f))
* improve default PDF readability ([#85](https://github.com/santifer/career-ops/issues/85)) ([10034ec](https://github.com/santifer/career-ops/commit/10034ec3304c1c79ff9c9678c7826ab77c0bcbf7))
* liveness checks ignore nav/footer Apply text, expired signals win ([3a3cb95](https://github.com/santifer/career-ops/commit/3a3cb95bdf09235509df72e30b3077623f571ea1))
* **liveness:** detect closed postings with applications-closed banner variants ([7f8217e](https://github.com/santifer/career-ops/commit/7f8217e057b327980a797a682c4f01d3318edbbe))
* **merge-tracker:** filter seniority and location stopwords + require overlap ratio in roleFuzzyMatch ([7821113](https://github.com/santifer/career-ops/commit/7821113261eeb32f99639ff076651ab2e7757209))
* **pt:** restore diacritical marks in PT-BR modes ([#358](https://github.com/santifer/career-ops/issues/358)) ([3a4c596](https://github.com/santifer/career-ops/commit/3a4c596cb0a522f562ba38b35c210facaf38a503))
* **pt:** restore diacritical marks in PT-BR modes ([#359](https://github.com/santifer/career-ops/issues/359)) ([3a4c596](https://github.com/santifer/career-ops/commit/3a4c596cb0a522f562ba38b35c210facaf38a503))
* **release:** sync VERSION and package.json via release-please-config ([6a3dc22](https://github.com/santifer/career-ops/commit/6a3dc224337a1942bf2ebf18b9b275d94fc06e7a))
* remove wellfound, lever and remotefront from portals.example.yml ([#286](https://github.com/santifer/career-ops/issues/286)) ([ecd013c](https://github.com/santifer/career-ops/commit/ecd013cc6f59e3a1a8ef77d34e7abc15e8075ed3))
* replace grep -P with POSIX-compatible grep in batch-runner.sh ([637b39e](https://github.com/santifer/career-ops/commit/637b39e383d1174c8287f42e9534e9e3cdfabb19))
* test-all.mjs scans only git-tracked files, avoids false positives ([47c9f98](https://github.com/santifer/career-ops/commit/47c9f984d8ddc70974f15c99b081667b73f1bb9a))
* **update-system:** cross-check GitHub Releases API when VERSION file is stale ([b0ee6eb](https://github.com/santifer/career-ops/commit/b0ee6ebfcec7920ea7590ada61f3c39324d22ebc))
* **update-system:** expand SYSTEM_PATHS to cover all language modes and current scripts ([34fe3fb](https://github.com/santifer/career-ops/commit/34fe3fbd5782f7f57faf8ef4a245fbee6275a040))
* use candidate name from profile.yml in PDF filename ([7bcbc08](https://github.com/santifer/career-ops/commit/7bcbc08ca6184362398690234e49df0ac157567f))
* use execFileSync to prevent shell injection in test-all.mjs ([c99d5a6](https://github.com/santifer/career-ops/commit/c99d5a6526f923b56c3790b79b0349f402fa00e2))
* use fileURLToPath for cross platform compatible paths in tracker scripts ([#32](https://github.com/santifer/career-ops/issues/32)) ([#58](https://github.com/santifer/career-ops/issues/58)) ([ab77510](https://github.com/santifer/career-ops/commit/ab775102f4586ae4663a593b519927531be27122))
* use hi@santifer.io in English README ([5518d3d](https://github.com/santifer/career-ops/commit/5518d3dd07716137b97bb4d8c7b5264b94e2b9e9))


### Performance Improvements

* compress hero banner from 5.7MB to 671KB ([dac4259](https://github.com/santifer/career-ops/commit/dac425913620fe0a66916dda7ba8d8fc4c427d51))

## [1.6.0](https://github.com/santifer/career-ops/compare/v1.5.0...v1.6.0) (2026-04-26)


### Features

* add Gemini CLI native integration and evaluator script  ([#349](https://github.com/santifer/career-ops/issues/349)) ([0853486](https://github.com/santifer/career-ops/commit/0853486d2c01a35adafea2cc6b6d8c429b843588))
* add Gemini CLI native integration and evaluator script (closes [#344](https://github.com/santifer/career-ops/issues/344)) ([0853486](https://github.com/santifer/career-ops/commit/0853486d2c01a35adafea2cc6b6d8c429b843588))
* add LaTeX/Overleaf CV export mode with pdflatex compilation ([#362](https://github.com/santifer/career-ops/issues/362)) ([b824953](https://github.com/santifer/career-ops/commit/b824953d0e3b7f8c6105dfcce7e17257c95ce6cd))
* add LaTeX/Overleaf CV export mode with pdflatex compilation (closes [#47](https://github.com/santifer/career-ops/issues/47)) ([b824953](https://github.com/santifer/career-ops/commit/b824953d0e3b7f8c6105dfcce7e17257c95ce6cd))
* **cv:** add cv.output_format to route between html and latex generation ([b82bb5f](https://github.com/santifer/career-ops/commit/b82bb5fb7c86ab3074a54eaf0f3186f81d41f417))
* **dashboard:** add rejected and discarded pipeline tabs ([7d05967](https://github.com/santifer/career-ops/commit/7d05967389fb6185f0d6e566a4ba583ee3824e1e))
* **dashboard:** show tracker IDs in pipeline list ([8d289c6](https://github.com/santifer/career-ops/commit/8d289c64e31f81cf447f75105b500d1feca21058))
* **latex:** add tectonic engine auto-detect with pdflatex fallback ([4b71b2c](https://github.com/santifer/career-ops/commit/4b71b2cbf4fd49d3882cdd8767e31727337fab34))
* **portals:** add Canada/Vancouver and automation companies to example template ([590ba6e](https://github.com/santifer/career-ops/commit/590ba6e1b4b9d2d9d03893b7f5fdae920d4f9a0b))


### Bug Fixes

* **ci:** correct first-interaction@v3 input names ([c5196a8](https://github.com/santifer/career-ops/commit/c5196a8dd8ff05da51c72ea151f67e481f12c329))
* **ci:** gracefully handle missing dependency graph in dependency-review ([#343](https://github.com/santifer/career-ops/issues/343)) ([7c5fecb](https://github.com/santifer/career-ops/commit/7c5fecb00d60521f77b33724eb345a28257d8832))
* **ci:** gracefully handle missing dependency graph in dependency-review workflow ([#352](https://github.com/santifer/career-ops/issues/352)) ([7c5fecb](https://github.com/santifer/career-ops/commit/7c5fecb00d60521f77b33724eb345a28257d8832))
* **liveness:** detect closed postings with applications-closed banner variants ([7f8217e](https://github.com/santifer/career-ops/commit/7f8217e057b327980a797a682c4f01d3318edbbe))
* **merge-tracker:** filter seniority and location stopwords + require overlap ratio in roleFuzzyMatch ([7821113](https://github.com/santifer/career-ops/commit/7821113261eeb32f99639ff076651ab2e7757209))
* **pt:** restore diacritical marks in PT-BR modes ([#358](https://github.com/santifer/career-ops/issues/358)) ([3a4c596](https://github.com/santifer/career-ops/commit/3a4c596cb0a522f562ba38b35c210facaf38a503))
* **pt:** restore diacritical marks in PT-BR modes ([#359](https://github.com/santifer/career-ops/issues/359)) ([3a4c596](https://github.com/santifer/career-ops/commit/3a4c596cb0a522f562ba38b35c210facaf38a503))
* **update-system:** cross-check GitHub Releases API when VERSION file is stale ([b0ee6eb](https://github.com/santifer/career-ops/commit/b0ee6ebfcec7920ea7590ada61f3c39324d22ebc))
* **update-system:** expand SYSTEM_PATHS to cover all language modes and current scripts ([34fe3fb](https://github.com/santifer/career-ops/commit/34fe3fbd5782f7f57faf8ef4a245fbee6275a040))

## [1.5.0](https://github.com/santifer/career-ops/compare/v1.4.0...v1.5.0) (2026-04-14)


### Features

* add --min-score flag to batch runner ([#249](https://github.com/santifer/career-ops/issues/249)) ([cb0c7f7](https://github.com/santifer/career-ops/commit/cb0c7f7d7d3b9f3f1c3dc75ccac0a08d2737c01e))
* add {{PHONE}} placeholder to CV template ([#287](https://github.com/santifer/career-ops/issues/287)) ([e71595f](https://github.com/santifer/career-ops/commit/e71595f8ba134971ecf1cc3c3420d9caf21eed43))
* **dashboard:** add manual refresh shortcut ([#246](https://github.com/santifer/career-ops/issues/246)) ([4b5093a](https://github.com/santifer/career-ops/commit/4b5093a8ef1733c449ec0821f722f996625fcb84))


### Bug Fixes

* add stopword filtering and overlap ratio to roleMatch ([#248](https://github.com/santifer/career-ops/issues/248)) ([4da772d](https://github.com/santifer/career-ops/commit/4da772d3a4996bc9ecbe2d384d1e9d2ed75b9819))
* **dashboard:** show dates in pipeline list ([#298](https://github.com/santifer/career-ops/issues/298)) ([e5e2a6c](https://github.com/santifer/career-ops/commit/e5e2a6cffe9a5b9f3cec862df25410d02ecc9aa4))
* ensure data/ and output/ dirs exist before writing in scripts ([#261](https://github.com/santifer/career-ops/issues/261)) ([4b834f6](https://github.com/santifer/career-ops/commit/4b834f6f7f8f1b647a6bf76e43b017dcbe9cd52f))
* remove wellfound, lever and remotefront from portals.example.yml ([#286](https://github.com/santifer/career-ops/issues/286)) ([ecd013c](https://github.com/santifer/career-ops/commit/ecd013cc6f59e3a1a8ef77d34e7abc15e8075ed3))

## [1.4.0](https://github.com/santifer/career-ops/compare/v1.3.0...v1.4.0) (2026-04-13)


### Features

* add GitHub Actions CI + auto-labeler + welcome bot + /run skill ([2ddf22a](https://github.com/santifer/career-ops/commit/2ddf22a6a2731b38bcaed5786c4855c4ab9fe722))
* **dashboard:** add Catppuccin Latte light theme with auto-detection ([ff686c8](https://github.com/santifer/career-ops/commit/ff686c8af97a7bf93565fe8eeac677f998cc9ece))
* **dashboard:** add progress analytics screen ([623c837](https://github.com/santifer/career-ops/commit/623c837bf3155fd5b7413554240071d40585dd7e))
* **dashboard:** add vim motions to pipeline screen ([#262](https://github.com/santifer/career-ops/issues/262)) ([d149e54](https://github.com/santifer/career-ops/commit/d149e541402db0c88161a71c73899cd1836a1b2d))
* **dashboard:** aligned tables and markdown syntax rendering in viewer ([dbd1d3f](https://github.com/santifer/career-ops/commit/dbd1d3f7177358d0384d6e661d1b0dfc1f60bd4e))


### Bug Fixes

* **ci:** use pull_request_target for labeler on fork PRs ([#260](https://github.com/santifer/career-ops/issues/260)) ([2ecf572](https://github.com/santifer/career-ops/commit/2ecf57206c2eb6e35e2a843d6b8365f7a04c53d6))
* correct _shared.md → _profile.md reference in CUSTOMIZATION.md (closes [#137](https://github.com/santifer/career-ops/issues/137)) ([a91e264](https://github.com/santifer/career-ops/commit/a91e264b6ea047a76d8c033aa564fe01b8f9c1d9))
* replace grep -P with POSIX-compatible grep in batch-runner.sh ([637b39e](https://github.com/santifer/career-ops/commit/637b39e383d1174c8287f42e9534e9e3cdfabb19))
* test-all.mjs scans only git-tracked files, avoids false positives ([47c9f98](https://github.com/santifer/career-ops/commit/47c9f984d8ddc70974f15c99b081667b73f1bb9a))
* use execFileSync to prevent shell injection in test-all.mjs ([c99d5a6](https://github.com/santifer/career-ops/commit/c99d5a6526f923b56c3790b79b0349f402fa00e2))
