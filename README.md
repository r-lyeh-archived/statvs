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
  - [Sand](http://github.com/r-lyeh/sand) -- lightweight and simple **time library** written in C++11 that provides interface for Unix stamps, hires timers, calendars, locales and tweening.
* Audio
  - [Wave](http://github.com/r-lyeh/wave) -- lightweight **3D sound wrapper** for OpenAL that supports OGG and MusePack decoding.
* Containers
  - [Oak](http://github.com/r-lyeh/oak) -- simple and lightweight **tree container**. Written in C++11. 
  - [Wire](http://github.com/r-lyeh/wire) -- C++ **std::string replacement** that features extended functionality, string interpolation and safe C/C++ formatters.
  - [Trie](http://github.com/r-lyeh/trie) -- lightweight and simple **autocompletion** data structure written in C++11.
  - [Unordered_map](http://github.com/r-lyeh/unordered_map) -- **portable header** for std::unordered_map<K,V> template.
* Compression
  - [Bundle](https://github.com/r-lyeh/bundle) -- lightweight C++ **compression library** that provides interface for ZIP, LZMA, LZIP, ZPAQ, LZ4 and SHOCO algorithms.
  - [Bundler](https://github.com/r-lyeh/bundler) -- command-line **compression tool**.
* Databases
  - [SQLight](http://github.com/r-lyeh/sqlight) -- lightweight **MySQL client** written in C++11. Based on code by Ladislav Nevery.
* Debug
  - [Heal](http://github.com/r-lyeh/heal) -- lightweight C++11 library to aid and **debug applications**.
  - [Tracey](http://github.com/r-lyeh/tracey) -- lightweight and simple C++ memory **leak finder** with no dependencies.
* Gameplay
  - [FSM](http://github.com/r-lyeh/fsm) -- lightweight C++11 Hierarchical/**Finite-State Machine** (H/FSM) class.
  - [Kult](https://github.com/r-lyeh/kult) -- lightweight **entity/component/system** library written in C++11.
  - [Live](http://github.com/r-lyeh/live) -- **automatic reloader** of variables in C++11, featuring type inference.
  - [Memo](http://github.com/r-lyeh/memo) -- simple and lightweight C++11 **factory class**, featuring automatic type casting.
* Hashing
  - [Cocoa](http://github.com/r-lyeh/cocoa) -- **hashing library** that provides interface for CRC32, CRC64, GCRC, RS, JS, PJW, ELF, BKDR, SBDM, DJB, DJB2, BP, FNV, AP, BJ1, MH2, SHA1, SFH.
  - [ID](http://github.com/r-lyeh/id) -- simple **compile-time hasher** and sequential ID generator. Written in C++11.
  - [Sole](http://github.com/r-lyeh/sole) -- lightweight C++11 library to generate universally **unique identificators** (UUID) both v1 and v4.
* Input
  - [Hyde](http://github.com/r-lyeh/hyde) -- lightweight and simple Human **Inferface Device** (HID) C++ library. 
* I/O
  - [Apathy](http://github.com/r-lyeh/apathy) -- lightweight **stream/file/mmap/path/virtual-filesystem** IO C++11 library.
  - [Base91x](http://github.com/r-lyeh/base91x) Base91x -- lightweight **binary-to-text encoder** and decoder written in C++ that features 19% to 10% less overhead than base64. 
  - [Knot](http://github.com/r-lyeh/knot) -- lightweight and simple **TCP networking** C++ library.
  - [Giant](http://github.com/r-lyeh/giant) -- tiny C++11 library to **handle little/big endianness**.
* Render
  - [Dot](http://github.com/r-lyeh/dot) -- simple and lightweight RGBA/HSLA library that support **WebP, JPG, progressive JPG, SVG, PNG, TGA, BMP, PSD, GIF, HDR and PIC images**.
* Security
  - [Auth](http://github.com/r-lyeh/auth) -- simple, lightweight and safe client-server **authentication system**. Written in C++.
  - [Vault](http://github.com/r-lyeh/vault) -- lightweight and simple **crypt library** that provides interface for ARC4. Written in C++.
* Serialization
  - [Medea (spec+lib)](http://github.com/r-lyeh/medea) -- lightweight and **tiny serializer** written in C++11. In mythology, also Jason's wife. 
* Specifications
  - [ARYA](http://github.com/r-lyeh/ARYA) -- CC0 **asset naming convention**. 
  - [JXML](http://github.com/r-lyeh/JXML) -- loss-less representation of **JSON in XML** that is based on [JSONx](http://goo.gl/I3cxs). 
  - [JXMLex](http://github.com/r-lyeh/JXMLex) is an expressive and relatively small representation of **JSON in XML** that is based on [JSONx](http://goo.gl/I3cxs) and [JXML](http://github.com/r-lyeh/JXML).
* Unit-testing
  - [Dessert](http://github.com/r-lyeh/dessert) -- lightweight and simple C++11 **test framework**.
* User Interface
  - [Bubble](https://github.com/r-lyeh/bubble) -- simple and lightweight C++11 **dialog library for Windows** 

Personal or recent
----

These are mostly released experiments, but are geared towards personal use; as such, they may be buggy or be of very limited use during development.

* [Codex](http://github.com/r-lyeh/codex) -- lightweight and simple C++ library to escape, unescape, read, write and convert from/to different **encoding charsets**.
* [Duty](http://github.com/r-lyeh/duty) -- lightweight C++11 **task manager** for parallel coroutines and serial jobs.
* [JPNG](http://github.com/r-lyeh/jpng) -- **jpg-with-alpha image format**. Repository provides specification and image conversion tools
* [LRU](https://github.com/r-lyeh/lru) -- lightweight **LRU cache structure** for list<T> and map<K,V> containers. Written in C++11 
* [RGB332 (tool)](http://github.com/r-lyeh/rgb332) -- custom uniform **RGB332 palette**.
* [Route66](https://github.com/r-lyeh/route66) -- lightweight **embeddable HTTP server** written in C++11.
* [Sentry](http://github.com/r-lyeh/sentry) -- lightweight **data monitor** written in C++11.
* [Variant](http://github.com/r-lyeh/variant) -- **varying** C++11 class that clones javascript behaviour as much as possible.

In Progress
----

Very buggy, currently in active development.

* [Eve](https://github.com/r-lyeh/eve) -- **game engine** where graphics are low priority. Written in C++11
* [Frodo](https://github.com/r-lyeh/frodo) -- lightweight **ring based application framework**. Written in C++11.
* [Watchmen](https://github.com/r-lyeh/watchmen) -- **asset dependency system** for games in run-time.
* [Play](https://github.com/r-lyeh/play) -- easy **alternative to scripting** in gameplay code.

Contributing
----

Projects in collaboration with other coders.

* [jsonxx](http://github.com/hjiang/jsonxx) -- lightweight **JSON parser** written in C++.
* [IMGUI](http://github.com/r-lyeh/imgui) -- OpenGL 2/3 **Immediate Mode GUI** toolkit.

On Hold
----

Each of these projects are suffering from an existential crisis.

* [Fontbase](http://github.com/r-lyeh/fontbase) -- collection of **western, CJK and iconographic fonts** free for commercial usage.
* [Stringbase](http://github.com/r-lyeh/stringbase) -- collaborative effort aimed to **translate common texts** found in videogames and regular apps. 

Planned
----

Yet to be committed, removed and/or finished. Someday.

* [Atlas](https://github.com/r-lyeh/atlas)
* [Blender](http://github.com/r-lyeh/blender)
* [Gamebook](https://github.com/r-lyeh/gamebook)
* [Geohash](https://github.com/r-lyeh/geohash)
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

* [Moon9](https://github.com/r-lyeh/moon9) -- old engine
* [Wood](https://github.com/r-lyeh/wood) -- old tree structure

End of experiment
----

I am pretty done with this stuff. Moving on.

* [Cash-of-clans](https://github.com/r-lyeh/cash-of-clans) -- a free re-implementation of a working **game economy system**.
* [Test-allocators](https://github.com/r-lyeh/test-allocators) -- benchmark for different **memory allocators**.
* [Test-physics](https://github.com/r-lyeh/test-physics) -- benchmark for different **physics integrators**.

Resume
---

For completeness.

* [Vitae](http://github.com/r-lyeh/vitae) -- my self-compilable **C++ resume**
