# Changelog

## [5.0.0](https://github.com/katawful/neorg/compare/v4.4.1...v5.0.0) (2023-05-17)


### ⚠ BREAKING CHANGES

* move all `gt*` keybinds to `<LocalLeader>t*`
* remove `core.news`
* move all `core.norg.*` modules into `core.*`
* **Makefile:** remove `install_pre_commit` target
* move `core.norg.dirman.summary` -> `core.summary`
* **summary:** refactor of the `core.norg.dirman.summary` module
* **docgen:** wipe whole wiki on every reparse
* **core.norg.qol.toc:** rewrite the table of contents implementation
* NUKE GTD
* **dirman:** make the behaviours of `default_workspace` and `open_last_workspace` more logical
* **dirman:** do not alter the user's cwd, ever
* **dirman:** make the behaviours of `default_workspace` and `open_last_workspace` more logical
* **dirman:** do not alter the user's cwd, ever

### Features

* add `core.clipboard.code-blocks` module ([523bb8a](https://github.com/katawful/neorg/commit/523bb8a45a9b81de1f76f2b0cb616cee9ad7c762))
* add `core.clipboard.code-blocks` module ([0bc9713](https://github.com/katawful/neorg/commit/0bc9713b9d50eeb17d3969d20cee0e4d2617d3c4))
* add `core.clipboard` module ([f5cacee](https://github.com/katawful/neorg/commit/f5caceeab5829df51fc2c560eeb5b7d1db707310))
* add `core.clipboard` module ([e6bbfa8](https://github.com/katawful/neorg/commit/e6bbfa874b7fa33eb796a6f726e2c9e713827a69))
* add `core.fs` module ([8931228](https://github.com/katawful/neorg/commit/89312281ca088943398b342e8584e21e8cb63adf))
* add `core.itero` module ([204288d](https://github.com/katawful/neorg/commit/204288d23c63e4face45ddb5346e2b5b30e6d8a8))
* add `core.pivot` for toggling list types ([cbf383f](https://github.com/katawful/neorg/commit/cbf383ff4eca0e23a24d4244af20bed415ed400c))
* add `core.tempus` module for date management ([b73ec2f](https://github.com/katawful/neorg/commit/b73ec2f5e1b11864ca0628a842a53a617d5851ce))
* add `directory_map` function ([18ea526](https://github.com/katawful/neorg/commit/18ea5264510c9485730c2b2c8cec1224503f207f))
* add `dirman.summary` module ([#750](https://github.com/katawful/neorg/issues/750)) ([93c40f2](https://github.com/katawful/neorg/commit/93c40f2e38a0770e9ce95787c8363320344a87c3))
* add `Home.md` generation capability ([6bdf557](https://github.com/katawful/neorg/commit/6bdf557ece33850f9733dddc343369d743a51564))
* add basic cheatsheet (viewable via `:h neorg-cheatsheet`) ([d3e37a6](https://github.com/katawful/neorg/commit/d3e37a681743181a34dcfa7adb6ec61fb5aeb63c))
* add left-right cursor movement ([ea588bb](https://github.com/katawful/neorg/commit/ea588bbc2cabe37f90652a8cb49bf8b286498d2a))
* add skeleton for the calendar UI element ([3c99106](https://github.com/katawful/neorg/commit/3c99106d64792533a3cf10ac6ef20a089e94c1ff))
* add support for upgrading directories ([835c9af](https://github.com/katawful/neorg/commit/835c9afa1d91b75c8dc5c0a1b0b3231dde3a2556))
* **calendar:** add `?` help page for custom input ([211b0ba](https://github.com/katawful/neorg/commit/211b0ba61b5cf8f4520b5e03f5235f6de87e4417))
* **calendar:** add `$` and `0`/`_` navigation keybinds ([0061928](https://github.com/katawful/neorg/commit/006192808d436c27f8ceca0fffcc4a238ec402a7))
* **calendar:** add `m`/`M`, `L`/`H` and `y`/`Y` keybinds for the monthly view ([9bf562d](https://github.com/katawful/neorg/commit/9bf562d4633abac71b749ad7380cfe010a4c3bd7))
* **calendar:** add `t` command for "today" ([e53a509](https://github.com/katawful/neorg/commit/e53a5099b5725162c8f0a626823cac4819a9427d))
* **calendar:** add basic help popup when `?` is invoked ([779d089](https://github.com/katawful/neorg/commit/779d089e17139acfdd2a4988c34eea892f29a475))
* **calendar:** allow many simultaneous calendars ([f816fe7](https://github.com/katawful/neorg/commit/f816fe77ef2abecff9e98d8d35ff48a453317cf0))
* **calendar:** generalize functions even further, allow for offsets ([d857c34](https://github.com/katawful/neorg/commit/d857c34fe7a4645501551f2b66dd7915b9575b4f))
* **calendar:** implement basic `i` functionality ([6713f40](https://github.com/katawful/neorg/commit/6713f40d5d1f9e7a0e8b80ffdc82d4fff79c16c0))
* **calendar:** render as many months as is possible on screen ([fa23767](https://github.com/katawful/neorg/commit/fa237674cf75bf2bbc62a438b1606b65cc277ebd))
* **ci:** add `version_in_code.yml` workflow ([5746245](https://github.com/katawful/neorg/commit/5746245756bac83fcf02338c93bc87f6089e2bf3))
* cleanup, add document comments to all modules, add more error checks ([81284c1](https://github.com/katawful/neorg/commit/81284c1e2f6e441f6532678b76ff5378396dda2c))
* **config.lua:** add `norg_version`, bump `version` to `3.0.0` ([8d76723](https://github.com/katawful/neorg/commit/8d767232a571513a3ab8c5c14ddc6f26d09aa98a))
* convert inline comments ([2460c3c](https://github.com/katawful/neorg/commit/2460c3cb4c2989b3ff81bdd670bd8c78c72b4557))
* convert link marker targets ([5bf9683](https://github.com/katawful/neorg/commit/5bf96838832ba128834cfe5b2ff9027e14249b51))
* convert markers to headings, convert insertions to infirm tags ([8ed4c0b](https://github.com/katawful/neorg/commit/8ed4c0bfd7bd00660578498ae89c30c5b618c44c))
* convert variables, spoilers ([fd62d40](https://github.com/katawful/neorg/commit/fd62d401c4997e03a78cfbe1736bc8556d072241))
* **core.clipboard:** finalize clipboard module ([6206f8c](https://github.com/katawful/neorg/commit/6206f8c57451c873532cd5af12c4842a3cb2cf60))
* **core.clipboard:** finalize clipboard module ([4de9659](https://github.com/katawful/neorg/commit/4de9659ff6e9f41d71c5c219757c453c478ebfe4))
* **core.clipboard:** refactor and stabilize module ([840610f](https://github.com/katawful/neorg/commit/840610f9d8f95be40cc880362745bc8a56dddcea))
* **core.clipboard:** refactor and stabilize module ([89d6caf](https://github.com/katawful/neorg/commit/89d6caf9003f58ca3190f7642e86f694b7cb212b))
* **core.export:** add `NeorgExportComplete` user autocommand ([8b10e61](https://github.com/katawful/neorg/commit/8b10e61d2f2c5e626849f9a6f8cb4399c28a1a47))
* **core.integrations.treesitter:** Return all same attributes of a tag ([bedf13d](https://github.com/katawful/neorg/commit/bedf13dbcef63099a52dd4f160d90c46fc1de440))
* **core.norg.news:** add `:Neorg news dismiss` command ([579945d](https://github.com/katawful/neorg/commit/579945d5a228c46dba79f326e74f1b0301aefc35))
* **core.norg.qol.toc:** add multiple buffer handling logic ([467e311](https://github.com/katawful/neorg/commit/467e3113c32b8b9f1950a9425aa7b74c13cd88b8))
* **core.norg.qol.toc:** implement `qflist` generation option ([77c5149](https://github.com/katawful/neorg/commit/77c514970a9d4648b05b2334a060263666f588e2))
* **core.ui.calendar:** add day of the month rendering ([8bc3364](https://github.com/katawful/neorg/commit/8bc3364f306d5df528193a8ca68fa8b4a45701ef))
* **core.ui.calendar:** add static calendar ui ([adbb415](https://github.com/katawful/neorg/commit/adbb4151677bf22c809f9b6dfd35de5e07da6c7a))
* **core.ui.calendar:** highlight the current day differently ([eada386](https://github.com/katawful/neorg/commit/eada386cc79c122b648580de50b1f825b74a9627))
* **core.ui.calendar:** implement more of the barebones UI ([364f44a](https://github.com/katawful/neorg/commit/364f44a7d1179d5aa98d1f4ff6b4b6b1b6078bd3))
* **core.ui.calendar:** make the calendar display full month names ([c6cc059](https://github.com/katawful/neorg/commit/c6cc059992c812712c9a2bb4075b2d9b31f84f5c))
* **core.ui:** let `create_split` take in a `height` variable ([7dbbe9d](https://github.com/katawful/neorg/commit/7dbbe9d236596d8990827e717ea892cd98e79b23))
* correctly handle year boundaries ([58b55e1](https://github.com/katawful/neorg/commit/58b55e16366ecd431bece7ba4d42d512b21b972e))
* **dirman:** add new `use_popup` option for `dirman` ([#743](https://github.com/katawful/neorg/issues/743)) ([6350254](https://github.com/katawful/neorg/commit/63502544afde1c15d79ce097ad1928314cb8c7cd))
* **docgen:** add `module` page generator ([17496a8](https://github.com/katawful/neorg/commit/17496a8e975f1bd9d896d7cc78a6e61d1a131245))
* **docgen:** add basic rendering skeleton logic ([215719e](https://github.com/katawful/neorg/commit/215719ece560400592c2fef2ed75ab57430baf9b))
* **docgen:** add comment integrity checking logic ([799886f](https://github.com/katawful/neorg/commit/799886f7ba5a072a453d5a90708686109ce4fa21))
* **docgen:** allow strings as table keys ([4adf04e](https://github.com/katawful/neorg/commit/4adf04e05d98b6bcb6a3aac4cab60d64fd0d86f9))
* **docgen:** auto-open &lt;details&gt; tags that contain tables or lists ([1f2e0dc](https://github.com/katawful/neorg/commit/1f2e0dc23f6944bad660553ad4550847cf68e096))
* **docgen:** differentiate between lists and tables ([c0062e5](https://github.com/katawful/neorg/commit/c0062e5a75226f063b59eb5ee8250cb4da6ea202))
* **docgen:** differentiate empty and nonempty tables/lists ([0ab1a8d](https://github.com/katawful/neorg/commit/0ab1a8d469667d6b763e299c390a3e9bc7ea1a13))
* **docgen:** implement `Required By` field ([7033c4b](https://github.com/katawful/neorg/commit/7033c4bd2dc4633d0874b2da05b0ae67928b1117))
* **docgen:** implement `Required By` section ([15bf71b](https://github.com/katawful/neorg/commit/15bf71b15e07917e0f3a55de44e79fcdfbfc557d))
* **docgen:** implement configuration_options parsing logic ([b34658a](https://github.com/katawful/neorg/commit/b34658a21602fdd286889c2e57bf2d68d63d4472))
* **docgen:** implement function rendering, fix incorrect interpretation of function calls ([a023488](https://github.com/katawful/neorg/commit/a023488944473dfcd611308d5e21b7a9b2d7690d))
* **docgen:** implement table rendering ([9074328](https://github.com/katawful/neorg/commit/907432885e40a16f064d4406cd45efeb895f0962))
* **docgen:** indent nested table keys ([9cf679a](https://github.com/katawful/neorg/commit/9cf679a24f3bb9db145ae4dfbeb43878a49839e3))
* **docgen:** massive structure changes, implement proper table rendering ([42b8728](https://github.com/katawful/neorg/commit/42b8728f291072b9d8a11bdf9c7e205ef15fb94d))
* **docgen:** parse config tables ([93c41e1](https://github.com/katawful/neorg/commit/93c41e1f0aa290d0ad2e2590753312c71a782395))
* **docgen:** perform `[@module](https://github.com/module)` lookups, pasre complex data structures like tables ([19f2381](https://github.com/katawful/neorg/commit/19f23811ba0366fe3ec9423d26aec33d9d34fcc2))
* **docgen:** properly implement recursive table scanning ([33e06b8](https://github.com/katawful/neorg/commit/33e06b8d0fc2e7a9b386fc95e6bce4dfb714e56f))
* **docgen:** sort entries when rendering ([b420e70](https://github.com/katawful/neorg/commit/b420e70532766475bce0bf1d34129e711a31e21a))
* **docgen:** start generating true module pages ([5115d5c](https://github.com/katawful/neorg/commit/5115d5cd4bd1fefb11f82cb3e3da18b74d4e9b9e))
* fix injections ([99ae087](https://github.com/katawful/neorg/commit/99ae087892171df3b7bea71c5d4032e9d1e81801))
* **helpers/lib:** add `read_files` and `title` functions ([d59f41b](https://github.com/katawful/neorg/commit/d59f41b78755b102a41d172d4e3f64d59cb86b8b))
* **helpers:** add `ensure_nested` function ([2c4e8d0](https://github.com/katawful/neorg/commit/2c4e8d02feb7f1e6878307e7813a9f13ec000a73))
* **helpers:** Add wrapper to vim.notify ([#778](https://github.com/katawful/neorg/issues/778)) ([c278f6f](https://github.com/katawful/neorg/commit/c278f6f895c6b2f9ef4fc217ed867675108d804e))
* **highlights:** add conceals and spelling support ([d2568b8](https://github.com/katawful/neorg/commit/d2568b864751acda0e42205a7fd547becf01b24a))
* **highlights:** add support for anchors ([c2e7e4a](https://github.com/katawful/neorg/commit/c2e7e4ad36abea7f415a5c1313e20ff2324845a7))
* **highlights:** add support for headings, errors, escape sequences and definitions ([1f222a8](https://github.com/katawful/neorg/commit/1f222a89dbca9ace3788113595cc024cd2af590e))
* **highlights:** add support for new carryover tags and new verbatim ranged tags ([4758008](https://github.com/katawful/neorg/commit/47580083d6fb6133fafc77f613ef60a01295717c))
* **highlights:** add support for paragraph delimiters, regular markup and free form markup ([a53e982](https://github.com/katawful/neorg/commit/a53e9824809d04d5d64f08db2c670a1c5e88c7d8))
* **highlights:** add support for unordered and ordered lists and quotes ([1fc5828](https://github.com/katawful/neorg/commit/1fc58287fc33f2addbabf9ee206ea348e0eb47e6))
* **highlights:** reintroduce trailing mod, link modifier and links ([268b252](https://github.com/katawful/neorg/commit/268b252c098cdc8ef187c254d9307f767285a9b5))
* **highlights:** superscript in subscript and vice versa should be an error ([cc8c510](https://github.com/katawful/neorg/commit/cc8c5101ab1afea82473a5463649b394a1221142))
* **hop:** allow users to jump to timestamps ([22b12fb](https://github.com/katawful/neorg/commit/22b12fb2301582fd9552ab10ac0c934cda4d0a14))
* implement _Sidebar generation ([733b74c](https://github.com/katawful/neorg/commit/733b74c92481bc955f1f46594e50fb4931ab3cf5))
* implement `render_month` function ([343fb8d](https://github.com/katawful/neorg/commit/343fb8d02422fe2f2a3c791f2bdba0be95c3c96b))
* implement directory backup functionality ([20e9c43](https://github.com/katawful/neorg/commit/20e9c43a0b96500b758554441086589265e3020b))
* implement necessary APIs for complex data structure parsing ([b78f01c](https://github.com/katawful/neorg/commit/b78f01cd951b8ecfe7e842d31f609e6e4d5ac9db))
* implement new docgen featuring top-comment validation ([b77fbd5](https://github.com/katawful/neorg/commit/b77fbd52f96db049687901ac1f0a8aea7ab4bdfa))
* **indent:** adapt indentation of nestable detached modifiers when a detached modifier extension is found ([56e59da](https://github.com/katawful/neorg/commit/56e59daff56ba7f4d76b11ff3fc6dd70c4b54524))
* **integrations.treesitter:** add a public `parser_path` variable so the user doesn't have to recompute it every time ([ff6c591](https://github.com/katawful/neorg/commit/ff6c59154bd48100c1056040093c0898cd809d17))
* **journal:** allow `custom` to take in no arguments, in which case ([ea0497a](https://github.com/katawful/neorg/commit/ea0497aea783507ce640e909b6764be4fcd5a388))
* keep checkboxes with `core.itero` ([#663](https://github.com/katawful/neorg/issues/663)) ([00532bd](https://github.com/katawful/neorg/commit/00532bd997d2aef0384ed8f11500d33d229a7e53))
* **keybinds:** add default keybinds for `core.pivot` ([2f49628](https://github.com/katawful/neorg/commit/2f496283504dcfb30d9ee60101a8290e743c1753))
* **keybinds:** warn when a deprecated keybind is used (will be removed with `5.0`) ([e20d3c3](https://github.com/katawful/neorg/commit/e20d3c324b091cac29ccd7ec8431d24aa9b792c8))
* make `core.upgrade` install old parser before upgrading to new syntax ([ed68224](https://github.com/katawful/neorg/commit/ed68224e95e129a5a6812e2833dcd778d5d168e4))
* **makefile:** add `local-documentation` option ([ed20f79](https://github.com/katawful/neorg/commit/ed20f796f5bb337d230f5d33a3f6ba420a8d30a4))
* migrate to `core.fs` APIs, work with nested directories ([eacaf72](https://github.com/katawful/neorg/commit/eacaf7297045592b15ee87d52762bb2c2b52716d))
* **pivot:** add `core.pivot.invert-list-type` keybind ([2d0446a](https://github.com/katawful/neorg/commit/2d0446a2d8e3789bbd17bbb3cb97e73befccb327))
* place cursor over current day when creating calendar ([3ce268b](https://github.com/katawful/neorg/commit/3ce268b703d321561b86e546c7633326b39fa494))
* **promo:** add `&lt;C-t&gt;` and `<C-d>` support, fix quotes and list items ([2c9d9c0](https://github.com/katawful/neorg/commit/2c9d9c0717ca1aaa2096e89425ad15bd4a67d020))
* **qol.todo_items:** add new `create_todo_items` option ([d810aa4](https://github.com/katawful/neorg/commit/d810aa43c96301db35af351306eab54e35071d57))
* **qol.todo_items:** add new `create_todo_parents` option (false by default) ([6b6ef04](https://github.com/katawful/neorg/commit/6b6ef04e5fb0a5b1c3ff59699a9371afd659d9ff))
* **qol.todo_items:** refactor code to support any TODO item on any object ([de7edc9](https://github.com/katawful/neorg/commit/de7edc90842d7c348021718fa472dba66c623341))
* **qol.todo_items:** when only done and uncertain items are present in ([1d6b0b0](https://github.com/katawful/neorg/commit/1d6b0b056b097e9f4bacf8877c49fdacbc445b2c))
* start using dev parser ([8bf9786](https://github.com/katawful/neorg/commit/8bf97866e7d5380704926d1ea2c4b3dfe0ff0d4d))
* start work on highlights ([ea29a2e](https://github.com/katawful/neorg/commit/ea29a2ebf6712f64166df23d2c7a2d02e79caa14))
* strip leading `--` from comments ([ecea630](https://github.com/katawful/neorg/commit/ecea6305a82007b6c8c509fd594f8b52c3331021))
* **summary:** implement `metadata` strategy and reimplement summary generation code ([f948288](https://github.com/katawful/neorg/commit/f9482881315d49d0a35206c7936a7f48c20dfcbf))
* support 80% of all the syntax ([5265936](https://github.com/katawful/neorg/commit/52659361866bd7ea431a62d20a49ad9da4b5f973))
* support exporting single files ([8d7e06d](https://github.com/katawful/neorg/commit/8d7e06dd06b218f890a52a8b67c1f98e179f4369))
* **tempus:** add `,id` (insert date) keybinding ([34f13ba](https://github.com/katawful/neorg/commit/34f13ba253c160e72ef7817a950508430ed050d1))
* **tempus:** add `to_lua_date` function ([ef62e53](https://github.com/katawful/neorg/commit/ef62e5308c684468a822684382d14de8f8f63193))
* **tempus:** add insert mode `&lt;M-d&gt;` keybind to insert a date ([b420f69](https://github.com/katawful/neorg/commit/b420f69602b23fa8fc2f7f6526f49838f9521b10))
* **tempus:** allow dates to be converted to norg-compatible dates with `tostring()` ([3ec5f96](https://github.com/katawful/neorg/commit/3ec5f96dfd673c2c2a34b09748518accf61ec677))
* **toc:** add `close_after_use` configuration option ([#785](https://github.com/katawful/neorg/issues/785)) ([e5d7fbb](https://github.com/katawful/neorg/commit/e5d7fbb0291e658f78545c29318c9162cf505d15))
* **treesitter:** add `execute_query` function ([310ebaa](https://github.com/katawful/neorg/commit/310ebaaef538dfd41d02a2903663be05fd38834b))
* **upgrade:** add upgrade tool barebones ([e30f780](https://github.com/katawful/neorg/commit/e30f780c91a0dfebf4ee669b54423dcba4025e1e))
* **upgrade:** more barebones ([07b4d50](https://github.com/katawful/neorg/commit/07b4d506aea552948d2f5512260381fcb8266528))
* warn access to `core.norg` modules instead of breaking ([ed761a5](https://github.com/katawful/neorg/commit/ed761a5c5a9100861034b31978049401444fd6fb))


### Bug Fixes

* `:Neorg journal today` would fail on alternative path separators ([#749](https://github.com/katawful/neorg/issues/749)) ([e7a5054](https://github.com/katawful/neorg/commit/e7a50542ad9921a8c7d652eeca6a9006cc024b79))
* `count` not working with `&gt;>` and `&lt;<` ([f3557ef](https://github.com/katawful/neorg/commit/f3557ef9af79322a649e6e03b10d573b608d6dbe))
* `file_exists` ignoring cwd/workspace difference ([#673](https://github.com/katawful/neorg/issues/673)) ([fd6d0bf](https://github.com/katawful/neorg/commit/fd6d0bf99b64e761b0f028f2673bfdd41becfb92))
* `file_exists` ignoring cwd/workspace difference ([#673](https://github.com/katawful/neorg/issues/673)) ([7594364](https://github.com/katawful/neorg/commit/75943647b6e894639d5386f62252e35a0e777a63))
* a few bugs with the insertion conversion ([02fbf3a](https://github.com/katawful/neorg/commit/02fbf3a301a57a73f9edb0b65fca969912a2ca00))
* always flush storage after changing news state ([b6558f0](https://github.com/katawful/neorg/commit/b6558f096ef4a93c15ccfebf7667d00e30e9f3c8))
* **base.lua:** don't assign the `extension` flag to parent modules, only to the imports themselves ([fa5f561](https://github.com/katawful/neorg/commit/fa5f56163510eb00a0d75bec81d40d901c175d3b))
* **calendar:** allow the view to be written to on rerender ([8e247d4](https://github.com/katawful/neorg/commit/8e247d414bcb0d1123b2b12c7ff29bdf36c50cbd))
* **calendar:** fix incorrect movement with `H` across boundaries of months with different lengths ([48face2](https://github.com/katawful/neorg/commit/48face25855d7844302b13a125363c30b8a6fe9a))
* **calendar:** fix rest of highlight groups ([ead4c4c](https://github.com/katawful/neorg/commit/ead4c4c53769839b5063fab71ebb92d155d53676))
* **calendar:** if another calendar is open then close it instead of erroring ([9751e7d](https://github.com/katawful/neorg/commit/9751e7d62af0b7e49ff788058154b966be205e2e))
* **calendar:** make distance between each month uniform and support modifying the distance between each month ([746354d](https://github.com/katawful/neorg/commit/746354dea70e9657f61531375329e407e7f5a203))
* **calendar:** make month rendering work again ([164028f](https://github.com/katawful/neorg/commit/164028fd621e3c5b56603d88d6d5e2ba5db51d42))
* **calendar:** overlapping month names in the calendar view ([709cf78](https://github.com/katawful/neorg/commit/709cf78410b6ea631192ad004d3f2b83761f9953))
* **calendar:** prevent the buffer from being modifiable after it has been filled ([351e103](https://github.com/katawful/neorg/commit/351e10326e0e2bb6166e165ddb6598e917e6d25c))
* **calendar:** properly display "today's day" in the calendar view ([74ee71a](https://github.com/katawful/neorg/commit/74ee71a446662f92afa3cbd49f6c980bdf25ae92))
* **calendar:** reversed namespace names ([77b214c](https://github.com/katawful/neorg/commit/77b214cef220580cdcf527265a15ef980e7bcaf3))
* check absolute path for journal template file ([#683](https://github.com/katawful/neorg/issues/683)) ([5613ff3](https://github.com/katawful/neorg/commit/5613ff3f471d148c9824daeb359dfdc61ddaf992))
* **clipboard.code-blocks:** don't cut off characters from non-visual-line selection ([744ae49](https://github.com/katawful/neorg/commit/744ae49fe5fab9e54de96282778a202f85a2f37b))
* **code.looking-glass:** Use last attribute as start row of looking-glass (fix [#777](https://github.com/katawful/neorg/issues/777)) ([beef6fd](https://github.com/katawful/neorg/commit/beef6fd9420d6a798ddd796779b96f006b14ca12))
* **commands.return:** don't override the workspace to `default` after running `:Neorg return` ([169c7be](https://github.com/katawful/neorg/commit/169c7bee8a5f101c63c3a473a577dce079f7ddec))
* completion for TODO items ([#711](https://github.com/katawful/neorg/issues/711)) ([9184027](https://github.com/katawful/neorg/commit/91840274112f1286ff5f4063ac6f515683b6dc67))
* **concealer:** broken delimiters ([75f2115](https://github.com/katawful/neorg/commit/75f2115e56ea9077aeda9f8f52846d85ede9729f))
* **concealer:** buggy debounce logic causing visual artifacts (especially on the first line of a buffer) ([45388fc](https://github.com/katawful/neorg/commit/45388fc0478e8d1273bd80789e7e1af1df76458f))
* **concealer:** make concealer work with new syntax ([dc90b01](https://github.com/katawful/neorg/commit/dc90b01a7b6ca4a3dc36849460d619d4d53ff3b4))
* **concealer:** stop concealer if buffer is not loaded ([#836](https://github.com/katawful/neorg/issues/836)) ([6aa9fd3](https://github.com/katawful/neorg/commit/6aa9fd303c807ed1ca3fb15cdeab1e322d02fd31))
* **concealer:** whenever running any scheduled command ensure that the buffer exists first ([b926416](https://github.com/katawful/neorg/commit/b9264161d0ef10ee61ace6ebeb0a55ca461b638a))
* **core.clipboard.code-blocks:** module would not work past version `1.0.0` ([ac88283](https://github.com/katawful/neorg/commit/ac8828369cb2a4b2e1e17e6b495645585ed2a37b))
* **core.clipboard.code-blocks:** visual selection would cut off one character too little ([87ed4bf](https://github.com/katawful/neorg/commit/87ed4bfde4a00a4cf4279298de02280bf11c7a74))
* **core.export.markdown:** incorrectly exported code blocks ([dd2750c](https://github.com/katawful/neorg/commit/dd2750c0e4d847b67a6ead79ff5043e671cac8bd))
* **core.export.markdown:** Update markdown exporter for new todo syntax (fix [#757](https://github.com/katawful/neorg/issues/757)) ([336416f](https://github.com/katawful/neorg/commit/336416f6c41777a4025cc80b8a085e21e758931f))
* **core.export:** incorrect exporting of code blocks with no parameters ([#701](https://github.com/katawful/neorg/issues/701)) ([0922815](https://github.com/katawful/neorg/commit/0922815837a374bd0b2a3cf0477b54e6668e133d))
* **core.fs:** show detailed error message when copy fails ([c7174e0](https://github.com/katawful/neorg/commit/c7174e03ab01f202bb9d8b71a6945c6c2a2cd037))
* **core.highlights:** broken or nonexistent highlights for a few syntax elements ([061e56b](https://github.com/katawful/neorg/commit/061e56bfdc9d7862fc2e7821a17abb13d37ca412))
* **core.itero:** preserve indentation on continued items ([92c31c4](https://github.com/katawful/neorg/commit/92c31c491caedd7d1a82b42d4ba6c2227c05d930))
* **core.looking-glass:** buffer being closed for no reason after leaving buffer ([828a37f](https://github.com/katawful/neorg/commit/828a37fe1f008dbfd70cd7fc0f7ba9d0bc75da2a))
* **core.norg.esupports.hop:** Make hop on anchors work again ([#756](https://github.com/katawful/neorg/issues/756)) ([d38a229](https://github.com/katawful/neorg/commit/d38a22940aaa55351cd4dc106540fa302fad4f0d))
* **core.norg.journal:** add proper error handling for `vim.loop.fs_scandir` ([4a9a5fe](https://github.com/katawful/neorg/commit/4a9a5fe13cd454692fc4db0b27783cd005e6be56))
* **core.norg.journal:** fixes [#736](https://github.com/katawful/neorg/issues/736) , now generates TOC correctly ([19c5558](https://github.com/katawful/neorg/commit/19c555836bc31f482e0ea42f08d150110754644f))
* **core.norg.news:** attempt at fixing perpetual "new news" message ([afa6013](https://github.com/katawful/neorg/commit/afa6013d5de8347934fda8da65ec87785ff1e50d))
* **core.norg.news:** attempt at fixing perpetual "new news" message ([0b46a9a](https://github.com/katawful/neorg/commit/0b46a9ae7e40037fced280131bef7fdc25a2041d))
* **core.promo:** don't error when the concealer is not loaded ([#767](https://github.com/katawful/neorg/issues/767)) ([3e09f69](https://github.com/katawful/neorg/commit/3e09f698b8a4151f2b4f77ee917e4b54388bc97a))
* **core.summary:** wrong module name in header, wrong internal command names ([a046900](https://github.com/katawful/neorg/commit/a0469001430a68f521d3292f8a8252655cfda941))
* **core.syntax:** make module work with latest syntax ([d1d1218](https://github.com/katawful/neorg/commit/d1d121890fbc58c55dafbac347e27333e62cd663))
* **core.ui.calendar:** logic error when parsing virt_text length for `set_logical_extmark` ([d5b29ee](https://github.com/katawful/neorg/commit/d5b29eea8e09d7bd0add778c6818539719914301))
* **core.ui.calendar:** wrong extmark being queried in month render routine ([46624b9](https://github.com/katawful/neorg/commit/46624b9a02e0d0e928026a0fd4852c4dd3ca7e0d))
* **core.ui:** clear the `winbar` option in Neorg popups to prevent "not enough room" errors ([fcebf9f](https://github.com/katawful/neorg/commit/fcebf9f6caf0667f99b1481e2c0a49f0eeb68fe9))
* **core.ui:** do not modify the user's `scrolloffset` ([bd2e58c](https://github.com/katawful/neorg/commit/bd2e58cf6f9d42527aa2b692fb187eafa82bd91e))
* **core.upgrade:** allow nil values to be returned by the generic `get_node_text` call ([27ecbe2](https://github.com/katawful/neorg/commit/27ecbe28753a76aab8db5fe2f2fde65452c3bf78))
* **core.upgrade:** allow nil values to be returned by the generic `get_node_text` call ([e45e34a](https://github.com/katawful/neorg/commit/e45e34aeb5bba218511e59cf74a6fc2c6e144740))
* **core.upgrade:** attached modifiers would not be preserved ([5c297f3](https://github.com/katawful/neorg/commit/5c297f3fc5e7c7c2314a026b28ca4670e34e97a7))
* **core.upgrade:** attached modifiers would not be preserved ([d219d0b](https://github.com/katawful/neorg/commit/d219d0b200700b0b8b96f90065d83b977aa9831f))
* **core.upgrade:** insertions would be upgraded with an extraneous newline if they had parameters ([1f05ed9](https://github.com/katawful/neorg/commit/1f05ed90707c66dc75a0aaff81b2b2e34b113662))
* **core.upgrade:** insertions would be upgraded with an extraneous newline if they had parameters ([5a77759](https://github.com/katawful/neorg/commit/5a77759f763e5170b3cb0bb04a3ece0e051fcaf4))
* **core.upgrade:** pass `buffer` as an argument to `get_node_text` ([b0ecb24](https://github.com/katawful/neorg/commit/b0ecb24fd3262ba6edc7642fe01d53d1fd87d5ed))
* **core.upgrade:** pass `buffer` as an argument to `get_node_text` ([c6b6154](https://github.com/katawful/neorg/commit/c6b6154912c0189446f50aab82ba0671a788ca38))
* **core.upgrade:** preserve indentation in upgraded file ([7a58cbb](https://github.com/katawful/neorg/commit/7a58cbb8e11de7b6e55aea425aadc033ee8e155d))
* **core.upgrade:** preserve indentation in upgraded file ([8066183](https://github.com/katawful/neorg/commit/80661832c9be783b9664551b909843c89da7bc36))
* **core.upgrade:** tag parameters being incorrectly upgraded ([7ff3efc](https://github.com/katawful/neorg/commit/7ff3efc9b8392e03c8c283c90c37e5d7b77089cf))
* **core.upgrade:** tag parameters being incorrectly upgraded ([791823c](https://github.com/katawful/neorg/commit/791823cf8d096401afb97920c9583d9b9e617004))
* **core.upgrade:** work properly with nested subdirectories ([a2f7062](https://github.com/katawful/neorg/commit/a2f70626228a29b0cfa2543cc5602f24d3ede176))
* **dirman.expand_path:** search for both `$/` and `$\` in links to support windows paths ([#830](https://github.com/katawful/neorg/issues/830)) ([160d40f](https://github.com/katawful/neorg/commit/160d40f5261be5149842942adbf260d6e359d9ec))
* **dirman:** automatically create the index file if it exists when running `:Neorg index` ([7ce2db5](https://github.com/katawful/neorg/commit/7ce2db5d2eeec37b4a4c4bc43009c4741c3755da))
* **dirman:** corrected win width and height calculation ([9766bef](https://github.com/katawful/neorg/commit/9766bef893ec993af9408ea0d44a8f13adbd1e80))
* **dirman:** don't create `index.norg` files in the default workspace when running `:Neorg index` ([c60747f](https://github.com/katawful/neorg/commit/c60747fcc567d7eb50b16c2007bcfd3a81a934d1))
* do not run tests for nightly/neorg-main, as GTD is no longer existent ([37f1f9a](https://github.com/katawful/neorg/commit/37f1f9a44ba65603b5992fc36761c61d921fab78))
* **docgen:** `&lt;h6&gt;` tags not being rendered properly ([d0a0da0](https://github.com/katawful/neorg/commit/d0a0da017135b48c5f4a325bfaedbcdf1ca79fe3))
* **docgen:** could not find module `neorg` ([b68a945](https://github.com/katawful/neorg/commit/b68a945d6b1a8c2f8c57e0c366f224a162f391e3))
* **docgen:** display listed modules in alphabetical order ([264b451](https://github.com/katawful/neorg/commit/264b451d74d3e4bc3f856d087070b9dac46f8e90))
* **docgen:** don't double-render numeric values ([35df191](https://github.com/katawful/neorg/commit/35df1918de321617972f10edd88d9c32cc8102a2))
* **docgen:** don't render description tags if no description is present ([64dc28d](https://github.com/katawful/neorg/commit/64dc28deea9a7f9c52c3ba5343f1ce3c754a566e))
* **docgen:** don't unnecessarily copy parsers ([46e7936](https://github.com/katawful/neorg/commit/46e79366775136592540fbe5f0532c001012daa5))
* **docgen:** incorrect wiki paths ([2dbead6](https://github.com/katawful/neorg/commit/2dbead687053610147161ecda1a908070720731f))
* **docgen:** installation documentation link for wiki ([ba8b31d](https://github.com/katawful/neorg/commit/ba8b31dc2491f80b9f65fadbafdfd94d6ef26988)), closes [#548](https://github.com/katawful/neorg/issues/548)
* **docgen:** internal modules that were part of `core.defaults` would not be displayed in the developer modules section ([c3099eb](https://github.com/katawful/neorg/commit/c3099ebd595d3ec491613c297f4199e316f85853))
* **docgen:** list items with no summary would break rendering ([b69ea57](https://github.com/katawful/neorg/commit/b69ea57029a2c62e72ea86c93d295102059c58ab))
* **docgen:** lists within lists would never be rendered ([06894bb](https://github.com/katawful/neorg/commit/06894bb090ad6deb52ba7b19f7e13bbb41385a63))
* **docgen:** make the spacing nicer to look at ([426ca24](https://github.com/katawful/neorg/commit/426ca246e310a212cef5f6bba367d7ebc84bf70b))
* **docgen:** remove debug log ([8ffcaed](https://github.com/katawful/neorg/commit/8ffcaed1095743b8474a16f25855b809cf4fe65d))
* **docgen:** this should work now i think (after 20 tries) ([72d3d49](https://github.com/katawful/neorg/commit/72d3d4981d85fd1114d3185e40cc135a7892a4a4))
* **docgen:** use minimal_init.vim instead of custom_init.vim ([a7cb7ab](https://github.com/katawful/neorg/commit/a7cb7ab443c24fbd1d9f696abddd91c16f05d842))
* **docgen:** wrong `require` order in `docgen.lua` ([7494b51](https://github.com/katawful/neorg/commit/7494b51a61cc31371514cb7b2e1ccdf4cef164e2))
* **docs:** incorrect parameter type ([#681](https://github.com/katawful/neorg/issues/681)) ([df159e1](https://github.com/katawful/neorg/commit/df159e12865f205dc64900e361167a13df827249))
* don't allow tempus to load unless the Neovim ver is at least 0.10.0 ([c4429fa](https://github.com/katawful/neorg/commit/c4429fa1e1eb0c3c5652495b00aa4e1c56068914))
* don't use multiline strings in `vim.ui.select` ([d585d64](https://github.com/katawful/neorg/commit/d585d6441aff5bacb3b6a48f68dce64e1ceb33a8))
* don't use multiline strings in `vim.ui.select` ([0fa908f](https://github.com/katawful/neorg/commit/0fa908fadee76347cdddb6b9506b83244443503e))
* **esupports.hop:** anchors to files woul dresult in a "link not found" ([#688](https://github.com/katawful/neorg/issues/688)) ([3009adf](https://github.com/katawful/neorg/commit/3009adf2cf48aedcbb309d0765e0fbbb64a0fdf4))
* **esupports.hop:** broken definitions and footnotes ([#733](https://github.com/katawful/neorg/issues/733)) ([94cf7d2](https://github.com/katawful/neorg/commit/94cf7d2889b386ce1313e80c8c04adf18872c028))
* **esupports.hop:** support new syntax as well as footnotes and definitions ([f09cebb](https://github.com/katawful/neorg/commit/f09cebb1277bf815bf28e44794732713dfc94318))
* **export.markdown:** start work on fixing markdown exporter ([c3b1b86](https://github.com/katawful/neorg/commit/c3b1b86dd83c50c3cf051287ebfb4390b52fcdcf))
* **export:** `gsub` export links that contain `#`, `?`. closes [#807](https://github.com/katawful/neorg/issues/807) ([#816](https://github.com/katawful/neorg/issues/816)) ([7f3a3b8](https://github.com/katawful/neorg/commit/7f3a3b850c8d4b73e7f85971aae2a96162bcb150))
* **export:** markdown export for horizontal_line ([#820](https://github.com/katawful/neorg/issues/820)) ([2178447](https://github.com/katawful/neorg/commit/217844796e00a1cea7c051435f9c49bee25e7caa))
* **export:** metadata should not be exported if the extension is disabled ([aeac26b](https://github.com/katawful/neorg/commit/aeac26be58a6aa53ab615e1ad468389a7c311536))
* finalize `version_in_code.yml` CI (it works yay) ([db9ed0b](https://github.com/katawful/neorg/commit/db9ed0b98ba30e2b783ea9da0fddda4cf6b2a47e))
* **folds:** correctly fold document metadata ([adc000a](https://github.com/katawful/neorg/commit/adc000aadd41e68e4de8a2d1bb90b2e910ffef1b))
* **highlights.scm:** free form open/close chars would not be concealed ([5de014e](https://github.com/katawful/neorg/commit/5de014e7cc3dc6eed0a62854fe8ba58f664d97ea))
* **highlights.scm:** incorrect concealing for anchors ([8a2979b](https://github.com/katawful/neorg/commit/8a2979beb15c38a85133e83d805906590002453b))
* **hop:** assume &lt;current-day&gt; when some parameters to dates are not supplied ([65bf064](https://github.com/katawful/neorg/commit/65bf06493ecb411b1589ad345771ae29aa17cd33))
* **indent:** indenting within code blocks ([76ea526](https://github.com/katawful/neorg/commit/76ea5269e9b75f6b23d46ddc188ca2e3f96edcb4))
* infinite loop with directory upgrade ([8b4472c](https://github.com/katawful/neorg/commit/8b4472c5c7c99824debc4c6bc6d980322a0bfa4e))
* infinite loop with directory upgrade ([f481379](https://github.com/katawful/neorg/commit/f4813795dddb68959e68fea2f5fa9c5f82963896))
* **integrations.treesitter:** broken `get_tag_info` logic ([9332c17](https://github.com/katawful/neorg/commit/9332c17e664601076c4f79514cc2cb8d5c374fce))
* **integrations.treesitter:** index out of bounds error for specific nodes (fixes `core.upgrade` errors) ([ad2f573](https://github.com/katawful/neorg/commit/ad2f5735c837046a40efef9aad70d01af5acd076))
* **keybinds.lua:** remove dead `toc` keybinds ([06666f2](https://github.com/katawful/neorg/commit/06666f298e146d758d691366ca3465a3bd1e3f7f))
* **looking-glass:** support new syntax ([d72569c](https://github.com/katawful/neorg/commit/d72569ca38996e2691942f6d761a6c5b66c86a2d))
* **metagen:** support new syntax and fix broken update behaviour ([0f842f6](https://github.com/katawful/neorg/commit/0f842f6ea97c028cacc6283ab14642e43db253d9))
* **metagen:** use `norg_version` ([a5c2553](https://github.com/katawful/neorg/commit/a5c25531de2790133310ad874fcbbb976d082c78))
* neovim 0.9 vim.treesitter.parse_query deprecation ([#784](https://github.com/katawful/neorg/issues/784)) ([f4a9759](https://github.com/katawful/neorg/commit/f4a9759e53fadaece9d93118a0471ddffd05d394))
* **promo:** don't add whitespace to empty lines ([#852](https://github.com/katawful/neorg/issues/852)) ([a7291f4](https://github.com/katawful/neorg/commit/a7291f4662664d0c3be3016adff6767dc52f907d))
* **qol.toc:** display headings with TODO statuses unless the status is "cancelled" ([2e44346](https://github.com/katawful/neorg/commit/2e44346813310de9afc411e2348cf2be8540f70c))
* **qol.toc:** support new syntax (infirm tag vs insertions) ([15efe92](https://github.com/katawful/neorg/commit/15efe92ff00c9c42b0b2fbb6aea7ac1e94981423))
* **qol.todo_item:** `&lt;C-space&gt;` would not create a new TODO item with ([fc45beb](https://github.com/katawful/neorg/commit/fc45bebde0fc9811ca4e770e2ba29c791035c885))
* **qol.todo_items:** `&lt;C-space&gt;` would not respect the `create_todo_items` option ([e764b92](https://github.com/katawful/neorg/commit/e764b92065ddd6bc206aaefd92837be8d0bd8419))
* **qol.todo_items:** don't updated nested objects of different types ([a11ad7c](https://github.com/katawful/neorg/commit/a11ad7c0071c5bafad7ac6f582642d725c228a6a))
* **qol.todo_items:** TODO attributes would be erroneously assigned multiple times ([1303097](https://github.com/katawful/neorg/commit/13030974acee5a49dd02c51bedeac104b4f33cb7))
* remove calendar as a dependency of `core.ui`, fix errors for people not on nightly ([cd26a22](https://github.com/katawful/neorg/commit/cd26a220e999cc9103a2502299d16ae8e6fab4d9))
* respect `check_news` flag in `core.norg.news` ([196f6b8](https://github.com/katawful/neorg/commit/196f6b8d775afa6d08460a23ba83fa4b5be0d989))
* set filetype when creating new norg buffer ([#672](https://github.com/katawful/neorg/issues/672)) ([1f60ae7](https://github.com/katawful/neorg/commit/1f60ae75620ed6e533915a7baa76a3b09de17e9e))
* set filetype when creating new norg buffer ([#672](https://github.com/katawful/neorg/issues/672)) ([605c978](https://github.com/katawful/neorg/commit/605c9784fdc44fe462d97f321264fc5c940d6ea3))
* stop syntax processing if a buffer is already closed ([#859](https://github.com/katawful/neorg/issues/859)) ([cc2834a](https://github.com/katawful/neorg/commit/cc2834ae2beb2d5baa75d15848a94dae022faa2c))
* **summary:** appropriately indent nested entries ([b725a58](https://github.com/katawful/neorg/commit/b725a58f25525efc1c39a13a09e6cec0c1c0ba4d))
* **summary:** broken wiki entry ([69fbabf](https://github.com/katawful/neorg/commit/69fbabfb5764cd164453a764174cf5cfa813ae60))
* **tangle:** support new syntax ([827c1f8](https://github.com/katawful/neorg/commit/827c1f81683b721e4c0c37cb41e7bcc8f94a3816))
* **tempus:** days like `4th`/`2nd` would not get parsed properly ([7368a8a](https://github.com/katawful/neorg/commit/7368a8ae10a0bab32729bd00dcac6f24cb55a8ef))
* **tempus:** do not assume `osdate` has all fields set ([c37a104](https://github.com/katawful/neorg/commit/c37a104c992326f8924de783d667f7c4c34f92b7))
* **tempus:** don't use the `re` module if it doesn't exist ([#872](https://github.com/katawful/neorg/issues/872)) ([3c99638](https://github.com/katawful/neorg/commit/3c99638db0ce4293e221216bdda03a55da6ad82b))
* **tempus:** paste correct weekday from calendar ([ba54231](https://github.com/katawful/neorg/commit/ba54231e14a31c0571ff7baa4828de121a5e3072))
* **tempus:** properly handle conversions w.r.t Sun-Sat/Mon-Sun ([e39fa1b](https://github.com/katawful/neorg/commit/e39fa1b1626fc6f4bb9f4695b15d7065561c2567))
* **treesitter:** don't constantly log errors about erroneous document syntax trees ([9f8b0a1](https://github.com/katawful/neorg/commit/9f8b0a1759d883fae901579ea83b3ffbfc81a53b))
* **treesitter:** fix `get_tag_info()` not querying information about carryover tags ([883b37c](https://github.com/katawful/neorg/commit/883b37ce7e67cf7ce0d30a9a8ee49eee5693e314))
* **ts:** use earlier revision of the `dev` parser ([ca69af6](https://github.com/katawful/neorg/commit/ca69af63429a7b5d7f865bd0de848be2862b4ca6))
* update links for the documentation ([#687](https://github.com/katawful/neorg/issues/687)) ([ea26542](https://github.com/katawful/neorg/commit/ea265425ddf116a4cb9777fe63b23104e52e343d))
* update links for the documentation ([#687](https://github.com/katawful/neorg/issues/687)) ([a79bf59](https://github.com/katawful/neorg/commit/a79bf5969e27a3f1f1478c9b05c187815f2b2390))
* update to latest `dev` parser revision (broken highlights) ([b636d9f](https://github.com/katawful/neorg/commit/b636d9f4e68f6129efa7fdc5d48d2f6683530bce))
* upgrade module not working with custom `vim.ui.select` ([836c5e7](https://github.com/katawful/neorg/commit/836c5e7f0ad7d75e1a39a0da9c3fb40b769c8caf))
* upgrade module not working with custom `vim.ui.select` ([25b0b76](https://github.com/katawful/neorg/commit/25b0b76f759ef79a2e4c3836c3ec75ef33e6885b))
* **version_in_code.yml:** perform checkout in the current directory ([3d7ad5a](https://github.com/katawful/neorg/commit/3d7ad5aa4b1277ea0f3ebb93ea79179eda5f6e27))
* **version_in_code.yml:** use `fetch-depth` of `0` ([2e8fa52](https://github.com/katawful/neorg/commit/2e8fa524d2cc73002378875970048d70ae70cc0b))


### Performance Improvements

* **concealer:** don't rerender the whole file on every single BufEnter ([7419cbb](https://github.com/katawful/neorg/commit/7419cbb7262200dd94df9d398ee1e7f5b9503a50))
* further optimize `toc` infirm tag grabber ([5e8d059](https://github.com/katawful/neorg/commit/5e8d05968e04f7945576d50a6b1576cc722f96fc))
* optimize the `toc` infirm tag grabber code ([a41bd4a](https://github.com/katawful/neorg/commit/a41bd4a92afefb7e2630b821b59f7707a054baac))


### Reverts

* **core.upgrade:** remove async execution checks which would cause infinite loops ([da91a71](https://github.com/katawful/neorg/commit/da91a711dfa33adf9407b06b9f53b5fb794907b0))
* **core.upgrade:** remove async execution checks which would cause infinite loops ([45352e6](https://github.com/katawful/neorg/commit/45352e60f89584b75c67ef765f6c0acb84c85d45))


### Miscellaneous Chores

* **docgen:** wipe whole wiki on every reparse ([09cb3e6](https://github.com/katawful/neorg/commit/09cb3e62022ff0f93965800a728ed698db540240))


### ref

* **core.norg.qol.toc:** rewrite the table of contents implementation ([c0104fb](https://github.com/katawful/neorg/commit/c0104fb9faed3b3213e4e275a55a522a299a2d0e))
* **dirman:** do not alter the user's cwd, ever ([8c36362](https://github.com/katawful/neorg/commit/8c36362481c094e9dc4e26e495e969ae58ba0f14))
* **dirman:** do not alter the user's cwd, ever ([12b96d8](https://github.com/katawful/neorg/commit/12b96d80b2c4364b2988ef6b325d6c3632b1014c))
* **dirman:** make the behaviours of `default_workspace` and `open_last_workspace` more logical ([0b95af1](https://github.com/katawful/neorg/commit/0b95af1406c8da27e21c5df610a164538f62150d))
* **dirman:** make the behaviours of `default_workspace` and `open_last_workspace` more logical ([59fdfdf](https://github.com/katawful/neorg/commit/59fdfdf293a8677824c871f8675fea7a53ef3795))
* **Makefile:** remove `install_pre_commit` target ([9a497f5](https://github.com/katawful/neorg/commit/9a497f5e8195e5b974d520f937a946cb8819f320))
* move `core.norg.dirman.summary` -&gt; `core.summary` ([254b6a6](https://github.com/katawful/neorg/commit/254b6a60b6c9f845400d2bcb0728ee7f38823781))
* NUKE GTD ([7c1a18a](https://github.com/katawful/neorg/commit/7c1a18a91317f0e212ef5c2535d5eee55a36b0ef))
* **summary:** refactor of the `core.norg.dirman.summary` module ([a2fe3ee](https://github.com/katawful/neorg/commit/a2fe3eea24c628fa15b7f854cef6c7acaf9ec3f9))


### Code Refactoring

* move all `core.norg.*` modules into `core.*` ([a5824ed](https://github.com/katawful/neorg/commit/a5824edf6893b8602e560ed7675c0d4174e263e4))
* move all `gt*` keybinds to `&lt;LocalLeader&gt;t*` ([f67110d](https://github.com/katawful/neorg/commit/f67110d11d37fde09756eb2de8a1814d04a4a03b))
* remove `core.news` ([4086d9f](https://github.com/katawful/neorg/commit/4086d9f17d823cfe5a13e7b12b30e13b5d3b796d))

## [4.4.1](https://github.com/nvim-neorg/neorg/compare/v4.4.0...v4.4.1) (2023-05-17)


### Bug Fixes

* **tempus:** paste correct weekday from calendar ([ba54231](https://github.com/nvim-neorg/neorg/commit/ba54231e14a31c0571ff7baa4828de121a5e3072))
* **tempus:** properly handle conversions w.r.t Sun-Sat/Mon-Sun ([e39fa1b](https://github.com/nvim-neorg/neorg/commit/e39fa1b1626fc6f4bb9f4695b15d7065561c2567))

## [4.4.0](https://github.com/nvim-neorg/neorg/compare/v4.3.0...v4.4.0) (2023-05-16)


### Features

* **journal:** allow `custom` to take in no arguments, in which case ([ea0497a](https://github.com/nvim-neorg/neorg/commit/ea0497aea783507ce640e909b6764be4fcd5a388))


### Bug Fixes

* **promo:** don't add whitespace to empty lines ([#852](https://github.com/nvim-neorg/neorg/issues/852)) ([a7291f4](https://github.com/nvim-neorg/neorg/commit/a7291f4662664d0c3be3016adff6767dc52f907d))
* **tempus:** don't use the `re` module if it doesn't exist ([#872](https://github.com/nvim-neorg/neorg/issues/872)) ([3c99638](https://github.com/nvim-neorg/neorg/commit/3c99638db0ce4293e221216bdda03a55da6ad82b))

## [4.3.0](https://github.com/nvim-neorg/neorg/compare/v4.2.0...v4.3.0) (2023-05-15)


### Features

* **calendar:** add `t` command for "today" ([e53a509](https://github.com/nvim-neorg/neorg/commit/e53a5099b5725162c8f0a626823cac4819a9427d))
* **hop:** allow users to jump to timestamps ([22b12fb](https://github.com/nvim-neorg/neorg/commit/22b12fb2301582fd9552ab10ac0c934cda4d0a14))


### Bug Fixes

* **hop:** assume &lt;current-day&gt; when some parameters to dates are not supplied ([65bf064](https://github.com/nvim-neorg/neorg/commit/65bf06493ecb411b1589ad345771ae29aa17cd33))
* **tempus:** days like `4th`/`2nd` would not get parsed properly ([7368a8a](https://github.com/nvim-neorg/neorg/commit/7368a8ae10a0bab32729bd00dcac6f24cb55a8ef))

## [4.2.0](https://github.com/nvim-neorg/neorg/compare/v4.1.1...v4.2.0) (2023-05-15)


### Features

* **tempus:** add `,id` (insert date) keybinding ([34f13ba](https://github.com/nvim-neorg/neorg/commit/34f13ba253c160e72ef7817a950508430ed050d1))
* **tempus:** add insert mode `&lt;M-d&gt;` keybind to insert a date ([b420f69](https://github.com/nvim-neorg/neorg/commit/b420f69602b23fa8fc2f7f6526f49838f9521b10))
* **tempus:** allow dates to be converted to norg-compatible dates with `tostring()` ([3ec5f96](https://github.com/nvim-neorg/neorg/commit/3ec5f96dfd673c2c2a34b09748518accf61ec677))


### Bug Fixes

* don't allow tempus to load unless the Neovim ver is at least 0.10.0 ([c4429fa](https://github.com/nvim-neorg/neorg/commit/c4429fa1e1eb0c3c5652495b00aa4e1c56068914))
* **tempus:** do not assume `osdate` has all fields set ([c37a104](https://github.com/nvim-neorg/neorg/commit/c37a104c992326f8924de783d667f7c4c34f92b7))

## [4.1.1](https://github.com/nvim-neorg/neorg/compare/v4.1.0...v4.1.1) (2023-05-15)


### Bug Fixes

* remove calendar as a dependency of `core.ui`, fix errors for people not on nightly ([cd26a22](https://github.com/nvim-neorg/neorg/commit/cd26a220e999cc9103a2502299d16ae8e6fab4d9))

## [4.1.0](https://github.com/nvim-neorg/neorg/compare/v4.0.1...v4.1.0) (2023-05-14)


### Features

* add `core.tempus` module for date management ([b73ec2f](https://github.com/nvim-neorg/neorg/commit/b73ec2f5e1b11864ca0628a842a53a617d5851ce))
* add left-right cursor movement ([ea588bb](https://github.com/nvim-neorg/neorg/commit/ea588bbc2cabe37f90652a8cb49bf8b286498d2a))
* add skeleton for the calendar UI element ([3c99106](https://github.com/nvim-neorg/neorg/commit/3c99106d64792533a3cf10ac6ef20a089e94c1ff))
* **calendar:** add `?` help page for custom input ([211b0ba](https://github.com/nvim-neorg/neorg/commit/211b0ba61b5cf8f4520b5e03f5235f6de87e4417))
* **calendar:** add `$` and `0`/`_` navigation keybinds ([0061928](https://github.com/nvim-neorg/neorg/commit/006192808d436c27f8ceca0fffcc4a238ec402a7))
* **calendar:** add `m`/`M`, `L`/`H` and `y`/`Y` keybinds for the monthly view ([9bf562d](https://github.com/nvim-neorg/neorg/commit/9bf562d4633abac71b749ad7380cfe010a4c3bd7))
* **calendar:** add basic help popup when `?` is invoked ([779d089](https://github.com/nvim-neorg/neorg/commit/779d089e17139acfdd2a4988c34eea892f29a475))
* **calendar:** allow many simultaneous calendars ([f816fe7](https://github.com/nvim-neorg/neorg/commit/f816fe77ef2abecff9e98d8d35ff48a453317cf0))
* **calendar:** generalize functions even further, allow for offsets ([d857c34](https://github.com/nvim-neorg/neorg/commit/d857c34fe7a4645501551f2b66dd7915b9575b4f))
* **calendar:** implement basic `i` functionality ([6713f40](https://github.com/nvim-neorg/neorg/commit/6713f40d5d1f9e7a0e8b80ffdc82d4fff79c16c0))
* **calendar:** render as many months as is possible on screen ([fa23767](https://github.com/nvim-neorg/neorg/commit/fa237674cf75bf2bbc62a438b1606b65cc277ebd))
* **core.ui.calendar:** add day of the month rendering ([8bc3364](https://github.com/nvim-neorg/neorg/commit/8bc3364f306d5df528193a8ca68fa8b4a45701ef))
* **core.ui.calendar:** add static calendar ui ([adbb415](https://github.com/nvim-neorg/neorg/commit/adbb4151677bf22c809f9b6dfd35de5e07da6c7a))
* **core.ui.calendar:** highlight the current day differently ([eada386](https://github.com/nvim-neorg/neorg/commit/eada386cc79c122b648580de50b1f825b74a9627))
* **core.ui.calendar:** implement more of the barebones UI ([364f44a](https://github.com/nvim-neorg/neorg/commit/364f44a7d1179d5aa98d1f4ff6b4b6b1b6078bd3))
* **core.ui.calendar:** make the calendar display full month names ([c6cc059](https://github.com/nvim-neorg/neorg/commit/c6cc059992c812712c9a2bb4075b2d9b31f84f5c))
* **core.ui:** let `create_split` take in a `height` variable ([7dbbe9d](https://github.com/nvim-neorg/neorg/commit/7dbbe9d236596d8990827e717ea892cd98e79b23))
* correctly handle year boundaries ([58b55e1](https://github.com/nvim-neorg/neorg/commit/58b55e16366ecd431bece7ba4d42d512b21b972e))
* implement `render_month` function ([343fb8d](https://github.com/nvim-neorg/neorg/commit/343fb8d02422fe2f2a3c791f2bdba0be95c3c96b))
* place cursor over current day when creating calendar ([3ce268b](https://github.com/nvim-neorg/neorg/commit/3ce268b703d321561b86e546c7633326b39fa494))
* **tempus:** add `to_lua_date` function ([ef62e53](https://github.com/nvim-neorg/neorg/commit/ef62e5308c684468a822684382d14de8f8f63193))


### Bug Fixes

* **calendar:** allow the view to be written to on rerender ([8e247d4](https://github.com/nvim-neorg/neorg/commit/8e247d414bcb0d1123b2b12c7ff29bdf36c50cbd))
* **calendar:** fix incorrect movement with `H` across boundaries of months with different lengths ([48face2](https://github.com/nvim-neorg/neorg/commit/48face25855d7844302b13a125363c30b8a6fe9a))
* **calendar:** fix rest of highlight groups ([ead4c4c](https://github.com/nvim-neorg/neorg/commit/ead4c4c53769839b5063fab71ebb92d155d53676))
* **calendar:** if another calendar is open then close it instead of erroring ([9751e7d](https://github.com/nvim-neorg/neorg/commit/9751e7d62af0b7e49ff788058154b966be205e2e))
* **calendar:** make distance between each month uniform and support modifying the distance between each month ([746354d](https://github.com/nvim-neorg/neorg/commit/746354dea70e9657f61531375329e407e7f5a203))
* **calendar:** make month rendering work again ([164028f](https://github.com/nvim-neorg/neorg/commit/164028fd621e3c5b56603d88d6d5e2ba5db51d42))
* **calendar:** overlapping month names in the calendar view ([709cf78](https://github.com/nvim-neorg/neorg/commit/709cf78410b6ea631192ad004d3f2b83761f9953))
* **calendar:** prevent the buffer from being modifiable after it has been filled ([351e103](https://github.com/nvim-neorg/neorg/commit/351e10326e0e2bb6166e165ddb6598e917e6d25c))
* **calendar:** properly display "today's day" in the calendar view ([74ee71a](https://github.com/nvim-neorg/neorg/commit/74ee71a446662f92afa3cbd49f6c980bdf25ae92))
* **calendar:** reversed namespace names ([77b214c](https://github.com/nvim-neorg/neorg/commit/77b214cef220580cdcf527265a15ef980e7bcaf3))
* **core.ui.calendar:** logic error when parsing virt_text length for `set_logical_extmark` ([d5b29ee](https://github.com/nvim-neorg/neorg/commit/d5b29eea8e09d7bd0add778c6818539719914301))
* **core.ui.calendar:** wrong extmark being queried in month render routine ([46624b9](https://github.com/nvim-neorg/neorg/commit/46624b9a02e0d0e928026a0fd4852c4dd3ca7e0d))

## [4.0.1](https://github.com/nvim-neorg/neorg/compare/v4.0.0...v4.0.1) (2023-05-11)


### Bug Fixes

* **highlights.scm:** free form open/close chars would not be concealed ([5de014e](https://github.com/nvim-neorg/neorg/commit/5de014e7cc3dc6eed0a62854fe8ba58f664d97ea))
* **qol.toc:** display headings with TODO statuses unless the status is "cancelled" ([2e44346](https://github.com/nvim-neorg/neorg/commit/2e44346813310de9afc411e2348cf2be8540f70c))
* stop syntax processing if a buffer is already closed ([#859](https://github.com/nvim-neorg/neorg/issues/859)) ([cc2834a](https://github.com/nvim-neorg/neorg/commit/cc2834ae2beb2d5baa75d15848a94dae022faa2c))

## [4.0.0](https://github.com/nvim-neorg/neorg/compare/v3.2.2...v4.0.0) (2023-05-05)


### ⚠ BREAKING CHANGES

* move all `gt*` keybinds to `<LocalLeader>t*`
* remove `core.news`

### Features

* add basic cheatsheet (viewable via `:h neorg-cheatsheet`) ([d3e37a6](https://github.com/nvim-neorg/neorg/commit/d3e37a681743181a34dcfa7adb6ec61fb5aeb63c))
* **keybinds:** warn when a deprecated keybind is used (will be removed with `5.0`) ([e20d3c3](https://github.com/nvim-neorg/neorg/commit/e20d3c324b091cac29ccd7ec8431d24aa9b792c8))


### Bug Fixes

* **concealer:** buggy debounce logic causing visual artifacts (especially on the first line of a buffer) ([45388fc](https://github.com/nvim-neorg/neorg/commit/45388fc0478e8d1273bd80789e7e1af1df76458f))
* **concealer:** stop concealer if buffer is not loaded ([#836](https://github.com/nvim-neorg/neorg/issues/836)) ([6aa9fd3](https://github.com/nvim-neorg/neorg/commit/6aa9fd303c807ed1ca3fb15cdeab1e322d02fd31))
* **dirman.expand_path:** search for both `$/` and `$\` in links to support windows paths ([#830](https://github.com/nvim-neorg/neorg/issues/830)) ([160d40f](https://github.com/nvim-neorg/neorg/commit/160d40f5261be5149842942adbf260d6e359d9ec))
* **esupports.hop:** anchors to files woul dresult in a "link not found" ([#688](https://github.com/nvim-neorg/neorg/issues/688)) ([3009adf](https://github.com/nvim-neorg/neorg/commit/3009adf2cf48aedcbb309d0765e0fbbb64a0fdf4))
* **keybinds.lua:** remove dead `toc` keybinds ([06666f2](https://github.com/nvim-neorg/neorg/commit/06666f298e146d758d691366ca3465a3bd1e3f7f))


### Code Refactoring

* move all `gt*` keybinds to `&lt;LocalLeader&gt;t*` ([f67110d](https://github.com/nvim-neorg/neorg/commit/f67110d11d37fde09756eb2de8a1814d04a4a03b))
* remove `core.news` ([4086d9f](https://github.com/nvim-neorg/neorg/commit/4086d9f17d823cfe5a13e7b12b30e13b5d3b796d))

## [3.2.2](https://github.com/nvim-neorg/neorg/compare/v3.2.1...v3.2.2) (2023-04-27)


### Bug Fixes

* **core.ui:** clear the `winbar` option in Neorg popups to prevent "not enough room" errors ([fcebf9f](https://github.com/nvim-neorg/neorg/commit/fcebf9f6caf0667f99b1481e2c0a49f0eeb68fe9))
* **esupports.hop:** broken definitions and footnotes ([#733](https://github.com/nvim-neorg/neorg/issues/733)) ([94cf7d2](https://github.com/nvim-neorg/neorg/commit/94cf7d2889b386ce1313e80c8c04adf18872c028))

## [3.2.1](https://github.com/nvim-neorg/neorg/compare/v3.2.0...v3.2.1) (2023-04-27)


### Bug Fixes

* **export:** `gsub` export links that contain `#`, `?`. closes [#807](https://github.com/nvim-neorg/neorg/issues/807) ([#816](https://github.com/nvim-neorg/neorg/issues/816)) ([7f3a3b8](https://github.com/nvim-neorg/neorg/commit/7f3a3b850c8d4b73e7f85971aae2a96162bcb150))
* **export:** markdown export for horizontal_line ([#820](https://github.com/nvim-neorg/neorg/issues/820)) ([2178447](https://github.com/nvim-neorg/neorg/commit/217844796e00a1cea7c051435f9c49bee25e7caa))

## [3.2.0](https://github.com/nvim-neorg/neorg/compare/v3.1.0...v3.2.0) (2023-04-22)


### Features

* add `core.pivot` for toggling list types ([cbf383f](https://github.com/nvim-neorg/neorg/commit/cbf383ff4eca0e23a24d4244af20bed415ed400c))
* **keybinds:** add default keybinds for `core.pivot` ([2f49628](https://github.com/nvim-neorg/neorg/commit/2f496283504dcfb30d9ee60101a8290e743c1753))
* **pivot:** add `core.pivot.invert-list-type` keybind ([2d0446a](https://github.com/nvim-neorg/neorg/commit/2d0446a2d8e3789bbd17bbb3cb97e73befccb327))


### Bug Fixes

* **core.summary:** wrong module name in header, wrong internal command names ([a046900](https://github.com/nvim-neorg/neorg/commit/a0469001430a68f521d3292f8a8252655cfda941))
* **docgen:** installation documentation link for wiki ([ba8b31d](https://github.com/nvim-neorg/neorg/commit/ba8b31dc2491f80b9f65fadbafdfd94d6ef26988)), closes [#548](https://github.com/nvim-neorg/neorg/issues/548)
* **summary:** broken wiki entry ([69fbabf](https://github.com/nvim-neorg/neorg/commit/69fbabfb5764cd164453a764174cf5cfa813ae60))

## [3.1.0](https://github.com/nvim-neorg/neorg/compare/v3.0.0...v3.1.0) (2023-04-19)


### Features

* warn access to `core.norg` modules instead of breaking ([ed761a5](https://github.com/nvim-neorg/neorg/commit/ed761a5c5a9100861034b31978049401444fd6fb))

## [3.0.0](https://github.com/nvim-neorg/neorg/compare/v2.0.1...v3.0.0) (2023-04-19)


### ⚠ BREAKING CHANGES

* move all `core.norg.*` modules into `core.*`
* **Makefile:** remove `install_pre_commit` target
* move `core.norg.dirman.summary` -> `core.summary`
* **summary:** refactor of the `core.norg.dirman.summary` module
* **docgen:** wipe whole wiki on every reparse

### Features

* add `dirman.summary` module ([#750](https://github.com/nvim-neorg/neorg/issues/750)) ([93c40f2](https://github.com/nvim-neorg/neorg/commit/93c40f2e38a0770e9ce95787c8363320344a87c3))
* add `Home.md` generation capability ([6bdf557](https://github.com/nvim-neorg/neorg/commit/6bdf557ece33850f9733dddc343369d743a51564))
* **ci:** add `version_in_code.yml` workflow ([5746245](https://github.com/nvim-neorg/neorg/commit/5746245756bac83fcf02338c93bc87f6089e2bf3))
* cleanup, add document comments to all modules, add more error checks ([81284c1](https://github.com/nvim-neorg/neorg/commit/81284c1e2f6e441f6532678b76ff5378396dda2c))
* **config.lua:** add `norg_version`, bump `version` to `3.0.0` ([8d76723](https://github.com/nvim-neorg/neorg/commit/8d767232a571513a3ab8c5c14ddc6f26d09aa98a))
* **core.integrations.treesitter:** Return all same attributes of a tag ([bedf13d](https://github.com/nvim-neorg/neorg/commit/bedf13dbcef63099a52dd4f160d90c46fc1de440))
* **dirman:** add new `use_popup` option for `dirman` ([#743](https://github.com/nvim-neorg/neorg/issues/743)) ([6350254](https://github.com/nvim-neorg/neorg/commit/63502544afde1c15d79ce097ad1928314cb8c7cd))
* **docgen:** add `module` page generator ([17496a8](https://github.com/nvim-neorg/neorg/commit/17496a8e975f1bd9d896d7cc78a6e61d1a131245))
* **docgen:** add basic rendering skeleton logic ([215719e](https://github.com/nvim-neorg/neorg/commit/215719ece560400592c2fef2ed75ab57430baf9b))
* **docgen:** add comment integrity checking logic ([799886f](https://github.com/nvim-neorg/neorg/commit/799886f7ba5a072a453d5a90708686109ce4fa21))
* **docgen:** allow strings as table keys ([4adf04e](https://github.com/nvim-neorg/neorg/commit/4adf04e05d98b6bcb6a3aac4cab60d64fd0d86f9))
* **docgen:** auto-open &lt;details&gt; tags that contain tables or lists ([1f2e0dc](https://github.com/nvim-neorg/neorg/commit/1f2e0dc23f6944bad660553ad4550847cf68e096))
* **docgen:** differentiate between lists and tables ([c0062e5](https://github.com/nvim-neorg/neorg/commit/c0062e5a75226f063b59eb5ee8250cb4da6ea202))
* **docgen:** differentiate empty and nonempty tables/lists ([0ab1a8d](https://github.com/nvim-neorg/neorg/commit/0ab1a8d469667d6b763e299c390a3e9bc7ea1a13))
* **docgen:** implement `Required By` field ([7033c4b](https://github.com/nvim-neorg/neorg/commit/7033c4bd2dc4633d0874b2da05b0ae67928b1117))
* **docgen:** implement `Required By` section ([15bf71b](https://github.com/nvim-neorg/neorg/commit/15bf71b15e07917e0f3a55de44e79fcdfbfc557d))
* **docgen:** implement configuration_options parsing logic ([b34658a](https://github.com/nvim-neorg/neorg/commit/b34658a21602fdd286889c2e57bf2d68d63d4472))
* **docgen:** implement function rendering, fix incorrect interpretation of function calls ([a023488](https://github.com/nvim-neorg/neorg/commit/a023488944473dfcd611308d5e21b7a9b2d7690d))
* **docgen:** implement table rendering ([9074328](https://github.com/nvim-neorg/neorg/commit/907432885e40a16f064d4406cd45efeb895f0962))
* **docgen:** indent nested table keys ([9cf679a](https://github.com/nvim-neorg/neorg/commit/9cf679a24f3bb9db145ae4dfbeb43878a49839e3))
* **docgen:** massive structure changes, implement proper table rendering ([42b8728](https://github.com/nvim-neorg/neorg/commit/42b8728f291072b9d8a11bdf9c7e205ef15fb94d))
* **docgen:** parse config tables ([93c41e1](https://github.com/nvim-neorg/neorg/commit/93c41e1f0aa290d0ad2e2590753312c71a782395))
* **docgen:** perform `[@module](https://github.com/module)` lookups, pasre complex data structures like tables ([19f2381](https://github.com/nvim-neorg/neorg/commit/19f23811ba0366fe3ec9423d26aec33d9d34fcc2))
* **docgen:** properly implement recursive table scanning ([33e06b8](https://github.com/nvim-neorg/neorg/commit/33e06b8d0fc2e7a9b386fc95e6bce4dfb714e56f))
* **docgen:** sort entries when rendering ([b420e70](https://github.com/nvim-neorg/neorg/commit/b420e70532766475bce0bf1d34129e711a31e21a))
* **docgen:** start generating true module pages ([5115d5c](https://github.com/nvim-neorg/neorg/commit/5115d5cd4bd1fefb11f82cb3e3da18b74d4e9b9e))
* **helpers/lib:** add `read_files` and `title` functions ([d59f41b](https://github.com/nvim-neorg/neorg/commit/d59f41b78755b102a41d172d4e3f64d59cb86b8b))
* **helpers:** add `ensure_nested` function ([2c4e8d0](https://github.com/nvim-neorg/neorg/commit/2c4e8d02feb7f1e6878307e7813a9f13ec000a73))
* **helpers:** Add wrapper to vim.notify ([#778](https://github.com/nvim-neorg/neorg/issues/778)) ([c278f6f](https://github.com/nvim-neorg/neorg/commit/c278f6f895c6b2f9ef4fc217ed867675108d804e))
* implement _Sidebar generation ([733b74c](https://github.com/nvim-neorg/neorg/commit/733b74c92481bc955f1f46594e50fb4931ab3cf5))
* implement necessary APIs for complex data structure parsing ([b78f01c](https://github.com/nvim-neorg/neorg/commit/b78f01cd951b8ecfe7e842d31f609e6e4d5ac9db))
* implement new docgen featuring top-comment validation ([b77fbd5](https://github.com/nvim-neorg/neorg/commit/b77fbd52f96db049687901ac1f0a8aea7ab4bdfa))
* **indent:** adapt indentation of nestable detached modifiers when a detached modifier extension is found ([56e59da](https://github.com/nvim-neorg/neorg/commit/56e59daff56ba7f4d76b11ff3fc6dd70c4b54524))
* **makefile:** add `local-documentation` option ([ed20f79](https://github.com/nvim-neorg/neorg/commit/ed20f796f5bb337d230f5d33a3f6ba420a8d30a4))
* **qol.todo_items:** add new `create_todo_items` option ([d810aa4](https://github.com/nvim-neorg/neorg/commit/d810aa43c96301db35af351306eab54e35071d57))
* **qol.todo_items:** add new `create_todo_parents` option (false by default) ([6b6ef04](https://github.com/nvim-neorg/neorg/commit/6b6ef04e5fb0a5b1c3ff59699a9371afd659d9ff))
* **qol.todo_items:** when only done and uncertain items are present in ([1d6b0b0](https://github.com/nvim-neorg/neorg/commit/1d6b0b056b097e9f4bacf8877c49fdacbc445b2c))
* strip leading `--` from comments ([ecea630](https://github.com/nvim-neorg/neorg/commit/ecea6305a82007b6c8c509fd594f8b52c3331021))
* **summary:** implement `metadata` strategy and reimplement summary generation code ([f948288](https://github.com/nvim-neorg/neorg/commit/f9482881315d49d0a35206c7936a7f48c20dfcbf))
* **toc:** add `close_after_use` configuration option ([#785](https://github.com/nvim-neorg/neorg/issues/785)) ([e5d7fbb](https://github.com/nvim-neorg/neorg/commit/e5d7fbb0291e658f78545c29318c9162cf505d15))


### Bug Fixes

* `:Neorg journal today` would fail on alternative path separators ([#749](https://github.com/nvim-neorg/neorg/issues/749)) ([e7a5054](https://github.com/nvim-neorg/neorg/commit/e7a50542ad9921a8c7d652eeca6a9006cc024b79))
* **base.lua:** don't assign the `extension` flag to parent modules, only to the imports themselves ([fa5f561](https://github.com/nvim-neorg/neorg/commit/fa5f56163510eb00a0d75bec81d40d901c175d3b))
* **clipboard.code-blocks:** don't cut off characters from non-visual-line selection ([744ae49](https://github.com/nvim-neorg/neorg/commit/744ae49fe5fab9e54de96282778a202f85a2f37b))
* **code.looking-glass:** Use last attribute as start row of looking-glass (fix [#777](https://github.com/nvim-neorg/neorg/issues/777)) ([beef6fd](https://github.com/nvim-neorg/neorg/commit/beef6fd9420d6a798ddd796779b96f006b14ca12))
* **commands.return:** don't override the workspace to `default` after running `:Neorg return` ([169c7be](https://github.com/nvim-neorg/neorg/commit/169c7bee8a5f101c63c3a473a577dce079f7ddec))
* **concealer:** whenever running any scheduled command ensure that the buffer exists first ([b926416](https://github.com/nvim-neorg/neorg/commit/b9264161d0ef10ee61ace6ebeb0a55ca461b638a))
* **core.clipboard.code-blocks:** module would not work past version `1.0.0` ([ac88283](https://github.com/nvim-neorg/neorg/commit/ac8828369cb2a4b2e1e17e6b495645585ed2a37b))
* **core.clipboard.code-blocks:** visual selection would cut off one character too little ([87ed4bf](https://github.com/nvim-neorg/neorg/commit/87ed4bfde4a00a4cf4279298de02280bf11c7a74))
* **core.export.markdown:** Update markdown exporter for new todo syntax (fix [#757](https://github.com/nvim-neorg/neorg/issues/757)) ([336416f](https://github.com/nvim-neorg/neorg/commit/336416f6c41777a4025cc80b8a085e21e758931f))
* **core.itero:** preserve indentation on continued items ([92c31c4](https://github.com/nvim-neorg/neorg/commit/92c31c491caedd7d1a82b42d4ba6c2227c05d930))
* **core.norg.esupports.hop:** Make hop on anchors work again ([#756](https://github.com/nvim-neorg/neorg/issues/756)) ([d38a229](https://github.com/nvim-neorg/neorg/commit/d38a22940aaa55351cd4dc106540fa302fad4f0d))
* **core.norg.journal:** fixes [#736](https://github.com/nvim-neorg/neorg/issues/736) , now generates TOC correctly ([19c5558](https://github.com/nvim-neorg/neorg/commit/19c555836bc31f482e0ea42f08d150110754644f))
* **core.promo:** don't error when the concealer is not loaded ([#767](https://github.com/nvim-neorg/neorg/issues/767)) ([3e09f69](https://github.com/nvim-neorg/neorg/commit/3e09f698b8a4151f2b4f77ee917e4b54388bc97a))
* **dirman:** automatically create the index file if it exists when running `:Neorg index` ([7ce2db5](https://github.com/nvim-neorg/neorg/commit/7ce2db5d2eeec37b4a4c4bc43009c4741c3755da))
* **dirman:** corrected win width and height calculation ([9766bef](https://github.com/nvim-neorg/neorg/commit/9766bef893ec993af9408ea0d44a8f13adbd1e80))
* **dirman:** don't create `index.norg` files in the default workspace when running `:Neorg index` ([c60747f](https://github.com/nvim-neorg/neorg/commit/c60747fcc567d7eb50b16c2007bcfd3a81a934d1))
* **docgen:** `&lt;h6&gt;` tags not being rendered properly ([d0a0da0](https://github.com/nvim-neorg/neorg/commit/d0a0da017135b48c5f4a325bfaedbcdf1ca79fe3))
* **docgen:** could not find module `neorg` ([b68a945](https://github.com/nvim-neorg/neorg/commit/b68a945d6b1a8c2f8c57e0c366f224a162f391e3))
* **docgen:** display listed modules in alphabetical order ([264b451](https://github.com/nvim-neorg/neorg/commit/264b451d74d3e4bc3f856d087070b9dac46f8e90))
* **docgen:** don't double-render numeric values ([35df191](https://github.com/nvim-neorg/neorg/commit/35df1918de321617972f10edd88d9c32cc8102a2))
* **docgen:** don't render description tags if no description is present ([64dc28d](https://github.com/nvim-neorg/neorg/commit/64dc28deea9a7f9c52c3ba5343f1ce3c754a566e))
* **docgen:** don't unnecessarily copy parsers ([46e7936](https://github.com/nvim-neorg/neorg/commit/46e79366775136592540fbe5f0532c001012daa5))
* **docgen:** incorrect wiki paths ([2dbead6](https://github.com/nvim-neorg/neorg/commit/2dbead687053610147161ecda1a908070720731f))
* **docgen:** internal modules that were part of `core.defaults` would not be displayed in the developer modules section ([c3099eb](https://github.com/nvim-neorg/neorg/commit/c3099ebd595d3ec491613c297f4199e316f85853))
* **docgen:** list items with no summary would break rendering ([b69ea57](https://github.com/nvim-neorg/neorg/commit/b69ea57029a2c62e72ea86c93d295102059c58ab))
* **docgen:** lists within lists would never be rendered ([06894bb](https://github.com/nvim-neorg/neorg/commit/06894bb090ad6deb52ba7b19f7e13bbb41385a63))
* **docgen:** make the spacing nicer to look at ([426ca24](https://github.com/nvim-neorg/neorg/commit/426ca246e310a212cef5f6bba367d7ebc84bf70b))
* **docgen:** remove debug log ([8ffcaed](https://github.com/nvim-neorg/neorg/commit/8ffcaed1095743b8474a16f25855b809cf4fe65d))
* **docgen:** this should work now i think (after 20 tries) ([72d3d49](https://github.com/nvim-neorg/neorg/commit/72d3d4981d85fd1114d3185e40cc135a7892a4a4))
* **docgen:** use minimal_init.vim instead of custom_init.vim ([a7cb7ab](https://github.com/nvim-neorg/neorg/commit/a7cb7ab443c24fbd1d9f696abddd91c16f05d842))
* **docgen:** wrong `require` order in `docgen.lua` ([7494b51](https://github.com/nvim-neorg/neorg/commit/7494b51a61cc31371514cb7b2e1ccdf4cef164e2))
* finalize `version_in_code.yml` CI (it works yay) ([db9ed0b](https://github.com/nvim-neorg/neorg/commit/db9ed0b98ba30e2b783ea9da0fddda4cf6b2a47e))
* **metagen:** use `norg_version` ([a5c2553](https://github.com/nvim-neorg/neorg/commit/a5c25531de2790133310ad874fcbbb976d082c78))
* neovim 0.9 vim.treesitter.parse_query deprecation ([#784](https://github.com/nvim-neorg/neorg/issues/784)) ([f4a9759](https://github.com/nvim-neorg/neorg/commit/f4a9759e53fadaece9d93118a0471ddffd05d394))
* **qol.todo_item:** `&lt;C-space&gt;` would not create a new TODO item with ([fc45beb](https://github.com/nvim-neorg/neorg/commit/fc45bebde0fc9811ca4e770e2ba29c791035c885))
* **qol.todo_items:** `&lt;C-space&gt;` would not respect the `create_todo_items` option ([e764b92](https://github.com/nvim-neorg/neorg/commit/e764b92065ddd6bc206aaefd92837be8d0bd8419))
* **qol.todo_items:** TODO attributes would be erroneously assigned multiple times ([1303097](https://github.com/nvim-neorg/neorg/commit/13030974acee5a49dd02c51bedeac104b4f33cb7))
* **summary:** appropriately indent nested entries ([b725a58](https://github.com/nvim-neorg/neorg/commit/b725a58f25525efc1c39a13a09e6cec0c1c0ba4d))
* **version_in_code.yml:** perform checkout in the current directory ([3d7ad5a](https://github.com/nvim-neorg/neorg/commit/3d7ad5aa4b1277ea0f3ebb93ea79179eda5f6e27))
* **version_in_code.yml:** use `fetch-depth` of `0` ([2e8fa52](https://github.com/nvim-neorg/neorg/commit/2e8fa524d2cc73002378875970048d70ae70cc0b))


### Performance Improvements

* **concealer:** don't rerender the whole file on every single BufEnter ([7419cbb](https://github.com/nvim-neorg/neorg/commit/7419cbb7262200dd94df9d398ee1e7f5b9503a50))


### Miscellaneous Chores

* **docgen:** wipe whole wiki on every reparse ([09cb3e6](https://github.com/nvim-neorg/neorg/commit/09cb3e62022ff0f93965800a728ed698db540240))


### ref

* **Makefile:** remove `install_pre_commit` target ([9a497f5](https://github.com/nvim-neorg/neorg/commit/9a497f5e8195e5b974d520f937a946cb8819f320))
* move `core.norg.dirman.summary` -&gt; `core.summary` ([254b6a6](https://github.com/nvim-neorg/neorg/commit/254b6a60b6c9f845400d2bcb0728ee7f38823781))
* **summary:** refactor of the `core.norg.dirman.summary` module ([a2fe3ee](https://github.com/nvim-neorg/neorg/commit/a2fe3eea24c628fa15b7f854cef6c7acaf9ec3f9))


### Code Refactoring

* move all `core.norg.*` modules into `core.*` ([a5824ed](https://github.com/nvim-neorg/neorg/commit/a5824edf6893b8602e560ed7675c0d4174e263e4))

## [2.0.1](https://github.com/nvim-neorg/neorg/compare/v2.0.0...v2.0.1) (2023-02-02)


### Bug Fixes

* completion for TODO items ([#711](https://github.com/nvim-neorg/neorg/issues/711)) ([9184027](https://github.com/nvim-neorg/neorg/commit/91840274112f1286ff5f4063ac6f515683b6dc67))
* **core.norg.journal:** add proper error handling for `vim.loop.fs_scandir` ([4a9a5fe](https://github.com/nvim-neorg/neorg/commit/4a9a5fe13cd454692fc4db0b27783cd005e6be56))
* **treesitter:** don't constantly log errors about erroneous document syntax trees ([9f8b0a1](https://github.com/nvim-neorg/neorg/commit/9f8b0a1759d883fae901579ea83b3ffbfc81a53b))

## [2.0.0](https://github.com/nvim-neorg/neorg/compare/v1.1.1...v2.0.0) (2023-01-06)


### ⚠ BREAKING CHANGES

* **core.norg.qol.toc:** rewrite the table of contents implementation

### Features

* **core.export:** add `NeorgExportComplete` user autocommand ([8b10e61](https://github.com/nvim-neorg/neorg/commit/8b10e61d2f2c5e626849f9a6f8cb4399c28a1a47))
* **core.norg.qol.toc:** add multiple buffer handling logic ([467e311](https://github.com/nvim-neorg/neorg/commit/467e3113c32b8b9f1950a9425aa7b74c13cd88b8))
* **core.norg.qol.toc:** implement `qflist` generation option ([77c5149](https://github.com/nvim-neorg/neorg/commit/77c514970a9d4648b05b2334a060263666f588e2))
* **treesitter:** add `execute_query` function ([310ebaa](https://github.com/nvim-neorg/neorg/commit/310ebaaef538dfd41d02a2903663be05fd38834b))


### Bug Fixes

* **core.ui:** do not modify the user's `scrolloffset` ([bd2e58c](https://github.com/nvim-neorg/neorg/commit/bd2e58cf6f9d42527aa2b692fb187eafa82bd91e))


### Performance Improvements

* further optimize `toc` infirm tag grabber ([5e8d059](https://github.com/nvim-neorg/neorg/commit/5e8d05968e04f7945576d50a6b1576cc722f96fc))
* optimize the `toc` infirm tag grabber code ([a41bd4a](https://github.com/nvim-neorg/neorg/commit/a41bd4a92afefb7e2630b821b59f7707a054baac))


### ref

* **core.norg.qol.toc:** rewrite the table of contents implementation ([c0104fb](https://github.com/nvim-neorg/neorg/commit/c0104fb9faed3b3213e4e275a55a522a299a2d0e))

## [1.1.1](https://github.com/nvim-neorg/neorg/compare/v1.1.0...v1.1.1) (2023-01-05)


### Bug Fixes

* **core.export:** incorrect exporting of code blocks with no parameters ([#701](https://github.com/nvim-neorg/neorg/issues/701)) ([0922815](https://github.com/nvim-neorg/neorg/commit/0922815837a374bd0b2a3cf0477b54e6668e133d))

## [1.1.0](https://github.com/nvim-neorg/neorg/compare/v1.0.1...v1.1.0) (2023-01-05)


### Features

* keep checkboxes with `core.itero` ([#663](https://github.com/nvim-neorg/neorg/issues/663)) ([00532bd](https://github.com/nvim-neorg/neorg/commit/00532bd997d2aef0384ed8f11500d33d229a7e53))


### Bug Fixes

* **core.export.markdown:** incorrectly exported code blocks ([dd2750c](https://github.com/nvim-neorg/neorg/commit/dd2750c0e4d847b67a6ead79ff5043e671cac8bd))
* **folds:** correctly fold document metadata ([adc000a](https://github.com/nvim-neorg/neorg/commit/adc000aadd41e68e4de8a2d1bb90b2e910ffef1b))

## [1.0.1](https://github.com/nvim-neorg/neorg/compare/1.0.0...v1.0.1) (2022-12-23)


### Bug Fixes

* **core.looking-glass:** buffer being closed for no reason after leaving buffer ([828a37f](https://github.com/nvim-neorg/neorg/commit/828a37fe1f008dbfd70cd7fc0f7ba9d0bc75da2a))
* do not run tests for nightly/neorg-main, as GTD is no longer existent ([37f1f9a](https://github.com/nvim-neorg/neorg/commit/37f1f9a44ba65603b5992fc36761c61d921fab78))
