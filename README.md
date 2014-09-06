status
======

- My name is rlyeh and I code videogames :neckbeard:
- All my libraries are MIT licensed and written in C++/C++11.
- Most of them are cross-platform, have no external dependencies and are single-header where possible.
- I follow this extension convention: libraries: *.hpp *.cpp, samples: *.cc, tests: *.cxx.

This repo is meant to be a semi-conclusive list of projects in which the author is / has participated in.

Released
----

Fully released / tested; more features may be incoming, but these are considered to be in a 'stable' state.

* Animation & time
  - [Sand](http://github.com/r-lyeh/sand) -- lightweight and simple *time library* that provides interface for Unix stamps, hires timers, calendars, locales and tweening (C++11).
* Audio
  - [Wave](http://github.com/r-lyeh/wave) -- lightweight *3D sound wrapper* for OpenAL that supports OGG and MusePack decoding.
* Compression
  - [Bundle](https://github.com/r-lyeh/bundle) -- lightweight C++ *compression library* that provides interface for ZIP, LZMA, LZIP, ZPAQ, LZ4 and SHOCO algorithms (C++03).
  - [Bundler](https://github.com/r-lyeh/bundler) -- command-line *compression tool*.
* Databases
  - [SQLight](http://github.com/r-lyeh/sqlight) -- lightweight *MySQL client* (C++11).
* Data structures
  - [Oak](http://github.com/r-lyeh/oak) -- simple and lightweight *tree container* (C++03). 
  - [Wire](http://github.com/r-lyeh/wire) -- C++ *std::string replacement* that features extended functionality, string interpolation and safe C/C++ formatters.
  - [Trie](http://github.com/r-lyeh/trie) -- lightweight and simple *autocompletion* data structure (C++11).
  - [Unordered_map](http://github.com/r-lyeh/unordered_map) -- *portable header* for std::unordered_map<K,V> template.
* Debug
  - [Assert++](http://github.com/r-lyeh/assert) -- a smart *assert replacement* for LHS/RHS value (C++03).
  - [Heal](http://github.com/r-lyeh/heal) -- lightweight library to aid and *debug applications* (C++03).
  - [Tracey](http://github.com/r-lyeh/tracey) -- lightweight and simple C++ memory *leak finder* with no dependencies.
* Gameplay
  - [FSM](http://github.com/r-lyeh/fsm) -- lightweight Hierarchical/*Finite-State Machine* (H/FSM) class (C++11).
  - [Kult](https://github.com/r-lyeh/kult) -- lightweight *entity/component/system* library (C++11).
  - [Live](http://github.com/r-lyeh/live) -- *automatic reloader* of variables, featuring type inference (C++11).
  - [Memo](http://github.com/r-lyeh/memo) -- simple and lightweight *factory class*, featuring automatic type casting (C++11).
* Hashing
  - [Cocoa](http://github.com/r-lyeh/cocoa) -- *hashing library* that provides interface for CRC32, CRC64, GCRC, RS, JS, PJW, ELF, BKDR, SBDM, DJB, DJB2, BP, FNV, AP, BJ1, MH2, SHA1, SFH (C++03).
  - [ID](http://github.com/r-lyeh/id) -- simple *compile-time hasher* and sequential ID generator (C++11).
  - [Sole](http://github.com/r-lyeh/sole) -- lightweight library to generate universally *unique identificators* (UUID) both v1 and v4 (C++11).
* Input
  - [Hyde](http://github.com/r-lyeh/hyde) -- lightweight and simple Human *Inferface Device* (HID) library (C++03). 
* I/O
  - [Apathy](http://github.com/r-lyeh/apathy) -- lightweight *stream/file/mmap/path/virtual-filesystem* IO library (C++11).
  - [Base91x](http://github.com/r-lyeh/base91x) -- lightweight *binary-to-text encoder/decoder* smaller than base64 (C++03). 
  - [Knot](http://github.com/r-lyeh/knot) -- lightweight and simple *TCP networking* C++ library (C++03).
  - [Giant](http://github.com/r-lyeh/giant) -- tiny library to *handle little/big endianness* (C++11).
* Render
  - [Dot](http://github.com/r-lyeh/dot) -- simple and lightweight RGBA/HSLA library that support *WebP, JPG, progressive JPG, SVG, PNG, TGA, BMP, PSD, GIF, HDR and PIC images* (C++03).
* Security
  - [Auth](http://github.com/r-lyeh/auth) -- simple, lightweight and safe client-server *authentication system* (C++).
  - [Vault](http://github.com/r-lyeh/vault) -- lightweight and simple *crypt library* that provides interface for ARC4 (C++03).
* Serialization
  - [Medea (spec+lib)](http://github.com/r-lyeh/medea) -- lightweight and *tiny serializer*. In mythology, also Jason's wife (C++11).
* Specifications
  - [ARYA](http://github.com/r-lyeh/ARYA) -- CC0 *asset naming convention*. 
  - [JXML](http://github.com/r-lyeh/JXML) -- loss-less representation of *JSON in XML* that is based on [JSONx](http://goo.gl/I3cxs). 
  - [JXMLex](http://github.com/r-lyeh/JXMLex) -- expressive representation of *JSON in XML* that is based on [JSONx](http://goo.gl/I3cxs) and [JXML](http://github.com/r-lyeh/JXML).
* Unit-testing
  - [Dessert](http://github.com/r-lyeh/dessert) -- lightweight and simple *test framework* (C++11).
* User Interface
  - [Bubble](https://github.com/r-lyeh/bubble) -- simple and lightweight *dialog library for Windows* (C++11). 

Personal
----

These are mostly released experiments, but are geared towards personal use; as such, they may be of very limited use during development.

* [Cash-of-clans](https://github.com/r-lyeh/cash-of-clans) -- a free re-implementation of a working *game economy system*.
* [Codex](http://github.com/r-lyeh/codex) -- lightweight and simple C++ library to escape, unescape, read, write and convert from/to different *encoding charsets*.
* [Duty](http://github.com/r-lyeh/duty) -- lightweight *task manager* for parallel coroutines and serial jobs (C++11).
* [JPNG](http://github.com/r-lyeh/jpng) -- *jpg-with-alpha image format*. Repository provides specification and image conversion tools
* [LRU](https://github.com/r-lyeh/lru) -- lightweight *LRU cache structure* for list<T> and map<K,V> containers (C++11). 
* [RGB332 (tool)](http://github.com/r-lyeh/rgb332) -- custom uniform *RGB332 palette*.
* [Route66](https://github.com/r-lyeh/route66) -- lightweight *embeddable HTTP server* (C++11).
* [Sentry](http://github.com/r-lyeh/sentry) -- lightweight *data monitor* (C++11).
* [Signals](https://github.com/r-lyeh/signals) -- lightweight C++ API to deal with *digital signals*.
* [Variant](http://github.com/r-lyeh/variant) -- *varying* class that clones javascript behaviour as much as possible (C++11).
* [Test-allocators](https://github.com/r-lyeh/test-allocators) -- benchmark for different *memory allocators*.
* [Test-physics](https://github.com/r-lyeh/test-physics) -- benchmark for different *physics integrators*.

In Progress
----

Proof-of-concepts until stabilised, currently in active development.

* [Eve](https://github.com/r-lyeh/eve) -- *game engine* where graphics are low priority (C++11).
* [Frodo](https://github.com/r-lyeh/frodo) -- lightweight *ring based application framework* (C++11).
* [Watchmen](https://github.com/r-lyeh/watchmen) -- *asset dependency system* for games in run-time.
* [Play](https://github.com/r-lyeh/play) -- easy *alternative to scripting* in gameplay code.

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

* [Atlas](https://github.com/r-lyeh/atlas)
* [Blender](http://github.com/r-lyeh/blender)
* [Flow](https://github.com/r-lyeh/flow)
* [Gamebook](https://github.com/r-lyeh/gamebook)
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
* [Wake](https://github.com/r-lyeh/wake)
* [Cash](https://github.com/r-lyeh/cash)
* [Gate](https://github.com/r-lyeh/gate)
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
