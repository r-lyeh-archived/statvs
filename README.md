status
======

My name is r-lyeh and I code videogames :neckbeard:

This repo is meant to be a semi-conclusive list of projects in which the author is / has participated in.

A few notes:

- The specifications below are Public Domain or CC0.
- The libraries below are Public Domain or _BOOST licensed_ (~MIT equivalent with no attribution required in binary distributions); they are (wherever possible) _cross-platform_, have _no external dependencies_, are _header-only_; they have been used in _commercial games_ (and should be battle-tested); and they follow this extension convention: `.hpp/.cpp` for sources, `.cc` for samples and `.cxx` for tests and benchmarks.

Released
----

Fully released / tested; more features may be incoming, but these are considered to be in a 'stable' state.

| Tags             | Repository  |
|:----------------:|:------------|
| io               | [Apathy (C++11)](http://github.com/r-lyeh/apathy) <br/> lightweight *stream/file/mmap/path/virtual-filesystem* IO library.
| spec             | [ARYA](http://github.com/r-lyeh/ARYA) <br/> CC0 *asset naming convention*.
| debug            | [Assert++ (C++03)](http://github.com/r-lyeh/assert) <br/> a smart *assert replacement* for LHS/RHS values.
| tool, image      | [Attila:star2:](https://github.com/r-lyeh/attila) <a href="https://travis-ci.org/r-lyeh/attila"><img src="https://api.travis-ci.org/r-lyeh/attila.svg?branch=master" align="right" /></a> <br/> tiny *atlas texture/image packer tool*.
| security         | [Auth (C++03)](http://github.com/r-lyeh/auth) <br/> simple, lightweight and safe client-server *authentication system*.
| encoding         | [Base91x (C++03)](http://github.com/r-lyeh/base91x) <br/> lightweight *binary-to-text encoder/decoder* smaller than base64.
| user-interface   | [Bubble (C++11)](https://github.com/r-lyeh/bubble) <br/> simple and lightweight *dialog library for Windows*.
| compression      | [Bundle (C++03,C++11):star2:](https://github.com/r-lyeh/bundle) <a href="https://travis-ci.org/r-lyeh/bundle"><img src="https://api.travis-ci.org/r-lyeh/bundle.svg?branch=master" align="right" /></a> <br/> an embeddable *compression* library that supports ZIP, LZMA, LZIP, ZPAQ, LZ4, ZSTD, BROTLI and SHOCO. |
| compression,tool | [Bundler](https://github.com/r-lyeh/bundler) <br/> command-line *compression tool*.
| hashing          | [Cocoa (C++11):star2:](http://github.com/r-lyeh/cocoa) <br/> *hashing library* that provides interface for CRC32, CRC64, GCRC, RS, JS, PJW, ELF, BKDR, SBDM, DJB, DJB2, BP, FNV, AP, BJ1, MH2, SHA1, SFH.
| encoding         | [Collage (C++03)](https://github.com/r-lyeh/collage) <br/> lightweight library to *diff and patch* arbitrary data.
| unit-testing     | [Dessert (C++11):star2:](http://github.com/r-lyeh/dessert) <br/> lightweight *unit-testing framework*.
| gameplay         | [Flare (C++03)](https://github.com/r-lyeh/flare) <br/> lightweight C++ API to deal with *digital signals/logical buttons*.
| network          | [Flow (C++11)](https://github.com/r-lyeh/flow) <br/> lightweight network downloader with native fallbacks aimed to gamedev.
| gameplay         | [Frodo (C++11)](https://github.com/r-lyeh/frodo) <br/> lightweight *ring dependency framework*.
| gameplay         | [FSM (C++11)](http://github.com/r-lyeh/fsm) <br/> lightweight Hierarchical/*Finite-State Machine* (H/FSM) class.
| design           | [Gamebook (Markdown)](https://github.com/r-lyeh/gamebook) <br/> unified *game design document*.
| io               | [Giant (C++11)](http://github.com/r-lyeh/giant) <br/> tiny library to *handle little/big endianness*.
| debug            | [Heal (C++03)](http://github.com/r-lyeh/heal) <br/> lightweight library to aid and *debug applications*.
| input            | [Hyde (C++03)](http://github.com/r-lyeh/hyde) <br/> lightweight and simple Human *Inferface Device* (HID) library.
| hashing          | [ID (C++11)](http://github.com/r-lyeh/id) <br/> simple *compile-time hasher* and sequential ID generator.
| spec             | [JXML](http://github.com/r-lyeh/JXML) <br/> loss-less representation of *JSON in XML* that is based on [JSONx](http://goo.gl/I3cxs).
| spec             | [JXMLex](http://github.com/r-lyeh/JXMLex) <br/> expressive representation of *JSON in XML* that is based on [JSONx](http://goo.gl/I3cxs) and [JXML](http://github.com/r-lyeh/JXML).
| network          | [Knot (C++03)](http://github.com/r-lyeh/knot) <br/> lightweight and simple *TCP networking* C++ library.
| gameplay         | [Kult (C++11):star2:](https://github.com/r-lyeh/kult) <br/> lightweight *entity/component/system* library.
| gameplay         | [Live (C++11)](http://github.com/r-lyeh/live) <br/> *automatic reloader* of variables, featuring type inference.
| data-structures  | [LRU (C++11)](https://github.com/r-lyeh/lru) <br/> lightweight *LRU cache structure* for list<T> and map<K,V> containers.
| spec,serial      | [Medea (C++11)](http://github.com/r-lyeh/medea) <br/> lightweight and *tiny serializer*. In mythology, also Jason's wife.
| gameplay         | [Memo (C++11)](http://github.com/r-lyeh/memo) <br/> simple and lightweight *factory class*, featuring automatic type casting.
| data-structures  | [Oak (C++03)](http://github.com/r-lyeh/oak) <br/> simple and lightweight *tree container*.
| design           | [Pitch (Markdown)](https://github.com/r-lyeh/pitch) <br/> forkable game *pitch template*.
| spec,tool,image  | [Pug](https://github.com/r-lyeh/pug) <br/> *pug, png with a twist*: lossy image format.
| network          | [Route66 (C++03)](https://github.com/r-lyeh/route66) <br/> lightweight *embeddable HTTP server*.
| time             | [Sand (C++11)](http://github.com/r-lyeh/sand) <br/> lightweight and simple *time library* that provides interface for Unix stamps, hires timers, calendars and locales.
| hashing          | [Sole (C++11):star2:](http://github.com/r-lyeh/sole) <br/> lightweight library to generate universally *unique identificators* (UUID) both v1 and v4.
| image            | [Spot (C++11):star2:](http://github.com/r-lyeh/spot) <a href="https://travis-ci.org/r-lyeh/spot"><img src="https://api.travis-ci.org/r-lyeh/spot.svg?branch=master" align="right" /></a> <br/> compact and embeddable RGBA/HSLA library that supports *WebP, JPG, progressive JPG, PNG, TGA, DDS DXT1/2/3/4/5, BMP, PSD, GIF, PKM (ETC1), PVR (PVRTC), HDR, PIC, PUG, PNM (PPM/PGM) and vectorial SVG files*.
| databases        | [SQLight (C++11)](http://github.com/r-lyeh/sqlight) <br/> lightweight *MySQL client*.
| debug            | [Tracey (C++11):star2:](http://github.com/r-lyeh/tracey) <br/> lightweight and simple C++ memory *leak finder* with no dependencies.
| data-structures  | [Trie (C++11)](http://github.com/r-lyeh/trie) <br/> lightweight and simple *autocompletion* data structure.
| animation        | [Tween (C++03)](https://github.com/r-lyeh/tween) <br/> lightweight *easing library*.
| data-structures  | [Unordered_map (C++11)](http://github.com/r-lyeh/unordered_map) <br/> *portable header* for std::unordered_map<K,V> template.
| security         | [Vault (C++03)](http://github.com/r-lyeh/vault) <br/> lightweight and simple *crypt library* that provides interface for ARC4.
| network          | [VLE (C99, C++03)](https://github.com/r-lyeh/vle) <br/> simple *variable-length encoder/decoder*.
| audio            | [Wave (C++11)](http://github.com/r-lyeh/wave) <br/> lightweight *3D sound wrapper* for OpenAL that supports OGG and MusePack decoding.
| data-structures  | [Wire (C++03):star2:](http://github.com/r-lyeh/wire) <br/> a drop-in *std::string replacement* with extended functionality, string interpolation and safe C/C++ formatters.


Personal
----

These are mostly released experiments, but are geared towards personal use; as such, they may be of very limited use during development.

* [Burg](https://github.com/r-lyeh/burg) -- a simple burg linear predictor (C++11).
* [Bridge](https://github.com/r-lyeh/bridge) -- a standard C++/boost *compatibility layer*, plus a few utils (C++11/C++03).
* [Cash-of-clans](https://github.com/r-lyeh/cash-of-clans) -- a free re-implementation of a working *game economy system*.
* [Codex](https://github.com/r-lyeh/codex) -- lightweight and simple C++ library to escape, unescape, read, write and convert from/to different *encoding charsets*.
* [DrEcho](https://github.com/r-lyeh/DrEcho) -- DrEcho *spices your terminal up* (C++11).
* [Duty](https://github.com/r-lyeh/duty) -- lightweight *task manager* for parallel coroutines and serial jobs (C++11).
* [RGB332 (tool)](https://github.com/r-lyeh/rgb332) -- custom uniform *RGB332 palette*.
* [Sentry](https://github.com/r-lyeh/sentry) -- lightweight *data monitor* (C++11).
* [Variant](https://github.com/r-lyeh/variant) -- *varying* class that clones javascript behaviour as much as possible (C++11).
* [Test-allocators](https://github.com/r-lyeh/test-allocators) -- benchmark for different *memory allocators*.
* [Test-physics](https://github.com/r-lyeh/test-physics) -- benchmark for different *physics integrators*.

In Progress
----

Proof-of-concepts until stabilised, currently in active development.

* [Eve](https://github.com/r-lyeh/eve) -- *game engine* where graphics are low priority (C++11).
* [Haikui](https://github.com/r-lyeh/haikui) -- UI library where everything is a *grid*.
* [Jabba](https://github.com/r-lyeh/jabba) -- (C++11).
* [Play](https://github.com/r-lyeh/play) -- easy *alternative to scripting* in gameplay code.
* [Solace](https://github.com/r-lyeh/solace) -- modern *console replacement*.
* [Wake](https://github.com/r-lyeh/wake)
* [Watchmen](https://github.com/r-lyeh/watchmen) -- *asset dependency system* for games in run-time.

Contributions
----

Projects in collaboration with other coders.

* [jsonxx](http://github.com/hjiang/jsonxx) -- lightweight *JSON parser* written in C++.
* [IMGUI](http://github.com/r-lyeh/imgui) -- OpenGL 2/3 *Immediate Mode GUI* toolkit.

On Hold
----

Each of these projects are suffering from an existential crisis.

* [Fontbase](http://github.com/r-lyeh/fontbase) -- collection of *western, CJK and iconographic fonts* free for commercial usage.
* [Stringbase](http://github.com/r-lyeh/stringbase) -- collaborative effort aimed to *translate common texts* found in videogames and regular apps. 

Planned
----

Yet to be committed, removed and/or finished. Someday.

* [Blender](http://github.com/r-lyeh/blender)
* [Cash](https://github.com/r-lyeh/cash)
* [Gate](https://github.com/r-lyeh/gate)
* [Geo](https://github.com/r-lyeh/geo)
* [Grog](https://github.com/r-lyeh/grog)
* [Ling](https://github.com/r-lyeh/ling)
* [Metatracker](http://github.com/r-lyeh/metatracker)
* [Realm](https://github.com/r-lyeh/realm)
* [Sharpdoc](https://github.com/r-lyeh/sharpdoc)
* [Silo](https://github.com/r-lyeh/silo)
* [Skull](https://github.com/r-lyeh/skull)
* [Social](https://github.com/r-lyeh/social)
* [Tint](http://github.com/r-lyeh/tint)
* [Unposix](https://github.com/r-lyeh/unposix)
* [Wrapp](https://github.com/r-lyeh/wrapp)

Abandoned
----

Help, I've fallen and can't get up!

These are either fully abandoned, or are buggy class-related repositories for classes which are finished.

* [Moon9](https://github.com/r-lyeh/moon9) -- old game engine
* [Wood](https://github.com/r-lyeh/wood) -- old tree data structure

Resume
---

For completeness.

* [Vitae](http://github.com/r-lyeh/vitae) -- my self-compilable *C++ resume*
