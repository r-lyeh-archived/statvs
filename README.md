status
======

My name is r-lyeh and I code videogames :neckbeard:

This repo is meant to be a semi-conclusive list of projects in which the author is / has participated in.

A few notes:

- Many of my libraries have been used in _commercial games_. They are, or should be, battle-tested.
- Most of my libraries are _cross-platform_, have _no external dependencies_ and are _header-only_ wherever possible.
- All my libraries are _BOOST licensed_ (~MIT equivalent with no attribution required in binary distributions).
- I follow this convention: `.hpp/.cpp` for libraries, `.cc` for samples, `.cxx` for tests and benchmarks.

Released
----

Fully released / tested; more features may be incoming, but these are considered to be in a 'stable' state.

* **Animation**
  - [Tween](https://github.com/r-lyeh/tween) -- lightweight *easing library* (C++03).
* **Audio**
  - [Wave](http://github.com/r-lyeh/wave) -- lightweight *3D sound wrapper* for OpenAL that supports OGG and MusePack decoding.
* **Compression**
  - [Bundle](https://github.com/r-lyeh/bundle) -- an embeddable *compression* library that supports ZIP, LZMA, LZIP, ZPAQ, LZ4, ZSTD, BROTLI and SHOCO (C++03)(C++11). :star2:
  - [Bundler](https://github.com/r-lyeh/bundler) -- command-line *compression tool*.
* **Databases**
  - [SQLight](http://github.com/r-lyeh/sqlight) -- lightweight *MySQL client* (C++11).
* **Data structures**
  - [LRU](https://github.com/r-lyeh/lru) -- lightweight *LRU cache structure* for list<T> and map<K,V> containers (C++11). 
  - [Oak](http://github.com/r-lyeh/oak) -- simple and lightweight *tree container* (C++03). 
  - [Trie](http://github.com/r-lyeh/trie) -- lightweight and simple *autocompletion* data structure (C++11).
  - [Unordered_map](http://github.com/r-lyeh/unordered_map) -- *portable header* for std::unordered_map<K,V> template.
  - [Wire](http://github.com/r-lyeh/wire) -- a drop-in *std::string replacement* with extended functionality, string interpolation and safe C/C++ formatters (C++03). :star2:
* **Debug**
  - [Assert++](http://github.com/r-lyeh/assert) -- a smart *assert replacement* for LHS/RHS values (C++03).
  - [Heal](http://github.com/r-lyeh/heal) -- lightweight library to aid and *debug applications* (C++03).
  - [Tracey](http://github.com/r-lyeh/tracey) -- lightweight and simple C++ memory *leak finder* with no dependencies. :star2:
* **Encoding**
  - [Base91x](http://github.com/r-lyeh/base91x) -- lightweight *binary-to-text encoder/decoder* smaller than base64 (C++03). 
  - [Collage](https://github.com/r-lyeh/collage) -- lightweight library to *diff and patch* arbitrary data (C++03).
* **Gameplay**
  - [Flare](https://github.com/r-lyeh/flare) -- lightweight C++ API to deal with *digital signals/logical buttons* (C++03).
  - [Frodo](https://github.com/r-lyeh/frodo) -- lightweight *ring dependency framework* (C++11).
  - [FSM](http://github.com/r-lyeh/fsm) -- lightweight Hierarchical/*Finite-State Machine* (H/FSM) class (C++11).
  - [Kult](https://github.com/r-lyeh/kult) -- lightweight *entity/component/system* library (C++11). :star2:
  - [Live](http://github.com/r-lyeh/live) -- *automatic reloader* of variables, featuring type inference (C++11).
  - [Memo](http://github.com/r-lyeh/memo) -- simple and lightweight *factory class*, featuring automatic type casting (C++11).
* **Hashing**
  - [Cocoa](http://github.com/r-lyeh/cocoa) -- *hashing library* that provides interface for CRC32, CRC64, GCRC, RS, JS, PJW, ELF, BKDR, SBDM, DJB, DJB2, BP, FNV, AP, BJ1, MH2, SHA1, SFH (C++11). :star2:
  - [ID](http://github.com/r-lyeh/id) -- simple *compile-time hasher* and sequential ID generator (C++11).
  - [Sole](http://github.com/r-lyeh/sole) -- lightweight library to generate universally *unique identificators* (UUID) both v1 and v4 (C++11). :star2:
* **Image**
  - [Pug](https://github.com/r-lyeh/pug) -- *PNG with a twist*: lossy diffuse and lossless alpha image format (spec/tools)
  - [Spot](http://github.com/r-lyeh/spot) -- compact and embeddable RGBA/HSLA library that supports *WebP, JPG, progressive JPG, PNG, TGA, DDS DXT1/2/3/4/5, BMP, PSD, GIF, PKM (ETC1), PVR (PVRTC), HDR, PIC and vectorial SVG files*. (C++03). :star2:
* **Input**
  - [Hyde](http://github.com/r-lyeh/hyde) -- lightweight and simple Human *Inferface Device* (HID) library (C++03). 
* **I/O**
  - [Apathy](http://github.com/r-lyeh/apathy) -- lightweight *stream/file/mmap/path/virtual-filesystem* IO library (C++11).
  - [Giant](http://github.com/r-lyeh/giant) -- tiny library to *handle little/big endianness* (C++11).
* **Network**
  - [Flow](https://github.com/r-lyeh/flow) -- lightweight network downloader with native fallbacks aimed to gamedev (C++11).
  - [Knot](http://github.com/r-lyeh/knot) -- lightweight and simple *TCP networking* C++ library (C++03).
  - [Route66](https://github.com/r-lyeh/route66) -- lightweight *embeddable HTTP server* (C++03).
* **Security**
  - [Auth](http://github.com/r-lyeh/auth) -- simple, lightweight and safe client-server *authentication system* (C++).
  - [Vault](http://github.com/r-lyeh/vault) -- lightweight and simple *crypt library* that provides interface for ARC4 (C++03).
* **Serialization**
  - [Medea (spec+lib)](http://github.com/r-lyeh/medea) -- lightweight and *tiny serializer*. In mythology, also Jason's wife (C++11).
* **Specifications**
  - [ARYA](http://github.com/r-lyeh/ARYA) -- CC0 *asset naming convention*. 
  - [JXML](http://github.com/r-lyeh/JXML) -- loss-less representation of *JSON in XML* that is based on [JSONx](http://goo.gl/I3cxs). 
  - [JXMLex](http://github.com/r-lyeh/JXMLex) -- expressive representation of *JSON in XML* that is based on [JSONx](http://goo.gl/I3cxs) and [JXML](http://github.com/r-lyeh/JXML).
* **Time**
  - [Sand](http://github.com/r-lyeh/sand) -- lightweight and simple *time library* that provides interface for Unix stamps, hires timers, calendars and locales (C++11).
* **Unit-testing**
  - [Dessert](http://github.com/r-lyeh/dessert) -- lightweight *unit-testing framework* (C++11). :star2:
* **User Interface**
  - [Bubble](https://github.com/r-lyeh/bubble) -- simple and lightweight *dialog library for Windows* (C++11). 

Personal
----

These are mostly released experiments, but are geared towards personal use; as such, they may be of very limited use during development.

* [Burg](https://github.com/r-lyeh/burg) -- a simple burg linear predictor (C++11).
* [Bridge](https://github.com/r-lyeh/bridge) -- a standard C++/boost *compatibility layer*, plus a few utils (C++11/C++03).
* [Cash-of-clans](https://github.com/r-lyeh/cash-of-clans) -- a free re-implementation of a working *game economy system*.
* [Codex](https://github.com/r-lyeh/codex) -- lightweight and simple C++ library to escape, unescape, read, write and convert from/to different *encoding charsets*.
* [DrEcho](https://github.com/r-lyeh/DrEcho) -- DrEcho *spices your terminal up* (C++11).
* [Duty](https://github.com/r-lyeh/duty) -- lightweight *task manager* for parallel coroutines and serial jobs (C++11).
* [Pitch](https://github.com/r-lyeh/pitch) -- game *template pitch*.
* [RGB332 (tool)](https://github.com/r-lyeh/rgb332) -- custom uniform *RGB332 palette*.
* [Sentry](https://github.com/r-lyeh/sentry) -- lightweight *data monitor* (C++11).
* [Variant](https://github.com/r-lyeh/variant) -- *varying* class that clones javascript behaviour as much as possible (C++11).
* [VLE](https://github.com/r-lyeh/vle) -- simple *variable-length encoder/decoder* (C99)(C++03).
* [Test-allocators](https://github.com/r-lyeh/test-allocators) -- benchmark for different *memory allocators*.
* [Test-physics](https://github.com/r-lyeh/test-physics) -- benchmark for different *physics integrators*.

In Progress
----

Proof-of-concepts until stabilised, currently in active development.

* [Attila](https://github.com/r-lyeh/attila) -- Simple and lightweight *atlas texture/image packer*.
* [Gamebook](https://github.com/r-lyeh/gamebook)
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
