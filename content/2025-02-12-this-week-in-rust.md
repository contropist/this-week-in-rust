Title: This Week in Rust 586
Number: 586
Date: 2025-02-12
Category: This Week in Rust

Hello and welcome to another issue of *This Week in Rust*!
[Rust](https://www.rust-lang.org/) is a programming language empowering everyone to build reliable and efficient software.
This is a weekly summary of its progress and community.
Want something mentioned? Tag us at [@ThisWeekInRust](https://x.com/ThisWeekInRust) on X (formerly Twitter) or [@ThisWeekinRust](https://mastodon.social/@thisweekinrust) on mastodon.social, or [send us a pull request](https://github.com/rust-lang/this-week-in-rust).
Want to get involved? [We love contributions](https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md).

*This Week in Rust* is openly developed [on GitHub](https://github.com/rust-lang/this-week-in-rust) and archives can be viewed at [this-week-in-rust.org](https://this-week-in-rust.org/).
If you find any errors in this week's issue, [please submit a PR](https://github.com/rust-lang/this-week-in-rust/pulls).

Want TWIR in your inbox? [Subscribe here](https://this-week-in-rust.us11.list-manage.com/subscribe?u=fd84c1c757e02889a9b08d289&id=0ed8b72485).

## Updates from Rust Community

<!--

Dear community contributors:
Please read README.md for guidance on submissions.
Each submitted link should be of the form:

* [Title of the Linked Page](https://example.com/my_article)

If you don't know which category to use, feel free to submit a PR anyway
and just ask the editors to select the category.

-->

### Official
* [crates.io: development update](https://blog.rust-lang.org/2025/02/05/crates-io-development-update.html)

### Foundation
* [Nell Shamrell-Harrington Elected as Rust Foundation Board of Directors Chair](https://rustfoundation.org/media/nell-shamrell-harrington-elected-as-rust-foundation-board-of-directors-chair/)

### Newsletters
* [This Month in Rust OSDev: January 2025](https://rust-osdev.com/this-month/2025-01/)

### Project/Tooling Updates
* [Fyrox Game Engine 0.36](https://fyrox.rs/blog/post/fyrox-game-engine-0-36/)
* [Refined: simple refinement types for Rust](https://jordankaye.dev/posts/refined/)
* [Maintainer opinions on Rust-for-Linux](https://lwn.net/SubscriberLink/1007921/9020dbb12585d48f/)
* [Rewriting essential Linux packages in Rust](https://lwn.net/SubscriberLink/1007907/a9db87fc233bceae/)
* [Nutype 0.6.0 - newtype with guarantees supports const functions now](https://github.com/greyblake/nutype/releases/tag/v0.6.0)
* [Glues v0.6.0 – TUI Note-Taking App with a major design refresh](https://github.com/gluesql/glues/releases/tag/v0.6.0)
* [Gladius 0.2 released - a GPLv3, command line, multicursor code editor with LSP support](https://codeberg.org/njskalski/bernardo/src/branch/master/docs/beta_release_notes/beta_1_release.md)

### Observations/Thoughts
* [A survey of every iterator variant](https://blog.yoshuawuyts.com/a-survey-of-every-iterator-variant)
* [Updating a large codebase to Rust 2024](https://codeandbitters.com/rust-2024-upgrade/)
* [How I learned to stop worrying and love the LLM](https://smallcultfollowing.com/babysteps/blog/2025/02/10/love-the-llm/)
* [The Three Basic Rules of Safety Hygiene](https://jack.wrenn.fyi/blog/safety-hygiene/)
* [video] [Bevy Meetup#1 - Alice - What the f*** is reflection?](https://www.youtube.com/watch?v=vxPKWb0dSqQ)
* [video] [The case for sans-io](https://www.youtube.com/watch?v=RYHYiXMJdZI)

### Rust Walkthroughs
* [First Steps in Game Development With Rust and Bevy](https://blog.jetbrains.com/rust/2025/02/04/first-steps-in-game-development-with-rust-and-bevy/)
* [Provisioning TLS Certificates in Rust With ACME](https://www.shuttle.dev/blog/2025/02/06/provisioning-tls-certificates-with-acme-in-rust)
* [Tip of the day #4: Type annotations on Rust match patterns](https://gaultier.github.io/blog/tip_of_the_day_4.html)
* [From hours to 360ms: over-engineering a puzzle solution](https://blog.danielh.cc/blog/puzzle)
* [Writing a Simple Driver in Rust](https://scorpiosoftware.net/2025/02/08/writing-a-simple-driver-in-rust/)
* [Solving the ABA Problem in Rust with Tagged Pointers](https://minikin.me/blog/solving-the-aba-problem-in-rust-tagged-pointers)
* [Mix in Rust with Java (or Kotlin!)](https://tweedegolf.nl/en/blog/147/mix-in-rust-with-java-or-kotlin)
* [How to write DRY code in Rust](https://baarse.substack.com/p/how-to-write-dry-code-in-rust)

### FOSDEM
* [Rust for Linux](https://fosdem.org/2025/schedule/event/fosdem-2025-6507-rust-for-linux/)
* [Rewriting the future of the Linux essential packages in Rust ?](https://fosdem.org/2025/schedule/event/fosdem-2025-6196-rewriting-the-future-of-the-linux-essential-packages-in-rust-/)
* [Writing a kubernetes controller… But in Rust](https://fosdem.org/2025/schedule/event/fosdem-2025-4189-writing-a-kubernetes-controller-but-in-rust/)
* [Using embedded Rust to build an unattended, battery-powered device](https://fosdem.org/2025/schedule/event/fosdem-2025-6300-using-embedded-rust-to-build-an-unattended-battery-powered-device/)
* [Augurs: a time series toolkit for Rust](https://fosdem.org/2025/schedule/event/fosdem-2025-4668-augurs-a-time-series-toolkit-for-rust/)
* [Building a watt-meter esp-rs and a rocket backend](https://fosdem.org/2025/schedule/event/fosdem-2025-5470-building-a-watt-meter-esp-rs-and-a-rocket-backend/)
* [Huge graph analysis on your own server with WebGraph in Rust](https://fosdem.org/2025/schedule/event/fosdem-2025-4773-huge-graph-analysis-on-your-own-server-with-webgraph-in-rust/)
* [Bringing terminal aesthetics to the Web with Rust (and vice versa)](https://fosdem.org/2025/schedule/event/fosdem-2025-5496-bringing-terminal-aesthetics-to-the-web-with-rust-and-vice-versa-/)
* [Abusing reborrowing for fun, profit, and a safepoint garbage collector](https://fosdem.org/2025/schedule/event/fosdem-2025-4394-abusing-reborrowing-for-fun-profit-and-a-safepoint-garbage-collector/)
* [Lessons from rewriting systems software in Rust](https://fosdem.org/2025/schedule/event/fosdem-2025-5088-lessons-from-rewriting-systems-software-in-rust/)
* [Rust-ifying the Linux kernel scheduler (in user space)](https://fosdem.org/2025/schedule/event/fosdem-2025-4620-rust-ifying-the-linux-kernel-scheduler-in-user-space-/)
* [Adventures in oxidizing Arch Linux Package Management](https://fosdem.org/2025/schedule/event/fosdem-2025-6259-adventures-in-oxidizing-arch-linux-package-management/)
* [Modeling Inheritance in SeaORM](https://www.sea-ql.org/blog/2025-01-08-sea-orm-inheritance/)

### Miscellaneous
* [January 2025 Rust Jobs Report](https://filtra.io/rust/jobs-report/jan-25)

## Crate of the Week

This week's crate is [esp32-mender-client](https://github.com/virust-ai/esp32-mender-client), a client for ESP32 to execute firmware updates and remote commands.

Thanks to [Kelvin](https://users.rust-lang.org/t/crate-of-the-week/2704/1399) for the self-suggestion!

[Please submit your suggestions and votes for next week][submit_crate]!

[submit_crate]: https://users.rust-lang.org/t/crate-of-the-week/2704

## Calls for Testing
An important step for RFC implementation is for people to experiment with the
implementation and give feedback, especially before stabilization.  The following
RFCs would benefit from user testing before moving forward:

### [RFCs](https://github.com/rust-lang/rfcs/issues?q=label%3Acall-for-testing)
* *No calls for testing were issued this week.*

### [Rust](https://github.com/rust-lang/rust/labels/call-for-testing)
* *No calls for testing were issued this week.*

### [Rustup](https://github.com/rust-lang/rustup/labels/call-for-testing)
* *No calls for testing were issued this week.*

If you are a feature implementer and would like your RFC to appear on the above list, add the new `call-for-testing`
label to your RFC along with a comment providing testing instructions and/or guidance on which aspect(s) of the feature
need testing.

## Call for Participation; projects and speakers

### CFP - Projects

Always wanted to contribute to open-source projects but did not know where to start?
Every week we highlight some tasks from the Rust community for you to pick and get started!

Some of these tasks may also have mentors available, visit the task page for more information.

*No Calls for participation were submitted this week.*

If you are a Rust project owner and are looking for contributors, please submit tasks [here][guidelines] or through a [PR to TWiR](https://github.com/rust-lang/this-week-in-rust) or by reaching out on [X (formerly Twitter)](https://x.com/ThisWeekInRust) or [Mastodon](https://mastodon.social/@thisweekinrust)!

[guidelines]:https://github.com/rust-lang/this-week-in-rust?tab=readme-ov-file#call-for-participation-guidelines

### CFP - Events

Are you a new or experienced speaker looking for a place to share something cool? This section highlights events that are being planned and are accepting submissions to join their event as a speaker.

*No Calls for papers or presentations were submitted this week.*

If you are an event organizer hoping to expand the reach of your event, please submit a link to the website through a [PR to TWiR](https://github.com/rust-lang/this-week-in-rust) or by reaching out on [X (formerly Twitter)](https://x.com/ThisWeekInRust) or [Mastodon](https://mastodon.social/@thisweekinrust)!

## Updates from the Rust Project

462 pull requests were [merged in the last week][merged]

[merged]: https://github.com/search?q=is%3Apr+org%3Arust-lang+is%3Amerged+merged%3A2025-02-04..2025-02-11

* [add amdgpu target](https://github.com/rust-lang/rust/pull/134740)
* [`#[contracts::requires(...)]` + `#[contracts::ensures(...)]`](https://github.com/rust-lang/rust/pull/128045)
* [`rustc_middle`: parallel: TyCtxt: remove "unsafe impl DynSend/DynSync"](https://github.com/rust-lang/rust/pull/136731)
* [add note about `FnPtr` trait being exposed as public bound](https://github.com/rust-lang/rust/pull/136518)
* [allow using named consts in pattern types](https://github.com/rust-lang/rust/pull/136284)
* [always compute coroutine layout for eagerly emitting recursive layout errors](https://github.com/rust-lang/rust/pull/136073)
* [avoid calling the `layout_of` query in `lit_to_const`](https://github.com/rust-lang/rust/pull/136302)
* [avoid using `make_direct_deprecated()` in extern "ptx-kernel"](https://github.com/rust-lang/rust/pull/133932)
* [check Sizedness of return type in WF](https://github.com/rust-lang/rust/pull/136274)
* [compiler: gate `extern "{abi}"` in `ast_lowering`](https://github.com/rust-lang/rust/pull/136603)
* [couple of changes to run rustc in miri](https://github.com/rust-lang/rust/pull/136580)
* [coverage: defer part of counter-creation until codegen](https://github.com/rust-lang/rust/pull/136053)
* [debuginfo for function ZSTs should have alignment of 8 bits, not 1 bit](https://github.com/rust-lang/rust/pull/136640)
* [detect (non-raw) borrows of null ZST pointers in CheckNull](https://github.com/rust-lang/rust/pull/136601)
* [disallow `repr()` on invalid items](https://github.com/rust-lang/rust/pull/133925)
* [display of integers without raw pointers and without `overflowing_literals`](https://github.com/rust-lang/rust/pull/135265)
* [don't reset cast kind without also updating the operand in `simplify_cast` in GVN](https://github.com/rust-lang/rust/pull/136450)
* [emit an error if `-Zdwarf-version=1` is requested](https://github.com/rust-lang/rust/pull/136746)
* [ensure that we never try to monomorphize the upcasting or vtable calls of impossible dyn types](https://github.com/rust-lang/rust/pull/136311)
* [fix `rustc_hidden_type_of_opaques` for RPITITs with no default body](https://github.com/rust-lang/rust/pull/136550)
* [fix `unreachable_pub` lint for hermit target](https://github.com/rust-lang/rust/pull/136595)
* [fix accidentally not emitting overflowing literals lints anymore in patterns](https://github.com/rust-lang/rust/pull/136393)
* [fix suggestion for `dependency_on_unit_never_type_fallback` involving closures + format args expansions](https://github.com/rust-lang/rust/pull/136598)
* [fix tail call checks wrt `#[track_caller]`](https://github.com/rust-lang/rust/pull/135973)
* [fix unwrap error in overflowing int literal](https://github.com/rust-lang/rust/pull/136760)
* [fuchsia: allow Rust to use a number of libc filesystem calls](https://github.com/rust-lang/rust/pull/136213)
* [generate correct terminate block under Wasm EH](https://github.com/rust-lang/rust/pull/136200)
* [introduce CoercePointeeValidated for coherence checks at typeck stage](https://github.com/rust-lang/rust/pull/136107)
* [label mismatched parameters at the def site for foreign functions](https://github.com/rust-lang/rust/pull/136651)
* [make `AsyncFnOnce`, `AsyncFnMut`, `AsyncFn` non-`#[fundamental]`](https://github.com/rust-lang/rust/pull/136724)
* [make `cenum_impl_drop_cast` a hard error](https://github.com/rust-lang/rust/pull/135964)
* [make sure to use `Receiver` trait when extracting object method candidate](https://github.com/rust-lang/rust/pull/135179)
* [only highlight unmatchable parameters at the definition site](https://github.com/rust-lang/rust/pull/136583)
* [pass spans around new solver](https://github.com/rust-lang/rust/pull/136269)
* [pattern Migration 2024: try to suggest eliding redundant binding modifiers](https://github.com/rust-lang/rust/pull/136577)
* [pick the max DWARF version when LTO'ing modules with different versions](https://github.com/rust-lang/rust/pull/136659)
* [ping me for attribute-related changes](https://github.com/rust-lang/rust/pull/136643)
* [reject negative literals for unsigned or char types in pattern ranges and literals](https://github.com/rust-lang/rust/pull/136304)
* [removed dependency on the field-offset crate, alternate approach](https://github.com/rust-lang/rust/pull/136201)
* [report generic mismatches when calling bodyless trait functions](https://github.com/rust-lang/rust/pull/136497)
* [resolve `llvm-config` path properly on cross builds](https://github.com/rust-lang/rust/pull/136681)
* [show diff suggestion format on verbose replacement](https://github.com/rust-lang/rust/pull/127541)
* [some `rustc_middle` cleanups](https://github.com/rust-lang/rust/pull/136465)
* [some miscellaneous edition-related library tweaks](https://github.com/rust-lang/rust/pull/136705)
* [transmutability: fix ICE when passing wrong ADT to ASSUME](https://github.com/rust-lang/rust/pull/136730)
* [uefi: process: add support for command environment variables](https://github.com/rust-lang/rust/pull/136418)
* [upgrade elsa to the newest version](https://github.com/rust-lang/rust/pull/136094)
* [use +secure-plt for powerpc-unknown-linux-gnu{,spe}](https://github.com/rust-lang/rust/pull/136154)
* [use `widening_mul` instead of a separate function](https://github.com/rust-lang/rust/pull/136409)
* [use an `Option` for `FindNextFileHandle` in `ReadDir` instead of `INVALID_FILE_HANDLE` sentinel value](https://github.com/rust-lang/rust/pull/136552)
* [use short ty string for binop and unop errors](https://github.com/rust-lang/rust/pull/136315)
* [visit all debug info in MIR Visitor](https://github.com/rust-lang/rust/pull/136722)
* [shard AllocMap Lock](https://github.com/rust-lang/rust/pull/136115)
* [miri: allow code to call `geteuid()`](https://github.com/rust-lang/miri/pull/4179)
* [miri: throw ub error when invoking non-vararg shim with vararg import](https://github.com/rust-lang/miri/pull/4181)
* [miri: use fcntl locking on Solaris instead of flock which is missing there](https://github.com/rust-lang/miri/pull/4177)
* [implement `eat_until` leveraging memchr in lexer](https://github.com/rust-lang/rust/pull/136585)
* [stabilise `Cursor::{get_mut, set_position}` in `const` scenarios](https://github.com/rust-lang/rust/pull/136634)
* [stabilize `feature(trait_upcasting)`](https://github.com/rust-lang/rust/pull/134367)
* [stabilize `map_many_mut` feature](https://github.com/rust-lang/rust/pull/136152)
* [stabilize `vec_pop_if`](https://github.com/rust-lang/rust/pull/135488)
* [add `unchecked_disjoint_bitor` per ACP373](https://github.com/rust-lang/rust/pull/135760)
* [add `UnsafeCell` direct access APIs](https://github.com/rust-lang/rust/pull/136398)
* [implement unstable `new_range` feature](https://github.com/rust-lang/rust/pull/136167)
* [implement inherent str constructors](https://github.com/rust-lang/rust/pull/136517)
* [add `cast_signed` and `cast_unsigned` methods for `NonZero` types](https://github.com/rust-lang/rust/pull/136511)
* [mark `std::fmt::from_fn` as `#[must_use]`](https://github.com/rust-lang/rust/pull/136502)
* [std: move network code into `sys`](https://github.com/rust-lang/rust/pull/136449)
* [std::fs: further simplify dirent64 handling](https://github.com/rust-lang/rust/pull/136479)
* [optimize `Rc::<str>::default()` implementation](https://github.com/rust-lang/rust/pull/136099)
* [rename `slice::take...` methods to `split_off...`](https://github.com/rust-lang/rust/pull/136555)
* [windows: remove readonly files](https://github.com/rust-lang/rust/pull/134679)
* [cargo: don't use on Solaris `libc::LOCK_*` which were removed from libc in ver…](https://github.com/rust-lang/cargo/pull/15143)
* [cargo: feat: add `cargo pkgid` support for cargo-script](https://github.com/rust-lang/cargo/pull/14961)
* [cargo: feat: emit error if package not found within workspace](https://github.com/rust-lang/cargo/pull/15071)
* [cargo: fix changelog link](https://github.com/rust-lang/cargo/pull/15142)
* [cargo: fix race condition in `panic_abort_tests`](https://github.com/rust-lang/cargo/pull/15169)
* [cargo: fix: align first line of unordered list with following](https://github.com/rust-lang/cargo/pull/15161)
* [cargo: fix: don't use "did you mean" in errors](https://github.com/rust-lang/cargo/pull/15138)
* [cargo: make cache tracking resilient to unexpected files](https://github.com/rust-lang/cargo/pull/15147)
* [cargo: simplify backtrack](https://github.com/rust-lang/cargo/pull/15150)
* [cargo: small resolver cleanups](https://github.com/rust-lang/cargo/pull/15040)
* [cargo: suggest similar feature names on CLI](https://github.com/rust-lang/cargo/pull/15133)
* [rustdoc: use ThinVec for generic arg parts](https://github.com/rust-lang/rust/pull/136265)
* [enable "jump to def" feature on rustc docs](https://github.com/rust-lang/rust/pull/136589)
* [rustfmt: `check_diff` function rewrite](https://github.com/rust-lang/rustfmt/pull/6390)
* [clippy: add `single_option_map` lint](https://github.com/rust-lang/rust-clippy/pull/14033)
* [clippy: `path_buf_push_overwrite`: mark suggestion as `MaybeIncorrect`](https://github.com/rust-lang/rust-clippy/pull/14010)
* [clippy: `useless_asref`: no lint if in a closure to change the ref depth](https://github.com/rust-lang/rust-clippy/pull/14090)
* [clippy: add MSRV check for `lines_filter_map_ok`](https://github.com/rust-lang/rust-clippy/pull/14130)
* [clippy: add MSRV check for `manual_flatten`](https://github.com/rust-lang/rust-clippy/pull/14086)
* [clippy: allow `assign_op_pattern` in the test of `string_add`](https://github.com/rust-lang/rust-clippy/pull/14143)
* [clippy: autofix for `range_zip_with_len`](https://github.com/rust-lang/rust-clippy/pull/14136)
* [clippy: change the applicability of `if_then_some_else_none` to `MachineApplicable`](https://github.com/rust-lang/rust-clippy/pull/14106)
* [clippy: correct "Affected lints" for `allow-one-hash-in-raw-strings`](https://github.com/rust-lang/rust-clippy/pull/14186)
* [clippy: correct version of `doc_overindented_list_items`](https://github.com/rust-lang/rust-clippy/pull/14152)
* [clippy: deprecate redundant lint `option_map_or_err_ok` and take `manual_ok_or` out of pedantic](https://github.com/rust-lang/rust-clippy/pull/14027)
* [clippy: do not trigger `[size_of_in_element_count]` for `u8`](https://github.com/rust-lang/rust-clippy/pull/14011)
* [clippy: don't emit suggestion inside macro in `manual_async_fn`](https://github.com/rust-lang/rust-clippy/pull/14142)
* [clippy: don't use labeled block as top-level blocks](https://github.com/rust-lang/rust-clippy/pull/14102)
* [clippy: fix ICE in `unnecessary_mut_passed`](https://github.com/rust-lang/rust-clippy/pull/14065)
* [clippy: fix `let_and_return` with temporary variables, and distinguish between Rust editions](https://github.com/rust-lang/rust-clippy/pull/14180)
* [clippy: fix `obfuscated_if_else` suggestion on left side of a binary expr](https://github.com/rust-lang/rust-clippy/pull/14124)
* [clippy: fix docs for `#[clippy::format_args]`](https://github.com/rust-lang/rust-clippy/pull/14161)
* [clippy: fix: `manual_unwrap_or_default` suggests falsely when condition type is uncertain](https://github.com/rust-lang/rust-clippy/pull/13889)
* [clippy: handle more cases in `is_normalizable`](https://github.com/rust-lang/rust-clippy/pull/13833)
* [clippy: make empty-line-after an early clippy lint](https://github.com/rust-lang/rust/pull/136657)
* [clippy: make `manual_map` ignore types that contain `dyn`](https://github.com/rust-lang/rust-clippy/pull/12712)
* [clippy: move `mutex_integer` to restriction and improve `mutex_`{`integer`, `atomic`} docs](https://github.com/rust-lang/rust-clippy/pull/14110)
* [clippy: skip `use_self` inside macro expansions of a `impl Self` block](https://github.com/rust-lang/rust-clippy/pull/13128)
* [clippy: two improvements to `disallowed_*`](https://github.com/rust-lang/rust-clippy/pull/13669)
* [clippy: use MIR body to identify more "default equivalent" calls for `derivable_impls`](https://github.com/rust-lang/rust-clippy/pull/13988)
* [clippy: use parentheses when needed in `nonminimal_bool` lint](https://github.com/rust-lang/rust-clippy/pull/14187)
* [rust-analyzer: fix off-by-one error in RangeFormatting](https://github.com/rust-lang/rust-analyzer/pull/19124)
* [rust-analyzer: don't emit empty scip occurrence for builtins](https://github.com/rust-lang/rust-analyzer/pull/19105)
* [rust-analyzer: fix IDE resolution of `use` inside a body](https://github.com/rust-lang/rust-analyzer/pull/19094)
* [rust-analyzer: if item exsits on module, resolve as module instead of type](https://github.com/rust-lang/rust-analyzer/pull/19088)
* [rust-analyzer: resolve projection types before checking casts](https://github.com/rust-lang/rust-analyzer/pull/19106)
* [rust-analyzer: upmap ranges in `convert_tuple_struct_to_named_struct` assist](https://github.com/rust-lang/rust-analyzer/pull/18912)
* [rust-analyzer: line-index: don't try to use (unavailable) neon on big-endian aarch64](https://github.com/rust-lang/rust-analyzer/pull/19083)
* [rust-analyzer: option to disable inlay Type hints for Closure parameters](https://github.com/rust-lang/rust-analyzer/pull/19104)
* [rust-analyzer: organise chapters in mdbook sidebar](https://github.com/rust-lang/rust-analyzer/pull/19115)
* [rust-analyzer: prevent panics from tearing down worker threads](https://github.com/rust-lang/rust-analyzer/pull/19093)
* [rust-analyzer: split cache priming into distinct phases](https://github.com/rust-lang/rust-analyzer/pull/19084)
* [rust-analyzer: use interior mutability for loaded `ProcMacrorv::expanders`](https://github.com/rust-lang/rust-analyzer/pull/19099)

### Rust Compiler Performance Triage

A relatively neutral week, with lots of real changes but most small in
magnitude. Most significant change is rustdoc's move of JS/CSS minification to
build time which cut doc generation times on most benchmarks fairly
significantly.

Triage done by **@simulacrum**.
Revision range: [01e4f19c..c03c38d5](https://perf.rust-lang.org/?start=01e4f19cc8027925ffe0885a86388b700e46bfab&end=c03c38d5c2368cd2aa0e056dba060b94fc747f4e&absolute=false&stat=instructions%3Au)

3 Regressions, 5 Improvements, 1 Mixed; 2 of them in rollups
32 artifact comparisons made in total

[Full report here](https://github.com/rust-lang/rustc-perf/blob/master/triage/2025-02-10.md)

### [Approved RFCs](https://github.com/rust-lang/rfcs/commits/master)

Changes to Rust follow the Rust [RFC (request for comments) process](https://github.com/rust-lang/rfcs#rust-rfcs). These
are the RFCs that were approved for implementation this week:

* *No RFCs were approved this week.*

### Final Comment Period

Every week, [the team](https://www.rust-lang.org/team.html) announces the 'final comment period' for RFCs and key PRs
which are reaching a decision. Express your opinions now.

#### [RFCs](https://github.com/rust-lang/rfcs/labels/final-comment-period)
* [RFC: project goals for 2025h1](https://github.com/rust-lang/rfcs/pull/3764)

#### Tracking Issues & PRs
##### [Rust](https://github.com/rust-lang/rust/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc)
* [Stabilize `num_midpoint_signed` feature](https://github.com/rust-lang/rust/pull/134340)
* [Do not deduplicate list of associated types provided by dyn principal](https://github.com/rust-lang/rust/pull/136458)
* [regression: a value of type `HashMap<Pulse, u64>` cannot be built from](https://github.com/rust-lang/rust/issues/135669)
* [Tracking Issue for `inherent_str_constructors`](https://github.com/rust-lang/rust/issues/131114)
* [Tracking Issue for `os_str_display`](https://github.com/rust-lang/rust/issues/120048)
* [Do not allow attributes on struct field rest patterns](https://github.com/rust-lang/rust/pull/136490)
* [feat(core): impl Step for NonZero < u* >](https://github.com/rust-lang/rust/pull/127534)
* [Future incompatibility warning `unsupported_fn_ptr_calling_conventions`: Also warn in dependencies](https://github.com/rust-lang/rust/pull/135767)
* [Make Miri aware of leaks of `Box`/`Vec`/`String`](https://github.com/rust-lang/rust/pull/135811)
* [Tracking Issue for `integer_sign_cast`](https://github.com/rust-lang/rust/issues/125882)

##### [Cargo](https://github.com/rust-lang/cargo/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc)
* *No Cargo Tracking Issues or PRs entered Final Comment Period this week.*

##### [Language Team](https://github.com/rust-lang/lang-team/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc+)
* *No Language Team Proposals entered Final Comment Period this week.*

##### [Language Reference](https://github.com/rust-lang/reference/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc)
* *No Language Reference RFCs entered Final Comment Period this week.*

##### [Unsafe Code Guidelines](https://github.com/rust-lang/unsafe-code-guidelines/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc)
* *No Unsafe Code Guideline Tracking Issues or PRs entered Final Comment Period this week.*

#### [New and Updated RFCs](https://github.com/rust-lang/rfcs/pulls)
* [#[doc(consts)]](https://github.com/rust-lang/rfcs/pull/3770)

## Upcoming Events

Rusty Events between 2025-02-12 - 2025-03-12 🦀

### Virtual
* 2025-02-12 | Virtual (Cardiff, UK) | [Rust and C++ Cardiff](https://www.meetup.com/rust-and-c-plus-plus-in-cardiff/events/)
    * [**Joint Online meetup with Rust Bristol!**](https://www.meetup.com/rust-and-c-plus-plus-in-cardiff/events/305833952)
* 2025-02-13 | Virtual (Berlin, DE) | [Rust Berlin](https://www.meetup.com/rust-berlin/events/)
    * [**Rust Hack and Learn**](https://www.meetup.com/rust-berlin/events/299468342)
* 2025-02-14 | Virtual (Jersey City, NJ, US) | [Jersey City Classy and Curious Coders Club Cooperative](https://www.meetup.com/jersey-city-classy-curious-coders-club-cooperative/events/)
    * [**Rust Coding / Game Dev Fridays Open Mob Session!**](https://www.meetup.com/jersey-city-classy-curious-coders-club-cooperative/events/305815307)
* 2025-02-19 | Virtual (Vancouver, BC, CA) | [Vancouver Rust](https://www.meetup.com/vancouver-rust/events/)
    * [**Pointer Provenance**](https://www.meetup.com/vancouver-rust/events/304051783)
* 2025-02-20 | Hybrid (Redmond, WA, US) | [Seattle Rust User Group](https://www.meetup.com/join-srug/events/)
    * [**February, 2025 SRUG (Seattle Rust User Group) Meetup**](https://www.meetup.com/join-srug/events/305658424)
* 2025-02-21 | Virtual (Jersey City, NJ, US) | [Jersey City Classy and Curious Coders Club Cooperative](https://www.meetup.com/jersey-city-classy-curious-coders-club-cooperative/events/)
    * [**Rust Coding / Game Dev Fridays Open Mob Session!**](https://www.meetup.com/jersey-city-classy-curious-coders-club-cooperative/events/gvxrntyhcdbcc)
* 2025-02-25 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust/events/)
    * [**Fourth Tuesday**](https://www.meetup.com/dallasrust/events/305361428)
* 2025-02-25 | Virtual (London, UK) | [Women in Rust](https://www.meetup.com/women-in-rust/events/)
    * [**Lunch & Learn: The complicated world of Strings in Rust**](https://www.meetup.com/women-in-rust/events/305716182)
* 2025-02-25 | Virtual (Washington, DC, US) | [Rust DC](https://www.meetup.com/rustdc/events/)
    * [**Mid-month Rustful—Everett Pompeii presents Bencher 🐰**](https://www.meetup.com/rustdc/events/305170682)
* 2025-02-27 | Virtual (US) | [Ardan Labs](https://www.eventbrite.com/o/ardan-labs-7092394651)
    * [**Intro to Rust**](https://www.eventbrite.com/e/intro-to-rust-tickets-1237517059839)
* 2025-02-27 | Virtual (Berlin, DE) | [Rust Berlin](https://www.meetup.com/rust-berlin/events/)
    * [**Rust Hack and Learn**](https://www.meetup.com/rust-berlin/events/300820295)
* 2025-02-27 | Virtual (Charlottesville, VA, US) | [Charlottesville Rust Meetup](https://www.meetup.com/charlottesville-rust-meetup/events/)
    * [**Parsing command line options with category theory and async**](https://www.meetup.com/charlottesville-rust-meetup/events/305948365)
* 2025-03-01 | Virtual (Kampala, UG) | [Rust Circle Kampala](https://www.eventbrite.com/o/rust-circle-kampala-65249289033/)
    * [**Rust Circle Meetup**](https://www.eventbrite.com/e/rust-circle-meetup-tickets-62876317658/)
* 2025-03-05 | Virtual (Indianapolis, IN, US) | [Indy Rust](https://www.meetup.com/indyrs/events/)
    * [**Indy.rs - with Social Distancing**](https://www.meetup.com/indyrs/events/302031659)
* 2025-03-06 | Virtual (Nürnberg, DE) | [Rust Nurnberg DE](https://www.meetup.com/rust-noris/)
    * [**Rust Nürnberg online**](https://www.meetup.com/rust-noris/events/300820281/)
* 2025-03-06 | Virtual (Rotterdam, NL) | [Bevy Game Development](https://www.meetup.com/bevy-game-development/events/)
    * [**Bevy Meetup #9**](https://www.meetup.com/bevy-game-development/events/306131557)
* 2025-03-11 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust/events/)
    * [**Second Tuesday**](https://www.meetup.com/dallasrust/events/303522529)
* 2025-03-11 | Virtual (London, UK) | [Women in Rust](https://www.meetup.com/women-in-rust/events/)
    * [**👋 Community Catch Up**](https://www.meetup.com/women-in-rust/events/305716839)

### Asia
* 2025-02-24 | Tel Aviv-Yafo, IL | [Rust 🦀 TLV](https://www.meetup.com/rust-tlv/events/)
    * [**In person Rust February 2025 at AWS in Tel Aviv**](https://www.meetup.com/rust-tlv/events/305570131)
* 2025-03-01 | Bangalore/Bengaluru, IN | [Rust Bangalore](https://hasgeek.com/rustbangalore)
    * [**Zig & Rust Meetup**](https://lu.ma/460w8v58)

### Europe
* 2025-02-12 | Reading, UK | [Reading Rust Workshop](https://www.meetup.com/reading-rust-workshop/events/)
    * [**Reading Rust Meetup**](https://www.meetup.com/reading-rust-workshop/events/305045444)
* 2025-02-14 | Edinburgh, UK | [Rust and Friends](https://www.meetup.com/rust-edi/events/)
    * [**Rust and Friends (daytime coffee)**](https://www.meetup.com/rust-and-friends/events/305791536)
* 2025-02-18 | Leipzig, SN, DE | [Rust - Modern Systems Programming in Leipzig](https://www.meetup.com/rust-modern-systems-programming-in-leipzig/events/)
    * [**Introduction to Context-Generic Programming in Rust**](https://www.meetup.com/rust-modern-systems-programming-in-leipzig/events/303729528)
* 2025-02-18 | London, UK | [Rust London User Group](https://www.meetup.com/rust-london-user-group/events/)
    * [**LDN Talks February: Rust Nation 2025 Pre-Conference Meetup **](https://www.meetup.com/rust-london-user-group/events/306036448)
* 2025-02-19 - 2025-02-20 | London, UK | [Rust Nation UK](https://www.rustnationuk.com/)
    * [**Rust Nation UK 2025**](https://www.rustnationuk.com/)
* 2025-02-20 | Bern, CH | [Rust Bern](https://www.meetup.com/rust-bern/events/)
    * [**2025 Rust Talks Bern #1 @Puzzle ITC**](https://www.meetup.com/rust-bern/events/305597994)
* 2025-02-21 | London, UK | [Rust Global: London 2025](https://rustfoundation.org/event/rust-global-london-2025/)
    * [**Rust Global: London 2025**](https://rustfoundation.org/event/rust-global-london-2025/)
* 2025-02-22 | Stockholm, SE | [Stockholm Rust](https://www.meetup.com/stockholm-rust/events/)
    * [**Ferris' Fika Forum #9**](https://www.meetup.com/stockholm-rust/events/305848723)
* 2025-02-25 | Madrid, ES | [MadRust](https://www.meetup.com/madrust/events/)
    * [**Rust desde cero: Cargo y tipos**](https://www.meetup.com/madrust/events/305896258)
* 2025-02-26 | Darmstadt, DE | [Rust Rhein Main](https://www.meetup.com/rust-rhein-main/events/)
    * [**Rust Compiler Tuning**](https://www.meetup.com/rust-rhein-main/events/305990886/)
* 2025-02-27 | Oslo, NO | [Rust Oslo](https://www.meetup.com/rust-oslo/events/)
    * [**Rust Hack'n'Learn at Kampen Bistro**](https://www.meetup.com/rust-oslo/events/305809675)
* 2025-02-27 | Paris, FR | [Rust Paris](https://www.meetup.com/rust-paris/events/)
    * [**Rust meetup #75**](https://www.meetup.com/rust-paris/events/305791655)
* 2025-03-01 | Nürnberg, DE | [Rust Nuremberg](https://www.meetup.com/rust-noris/events/)
    * [**Technikmuseum Speyer**](https://www.meetup.com/rust-noris/events/305361732/)
* 2025-03-05 | Barcelona, ES | [BcnRust](https://www.meetup.com/bcnrust/events/)
    * [**17th BcnRust Meetup**](https://www.meetup.com/bcnrust/events/305887675)
* 2025-03-12 | Reading, UK | [Reading Rust Workshop](https://www.meetup.com/reading-rust-workshop/events/)
    * [**Reading Rust Meetup**](https://www.meetup.com/reading-rust-workshop/events/305045445)

### North America
* 2025-02-13 | Portland, OR, US | [PDXRust](https://www.meetup.com/pdxrust/events/)
    * [**Spidering Wikipedia Politely In Async Rust**](https://www.meetup.com/pdxrust/events/306044189)
* 2025-02-14 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust/events/)
    * [**Downtown Rust Lunch, Feb 14**](https://www.meetup.com/bostonrust/events/305804954)
* 2025-02-18 | San Francisco, CA, US | [San Francisco Rust Study Group](https://www.meetup.com/san-francisco-rust-study-group/events/)
    * [**Rust Hacking in Person**](https://www.meetup.com/san-francisco-rust-study-group/events/302638261)
* 2025-02-20 | Chicago, IL, US | [Chicago Rust Meetup](https://www.meetup.com/chicago-rust-meetup/events/)
    * [**Rust Happy Hour**](https://www.meetup.com/chicago-rust-meetup/events/306087854)
* 2025-02-20 | Nashville, TN, US | [Music City Rust Developers](https://www.meetup.com/music-city-rust-developers/events/)
    * [**Rust Game Development Series 2: Basics of Game Development**](https://www.meetup.com/music-city-rust-developers/events/304333047)
* 2025-02-20 | Redmond, WA, US | [Seattle Rust User Group](https://www.meetup.com/join-srug/events/)
    * [**February, 2025 SRUG (Seattle Rust User Group) Meetup**](https://www.meetup.com/join-srug/events/305658424)
* 2025-02-21 | México City, MX | [Rust MX](https://www.meetup.com/rust-mx/events/)
    * [**Rust y ciencia de datos**](https://www.meetup.com/rust-mx/events/305793010)
* 2025-02-22 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust/events/)
    * [**Somerville Union Square Rust Lunch, Feb 22**](https://www.meetup.com/bostonrust/events/305805059)
* 2025-02-26 | Austin, TX, US | [Rust ATX](https://www.meetup.com/rust-atx/events/)
    * [**Rust Lunch - Fareground**](https://www.meetup.com/rust-atx/events/xvkdgtyhcdbjc)
* 2025-02-27 | Atlanta, GA, US | [Rust Atlanta](https://www.meetup.com/rust-atl/events/)
    * [**Starting the meetup again**](https://www.meetup.com/rust-atl/events/305776081)
* 2025-03-02 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust/events/)
    * [**Beacon Hill Rust Lunch, Mar 2**](https://www.meetup.com/bostonrust/events/305805164)
* 2025-03-06 | Saint Louis, MO, US | [STL Rust](https://www.meetup.com/stl-rust/events/)
    * [**CRDTs in Rust**](https://www.meetup.com/stl-rust/events/305187783)
* 2025-03-10 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust/events/)
    * [**Davis Square Rust Lunch, Mar 10**](https://www.meetup.com/bostonrust/events/305805192)

### Oceania
* 2025-02-24 | Collingwood, VI, AU | [Rust Melbourne](https://www.meetup.com/rust-melbourne/events/)
    * [**February 2025 Rust Melbourne Meetup**](https://www.meetup.com/rust-melbourne/events/306040785)
* 2025-02-25 | Barton, AC, AU | [Canberra Rust User Group](https://www.meetup.com/rust-canberra/events/)
    * [**February Meetup**](https://www.meetup.com/rust-canberra/events/306090406)
* 2025-03-04 | Perth, WA, AU | [Rust Perth Meetup Group](https://www.meetup.com/perth-rust-meetup-group/events/)
    * [**How Orica is using Rust in their workplace**](https://www.meetup.com/perth-rust-meetup-group/events/306131753)

If you are running a Rust event please add it to the [calendar] to get
it mentioned here. Please remember to add a link to the event too.
Email the [Rust Community Team][community] for access.

[calendar]: https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com
[community]: mailto:community-team@rust-lang.org

## Jobs
<!--

Rust Jobs:

TWiR has stopped featuring individual job postings. You can read more about this change here:

https://github.com/rust-lang/this-week-in-rust/issues/3412

-->

Please see the latest [Who's Hiring thread on r/rust](https://www.reddit.com/r/rust/comments/1hynsw7/official_rrust_whos_hiring_thread_for_jobseekers/)

# Quote of the Week

> Just because things are useful doesn't mean they are magically sound.

– [Ralf Jung on github](https://github.com/rust-lang/rust/issues/132442#issuecomment-2636065726)

Thanks to [scottmcm](https://users.rust-lang.org/t/twir-quote-of-the-week/328/1658) for the suggestion!

[Please submit quotes and vote for next week!](https://users.rust-lang.org/t/twir-quote-of-the-week/328)

*This Week in Rust is edited by: [nellshamrell](https://github.com/nellshamrell), [llogiq](https://github.com/llogiq), [cdmistman](https://github.com/cdmistman), [ericseppanen](https://github.com/ericseppanen), [extrawurst](https://github.com/extrawurst), [U007D](https://github.com/U007D), [joelmarcey](https://github.com/joelmarcey), [mariannegoldin](https://github.com/mariannegoldin), [bennyvasquez](https://github.com/bennyvasquez), [bdillo](https://github.com/bdillo)*

*Email list hosting is sponsored by [The Rust Foundation](https://foundation.rust-lang.org/)*

<small>[Discuss on r/rust](https://www.reddit.com/r/rust/comments/1ioajhc/this_week_in_rust_586_this_week_in_rust/)</small>
