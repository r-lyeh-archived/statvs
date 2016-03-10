status
======

[![Join the chat at https://gitter.im/r-lyeh/status](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/r-lyeh/status?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

My name is r-lyeh and I code videogames :neckbeard:

This repo is meant to be a semi-conclusive list of projects in which the author is / has participated in.

- The tools below are Public Domain.
- The specifications below are Public Domain (or CC0 licensed), written in Markdown.
- The libraries below are Public Domain (or _ZLIB/LibPNG licensed_), written in C++.
- Most of my source code is (where possible) _cross-platform_, _header-only_ and _self-contained_, and have been used in _commercial games_. It is therefore pretty much battle-tested, but use it at your own risk. No warranties provided.
- Extension convention: `.md` for documents, `.hpp/.cpp` for sources, `.cc` for samples and `.cxx` for tests and benchmarks.

## Released
Fully released / tested; more features may be incoming, but these are considered to be in a 'stable' state.

Tags|Repository
:----------------:|:------------
io|[Apathy (C++03)](http://github.com/r-lyeh/apathy) <a href="https://travis-ci.org/r-lyeh/apathy"><img src="https://api.travis-ci.org/r-lyeh/apathy.svg?branch=master" align="right" /></a> <br/> lightweight *path/file/mstream/mmap IO library*.
debug|[Assume (C++03)](http://github.com/r-lyeh/assume) <a href="https://travis-ci.org/r-lyeh/assume"><img src="https://api.travis-ci.org/r-lyeh/assume.svg?branch=master" align="right" /></a> <br/> smarter *assert replacement* for LHS/RHS values.
tool, image|[Attila (Win32) :star2:](https://github.com/r-lyeh/attila) <a href="https://travis-ci.org/r-lyeh/attila"><img src="https://api.travis-ci.org/r-lyeh/attila.svg?branch=master" align="right" /></a> <br/> tiny *atlas texture/image packer tool*.
security|[Auth (C++03)](http://github.com/r-lyeh/auth) <a href="https://travis-ci.org/r-lyeh/auth"><img src="https://api.travis-ci.org/r-lyeh/auth.svg?branch=master" align="right" /></a> <br/> simple, lightweight and safe client-server *authentication system*.
encoding|[Base91 (C++03)](http://github.com/r-lyeh/base91) <a href="https://travis-ci.org/r-lyeh/base91"><img src="https://api.travis-ci.org/r-lyeh/base91.svg?branch=master" align="right" /></a> <br/> *tighter-than-Base64 encoder*, still XML and JSON friendly.
serial|[Bourne (C++11)](http://github.com/r-lyeh/bourne) <a href="https://travis-ci.org/r-lyeh/bourne"><img src="https://api.travis-ci.org/r-lyeh/bourne.svg?branch=master" align="right" /></a> <br/> lightweight *JSON de/serializer*.
user-interface|[Bubble (C++11)](https://github.com/r-lyeh/bubble) <br/> simple and lightweight *dialog library for Windows*.
compression|[Bundle (C++03,C++11):star2:](https://github.com/r-lyeh/bundle) <a href="https://travis-ci.org/r-lyeh/bundle"><img src="https://api.travis-ci.org/r-lyeh/bundle.svg?branch=master" align="right" /></a> <br/> an embeddable *compression library* that supports 23 algorithms and 2 archivers.
compression,tool|[Bundler (Win32,OSX)](https://github.com/r-lyeh/bundler) <br/> *command-line archiver* that supports 23 compression algorithms.
data-structures|[Burg (C++11)](https://github.com/r-lyeh/burg) <a href="https://travis-ci.org/r-lyeh/burg"><img src="https://api.travis-ci.org/r-lyeh/burg.svg?branch=master" align="right" /></a> <br/> simple burg *linear predictor*.
hashing|[Cocoa (C++11):star2:](http://github.com/r-lyeh/cocoa) <a href="https://travis-ci.org/r-lyeh/cocoa"><img src="https://api.travis-ci.org/r-lyeh/cocoa.svg?branch=master" align="right" /></a> <br/> *hashing library* that provides interface for CRC32, CRC64, GCRC, RS, JS, PJW, ELF, BKDR, SBDM, DJB, DJB2, BP, FNV, AP, BJ1, MH2, SHA1, SFH.
encoding|[Collage (C++03)](https://github.com/r-lyeh/collage) <a href="https://travis-ci.org/r-lyeh/collage"><img src="https://api.travis-ci.org/r-lyeh/collage.svg?branch=master" align="right" /></a> <br/> lightweight library to *diff and patch* arbitrary data.
unit-testing|[Dessert (C++11):star2:](http://github.com/r-lyeh/dessert) <a href="https://travis-ci.org/r-lyeh/dessert"><img src="https://api.travis-ci.org/r-lyeh/dessert.svg?branch=master" align="right" /></a> <br/> lightweight *unit-testing framework*.
debug|[Dollar (C++11)](https://github.com/r-lyeh/dollar) <a href="https://goo.gl/nR594V"><img src="https://goo.gl/OtOjg4" align="right" /></a> <br> portable/generic *CPU profiler* with chrome://tracing support.
debug|[DrEcho (C++11)](http://github.com/r-lyeh/DrEcho) <a href="https://travis-ci.org/r-lyeh/DrEcho"><img src="https://api.travis-ci.org/r-lyeh/DrEcho.svg?branch=master" align="right" /></a> <br/> DrEcho *spices your terminal up*.
gameplay|[Flare (C++03)](https://github.com/r-lyeh/flare) <a href="https://travis-ci.org/r-lyeh/flare"><img src="https://api.travis-ci.org/r-lyeh/flare.svg?branch=master" align="right" /></a> <br/> lightweight C++ API to deal with *digital signals/logical buttons*.
network|[Flow (C++11)](https://github.com/r-lyeh/flow) <a href="https://travis-ci.org/r-lyeh/flow"><img src="https://api.travis-ci.org/r-lyeh/flow.svg?branch=master" align="right" /></a> <br/> lightweight network downloader with native fallbacks aimed to gamedev.
gameplay|[Frodo (C++11)](https://github.com/r-lyeh/frodo) <a href="https://travis-ci.org/r-lyeh/frodo"><img src="https://api.travis-ci.org/r-lyeh/frodo.svg?branch=master" align="right" /></a> <br/> lightweight *ring dependency framework*.
gameplay|[FSM (C++11)](http://github.com/r-lyeh/fsm) <a href="https://travis-ci.org/r-lyeh/fsm"><img src="https://api.travis-ci.org/r-lyeh/fsm.svg?branch=master" align="right" /></a> <br/> lightweight Hierarchical/*Finite-State Machine* (H/FSM) class.
design|[Gamebook (Markdown)](https://github.com/r-lyeh/gamebook) <br/> unified *game design document*.
io|[Giant (C++11)](http://github.com/r-lyeh/giant) <a href="https://travis-ci.org/r-lyeh/giant"><img src="https://api.travis-ci.org/r-lyeh/giant.svg?branch=master" align="right" /></a> <br/> tiny library to *handle little/big endianness*.
debug|[Heal (C++03)](http://github.com/r-lyeh/heal) <a href="https://travis-ci.org/r-lyeh/heal"><img src="https://api.travis-ci.org/r-lyeh/heal.svg?branch=master" align="right" /></a> <br/> lightweight library to aid and *debug applications*.
render|[Hertz (C++11)](https://github.com/r-lyeh/Hertz)<a href="https://travis-ci.org/r-lyeh/Hertz"><img src="https://api.travis-ci.org/r-lyeh/hertz.svg?branch=master" align="right" /></a> <br/> simple *framerate locker*.
input|[Hyde (C++03)](http://github.com/r-lyeh/hyde) <br/> lightweight and simple Human *Inferface Device* (HID) library.
hashing|[ID (C++11)](http://github.com/r-lyeh/id) <a href="https://travis-ci.org/r-lyeh/id"><img src="https://api.travis-ci.org/r-lyeh/id.svg?branch=master" align="right" /></a> <br/> simple *compile-time hasher* and sequential ID generator.
mesh, tool|[Img2Sky (Win32)](http://github.com/r-lyeh/img2sky) <br/> *vertex-color mesh builder tool* for skyboxes and static geometry.
io|[Journey (C++11)](http://github.com/r-lyeh/journey) <a href="https://travis-ci.org/r-lyeh/journey"><img src="https://api.travis-ci.org/r-lyeh/journey.svg?branch=master" align="right" /></a> <br/> lightweight *append-only, header-less, journaling file format*.
spec|[JXML](http://github.com/r-lyeh/JXML) <br/> loss-less representation of *JSON in XML*.
spec|[JXMLex](http://github.com/r-lyeh/JXMLex) <br/> expressive representation of *JSON in XML*.
network|[Knot (C++03)](http://github.com/r-lyeh/knot) <a href="https://travis-ci.org/r-lyeh/knot"><img src="https://api.travis-ci.org/r-lyeh/knot.svg?branch=master" align="right" /></a> <br/> lightweight and simple *TCP networking* C++ library.
gameplay|[Kult (C++11):star2:](https://github.com/r-lyeh/kult) <a href="https://travis-ci.org/r-lyeh/kult"><img src="https://api.travis-ci.org/r-lyeh/kult.svg?branch=master" align="right" /></a> <br/> lightweight *entity/component/system* library.
gameplay|[Live (C++11)](http://github.com/r-lyeh/live) <a href="https://travis-ci.org/r-lyeh/live"><img src="https://api.travis-ci.org/r-lyeh/live.svg?branch=master" align="right" /></a> <br/> *automatic reloader* of variables, featuring type inference.
data-structures|[LRU (C++11)](https://github.com/r-lyeh/lru) <a href="https://travis-ci.org/r-lyeh/LRU"><img src="https://api.travis-ci.org/r-lyeh/LRU.svg?branch=master" align="right" /></a> <br/> lightweight *LRU cache structure* for list<T> and map<K,V> containers.
gameplay|[Memo (C++11)](http://github.com/r-lyeh/memo) <a href="https://travis-ci.org/r-lyeh/memo"><img src="https://api.travis-ci.org/r-lyeh/memo.svg?branch=master" align="right" /></a> <br/> simple and lightweight *factory class*, featuring automatic type casting.
stats|[Metrics (C++11)](https://github.com/r-lyeh/metrics) <a href="https://goo.gl/l0C5wv"><img src="https://goo.gl/bn24Kq" align="right" /></a> <br/> table metrics w/ benchmarking, unit conversions in CSV,TSV,ASCII,markdown.
io|[mINI (C++11)](https://github.com/r-lyeh/mINI)<a href="https://travis-ci.org/r-lyeh/mINI"><img src="https://api.travis-ci.org/r-lyeh/mINI.svg?branch=master" align="right" /></a> <br/> very minimal *.INI reader/writer*.
data-structures|[Oak (C++03)](http://github.com/r-lyeh/oak) <a href="https://goo.gl/l2IoOI"><img src="https://goo.gl/8YevhJ" align="right" /></a> <br/> simple and lightweight *tree container*.
design|[Pitch (Markdown)](https://github.com/r-lyeh/pitch) <br/> forkable game *pitch template*.
spec,tool,image|[Pug](https://github.com/r-lyeh/pug) <br/> *pug, png with a twist*: lossy image format.
network|[Route66 (C++03)](https://github.com/r-lyeh/route66) <a href="https://goo.gl/rE1dM1"><img src="https://goo.gl/TD7UpH" align="right" /></a> <br/> lightweight *embeddable HTTP server*.
io|[Quant (C++03)](https://github.com/r-lyeh/quant) <a href="https://goo.gl/gSHXKv"><img src="https://goo.gl/Kuv8pn" align="right" /></a> <br/> *quantization suite* to/from half-floats, s/unorm bytes, quats and vec3s.
time|[Sand (C++11)](http://github.com/r-lyeh/sand) <a href="https://travis-ci.org/r-lyeh/sand"><img src="https://api.travis-ci.org/r-lyeh/sand.svg?branch=master" align="right" /></a> <br/> lightweight *timer controller*.
script|[Scriptorium:star:](https://github.com/r-lyeh/scriptorium) <br/> Game *Scripting Languages benchmarked*.
data|[Sentry (C++11)](https://github.com/r-lyeh/sentry) <a href="https://travis-ci.org/r-lyeh/sentry"><img src="https://api.travis-ci.org/r-lyeh/sentry.svg?branch=master" align="right" /></a> <br/> lightweight *data monitor*.
hashing|[Sole (C++11):star2:](http://github.com/r-lyeh/sole) <a href="https://travis-ci.org/r-lyeh/sole"><img src="https://api.travis-ci.org/r-lyeh/sole.svg?branch=master" align="right" /></a> <br/> lightweight library to generate universally *unique identificators* (UUID) both v1 and v4.
image|[Spot (C++11):star2:](http://github.com/r-lyeh/spot) <a href="https://travis-ci.org/r-lyeh/spot"><img src="https://api.travis-ci.org/r-lyeh/spot.svg?branch=master" align="right" /></a> <br/> compact and embeddable RGBA/HSLA library that supports *WEBP, JPG, progressive JPG, PNG, TGA, DDS DXT1/2/3/4/5, BMP, PSD, GIF, PVR2/3 (ETC1/PVRTC), KTX (ETC1/PVRTC), PKM (ETC1), HDR, PIC, PNM (PPM/PGM), CRN, PUG, FLIF, EXR and vectorial SVG files*.
databases |[SQLight (C++11)](http://github.com/r-lyeh/sqlight) <a href="https://travis-ci.org/r-lyeh/sqlight"><img src="https://api.travis-ci.org/r-lyeh/sqlight.svg?branch=master" align="right" /></a> <br/> lightweight *MySQL client*.
debug|[Tracey (C++11):star2:](http://github.com/r-lyeh/tracey) <a href="https://travis-ci.org/r-lyeh/tracey"><img src="https://api.travis-ci.org/r-lyeh/tracey.svg?branch=master" align="right" /></a> <br/> lightweight and simple C++ memory *leak finder* with no dependencies.
data-structures|[Trie (C++11)](http://github.com/r-lyeh/trie) <a href="https://travis-ci.org/r-lyeh/trie"><img src="https://api.travis-ci.org/r-lyeh/trie.svg?branch=master" align="right" /></a> <br/> lightweight and simple *autocompletion* data structure.
animation |[Tween (C++03)](https://github.com/r-lyeh/tween) <a href="https://travis-ci.org/r-lyeh/tween"><img src="https://api.travis-ci.org/r-lyeh/tween.svg?branch=master" align="right" /></a> <br/> lightweight *easing library*.
data-structures|[Unordered_map (C++11)](http://github.com/r-lyeh/unordered_map) <a href="https://travis-ci.org/r-lyeh/unordered_map"><img src="https://api.travis-ci.org/r-lyeh/unordered_map.svg?branch=master" align="right" /></a> <br/> *portable header* for std::unordered_map<K,V> template.
debug|[Unifont (C++11)](http://github.com/r-lyeh/unifont) <a href="https://travis-ci.org/r-lyeh/unifont"><img src="https://api.travis-ci.org/r-lyeh/unifont.svg?branch=master" align="right" /></a> <br/> *embeddable console 1bpp font*.
spec, io|[Unify (C++11)](http://github.com/r-lyeh/Unify) <a href="https://travis-ci.org/r-lyeh/unify"><img src="https://api.travis-ci.org/r-lyeh/unify.svg?branch=master" align="right" /></a> <br/> a function to *normalize resouce identificators*.
security|[Vault (C++03)](http://github.com/r-lyeh/vault) <a href="https://travis-ci.org/r-lyeh/vault"><img src="https://api.travis-ci.org/r-lyeh/vault.svg?branch=master" align="right" /></a> <br/> lightweight and simple *crypt library* that provides interface for ARC4.
network|[VLE (C99, C++03)](https://github.com/r-lyeh/vle) <a href="https://travis-ci.org/r-lyeh/vle"><img src="https://api.travis-ci.org/r-lyeh/vle.svg?branch=master" align="right" /></a> <br/> simple *variable-length encoder/decoder*.
audio|[Wave (C++11)](http://github.com/r-lyeh/wave) <br/> lightweight *3D sound wrapper* for OpenAL that supports OGG and MusePack decoding.
utils|[Warp (C++11):star2:](http://github.com/r-lyeh/warp) <a href="https://travis-ci.org/r-lyeh/warp"><img src="https://api.travis-ci.org/r-lyeh/warp.svg?branch=master" align="right" /></a> <br/> a handy *string interpolator*.
data-structures|[Wire (C++11):star2:](http://github.com/r-lyeh/wire) <a href="https://travis-ci.org/r-lyeh/wire"><img src="https://api.travis-ci.org/r-lyeh/wire.svg?branch=master" align="right" /></a> <br/> a drop-in *std::string replacement* with extended functionality and safe C/C++ formatters.

## Contributions
Forked projects or in collaboration with other coders.

* [jsonxx](http://github.com/hjiang/jsonxx) -- lightweight *JSON parser* written in C++.
* [IMGUI](http://github.com/r-lyeh/imgui) -- OpenGL 2/3 *Immediate Mode GUI* toolkit.
* [units](http://github.com/r-lyeh/units) -- numerical quantities with units (C++03).
* [unlzma](http://github.com/r-lyeh/unlzma) -- A very compact LZMA decoder (C++03).
* [eval](http://github.com/r-lyeh/eval) -- very simple expression evaluator using shunting-yard algorithm and RPN (C++11).

## Personal
These are mostly released experiments, but are geared towards personal use; as such, they may be of very limited use during development.

* [Bridge](https://github.com/r-lyeh/bridge) -- a standard C++/boost *compatibility layer*, plus a few utils (C++11/C++03).
* [Cash-of-clans](https://github.com/r-lyeh/cash-of-clans) -- a free re-implementation of a working *game economy system*.
* [Crawler](https://github.com/r-lyeh/crawler) -- a quick prototiping platform for Windows (C++11).
* [CLDR](https://github.com/r-lyeh/cldr) -- compact data from the Unicode Common Locale Data Repository.
* [Codex](https://github.com/r-lyeh/codex) -- lightweight and simple C++ library to escape, unescape, read, write and convert from/to different *encoding charsets*.
* [Duty](https://github.com/r-lyeh/duty) -- lightweight *task manager* for parallel coroutines and serial jobs (C++11).
* [Emojis](https://github.com/r-lyeh/emojis) -- emojis, atlased and indexed.
* [RGB332 (tool)](https://github.com/r-lyeh/rgb332) -- custom uniform *RGB332 palette*.
* [Variant](https://github.com/r-lyeh/variant) -- *varying* class that clones javascript behaviour as much as possible (C++11).
* [Malloc-survey](https://github.com/r-lyeh/malloc-survey) -- benchmark for different *memory allocators*.
* [Test-physics](https://github.com/r-lyeh/test-physics) -- benchmark for different *physics integrators*.

## In Progress
Proof-of-concepts until stabilised, currently in mid/active development.

* [EDGE](https://github.com/r-lyeh/EDGE) -- tiny *3D game engine* in C++, with C and Lua interfaces. Written in 32 days.
* [Jabba](https://github.com/r-lyeh/jabba) -- (C++11).
* [Play](https://github.com/r-lyeh/play) -- easy *alternative to scripting* in gameplay code.
* [Solace](https://github.com/r-lyeh/solace) -- modern *console replacement*.
* [Wake](https://github.com/r-lyeh/wake) -- a no-brainer *asset build system*. Designed for zombies.
* [Watchmen](https://github.com/r-lyeh/watchmen) -- *asset dependency system* for games in run-time.
* [Juice]() --
* [Graybox]() --
* [Drop]() --
* [Checklist]() --

## Planned
Yet to be committed, removed and/or finished. Someday.

* [Blender](http://github.com/r-lyeh/blender)
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

## On Hold / Abandoned
These are either fully abandoned, or are suffering from an existential crisis.

* [FortFont](http://github.com/r-lyeh/fortfont) -- collection of *western, CJK and iconographic fonts* free for commercial usage.
* [Eve](https://github.com/r-lyeh/eve) -- deprecated game engine where graphics are low priority (C++11).
* [Moon9](https://github.com/r-lyeh/moon9) -- old game engine.
* [Stringbase](http://github.com/r-lyeh/stringbase) -- collaborative effort aimed to *translate common texts* found in videogames and regular apps.
* [Wood](https://github.com/r-lyeh/wood) -- old tree data structure.

## Resume
For completeness.

* [Vitae](http://github.com/r-lyeh/vitae) -- my self-compilable *C++ resume*.
