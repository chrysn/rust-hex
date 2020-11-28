hex-noalloc
===========

**This is a temporary fork of the [hex](https://github.com/KokaKiwi/rust-hex)
crate, uploaded to make it usable for other crates that are uploaded to
crates.io until [#42](https://github.com/KokaKiwi/rust-hex/pull/42) is
merged.**

It is a snapshot of the hex crate, with just that single PR merged. It will be
yanked from crates.io once that issue is resolved and a new version of hex is
released, at which point users are asked to depend on hex again instead.

Usage, examples, license etc.
=============================

Please refer to the [original crate](https://github.com/KokaKiwi/rust-hex) for
this; other than the addition of the `alloc` feature merged from
[#42](https://github.com/KokaKiwi/rust-hex/pull/42), all else is unchanged.
