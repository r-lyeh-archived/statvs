status
======

[![Join the chat at DiscordApp](https://img.shields.io/badge/discord-support-blue.svg)](https://discord.gg/vu6Vt9d)

My name is r-lyeh and I code videogames :neckbeard:

This repo is meant to be a semi-conclusive list of projects in which the author is / has participated in.

- The list below is archived. A newer list can be [found here](https://github.com/r-lyeh/statvs).
- The tools below are Public Domain.
- The specifications below are Public Domain (or CC0 licensed), written in Markdown.
- The libraries below are Public Domain (or _ZLIB/LibPNG licensed_), written in C++.
- Most of my source code is (where possible) _cross-platform_, _header-only_ and _self-contained_, and have been used in _commercial games_. It is therefore pretty much battle-tested, but use it at your own risk. No warranties provided.
- Extension convention: `.md` for documents, `.hpp/.cpp` for sources, `.cc` for samples and `.cxx` for tests and benchmarks.

## Released
Fully released / tested; more features may be incoming, but these are considered to be in a 'stable' state.

Tags|Repository
:----------------:|:------------
io|[Apathy (C++03)](http://github.com/r-lyeh/apathy) <a href="https://travis-ci.org/r-lyeh-archived/apathy"><img src="https://api.travis-ci.org/r-lyeh-archived/apathy.svg?branch=master" align="right" /></a> <br/> lightweight *path/file/mstream/mmap IO library*.
debug|[Assume (C++03)](http://github.com/r-lyeh/assume) <a href="https://travis-ci.org/r-lyeh-archived/assume"><img src="https://api.travis-ci.org/r-lyeh-archived/assume.svg?branch=master" align="right" /></a> <br/> smarter *assert replacement* for LHS/RHS values.
tool, image|[Attila (Win32) :star2:](https://github.com/r-lyeh/attila) <a href="https://travis-ci.org/r-lyeh-archived/attila"><img src="https://api.travis-ci.org/r-lyeh-archived/attila.svg?branch=master" align="right" /></a> <br/> tiny *atlas texture/image packer tool*.
security|[Auth (C++03)](http://github.com/r-lyeh/auth) <a href="https://travis-ci.org/r-lyeh-archived/auth"><img src="https://api.travis-ci.org/r-lyeh-archived/auth.svg?branch=master" align="right" /></a> <br/> simple, lightweight and safe client-server *authentication system*.
encoding|[Base (C++03)](http://github.com/r-lyeh/base) <a href="https://travis-ci.org/r-lyeh-archived/base"><img src="https://api.travis-ci.org/r-lyeh-archived/base.svg?branch=master" align="right" /></a> <br/> *base91/base85/base64* de/encoders.
serial|[Bourne (C++11)](http://github.com/r-lyeh/bourne) <a href="https://travis-ci.org/r-lyeh-archived/bourne"><img src="https://api.travis-ci.org/r-lyeh-archived/bourne.svg?branch=master" align="right" /></a> <br/> lightweight *JSON de/serializer*.
user-interface|[Bubble (C++11)](https://github.com/r-lyeh/bubble) <br/> simple and lightweight *dialog library for Windows*.
compression|[Bundle (C++03,C++11):star2:](https://github.com/r-lyeh/bundle) <a href="https://travis-ci.org/r-lyeh-archived/bundle"><img src="https://api.travis-ci.org/r-lyeh-archived/bundle.svg?branch=master" align="right" /></a> <br/> an embeddable *compression library* that supports 23 algorithms and 2 archivers.
compression,tool|[Bundler (Win32,OSX)](https://github.com/r-lyeh/bundler) <br/> *command-line archiver* that supports 23 compression algorithms.
data-structures|[Burg (C++11)](https://github.com/r-lyeh/burg) <a href="https://travis-ci.org/r-lyeh-archived/burg"><img src="https://api.travis-ci.org/r-lyeh-archived/burg.svg?branch=master" align="right" /></a> <br/> simple burg *linear predictor*.
hashing|[Cocoa (C++11):star2:](http://github.com/r-lyeh/cocoa) <a href="https://travis-ci.org/r-lyeh-archived/cocoa"><img src="https://api.travis-ci.org/r-lyeh-archived/cocoa.svg?branch=master" align="right" /></a> <br/> *hashing library* that provides interface for CRC32, CRC64, GCRC, RS, JS, PJW, ELF, BKDR, SBDM, DJB, DJB2, BP, FNV, AP, BJ1, MH2, SHA1, SFH.
encoding|[Collage (C++03)](https://github.com/r-lyeh/collage) <a href="https://travis-ci.org/r-lyeh-archived/collage"><img src="https://api.travis-ci.org/r-lyeh-archived/collage.svg?branch=master" align="right" /></a> <br/> lightweight library to *diff and patch* arbitrary data.
unit-testing|[Dessert (C++11):star2:](http://github.com/r-lyeh/dessert) <a href="https://travis-ci.org/r-lyeh-archived/dessert"><img src="https://api.travis-ci.org/r-lyeh-archived/dessert.svg?branch=master" align="right" /></a> <br/> lightweight *unit-testing framework*.
debug|[Dollar (C++11)](https://github.com/r-lyeh/dollar) <a href="https://goo.gl/nR594V"><img src="https://goo.gl/OtOjg4" align="right" /></a> <br> portable/generic *CPU profiler* with chrome://tracing support.
debug|[DrEcho (C++11)](http://github.com/r-lyeh/DrEcho) <a href="https://travis-ci.org/r-lyeh-archived/DrEcho"><img src="https://api.travis-ci.org/r-lyeh-archived/DrEcho.svg?branch=master" align="right" /></a> <br/> DrEcho *spices your terminal up*.
debug|[Error64 (C,C++)](http://github.com/r-lyeh/error64) <a href="https://travis-ci.org/r-lyeh-archived/error64"><img src="https://api.travis-ci.org/r-lyeh-archived/error64.svg?branch=master" align="right" /></a> <br/> Handle custom 64-bit error codes, with extended meta-info
gameplay|[Flare (C++03)](https://github.com/r-lyeh/flare) <a href="https://travis-ci.org/r-lyeh-archived/flare"><img src="https://api.travis-ci.org/r-lyeh-archived/flare.svg?branch=master" align="right" /></a> <br/> lightweight C++ API to deal with *digital signals/logical buttons*.
network|[Flow (C++11)](https://github.com/r-lyeh/flow) <a href="https://travis-ci.org/r-lyeh-archived/flow"><img src="https://api.travis-ci.org/r-lyeh-archived/flow.svg?branch=master" align="right" /></a> <br/> lightweight network downloader with native fallbacks aimed to gamedev.
text|[Fmt11 (C++11)](http://github.com/r-lyeh/fmt11) <a href="https://travis-ci.org/r-lyeh-archived/fmt11"><img src="https://api.travis-ci.org/r-lyeh-archived/fmt11.svg?branch=master" align="right" /></a> <br/> tiny *format/mustache templating* library.
gameplay|[Frodo (C++11)](https://github.com/r-lyeh/frodo) <a href="https://travis-ci.org/r-lyeh-archived/frodo"><img src="https://api.travis-ci.org/r-lyeh-archived/frodo.svg?branch=master" align="right" /></a> <br/> lightweight *ring dependency framework*.
gameplay|[FSM (C++11)](http://github.com/r-lyeh/fsm) <a href="https://travis-ci.org/r-lyeh-archived/fsm"><img src="https://api.travis-ci.org/r-lyeh-archived/fsm.svg?branch=master" align="right" /></a> <br/> lightweight Hierarchical/*Finite-State Machine* (H/FSM) class.
io|[GetOpt (C++11)](http://github.com/r-lyeh/getopt) <a href="https://travis-ci.org/r-lyeh-archived/getopt"><img src="https://api.travis-ci.org/r-lyeh-archived/getopt.svg?branch=master" align="right" /></a> <br/> simple *command-line options handler*.
io|[Giant (C++11)](http://github.com/r-lyeh/giant) <a href="https://travis-ci.org/r-lyeh-archived/giant"><img src="https://api.travis-ci.org/r-lyeh-archived/giant.svg?branch=master" align="right" /></a> <br/> tiny library to *handle little/big endianness*.
debug|[Heal (C++03)](http://github.com/r-lyeh/heal) <a href="https://travis-ci.org/r-lyeh-archived/heal"><img src="https://api.travis-ci.org/r-lyeh-archived/heal.svg?branch=master" align="right" /></a> <br/> lightweight library to aid and *debug applications*.
render|[Hertz (C++11)](https://github.com/r-lyeh/Hertz)<a href="https://travis-ci.org/r-lyeh-archived/Hertz"><img src="https://api.travis-ci.org/r-lyeh-archived/hertz.svg?branch=master" align="right" /></a> <br/> simple *framerate locker*.
input|[Hyde (C++03)](http://github.com/r-lyeh/hyde) <br/> lightweight and simple Human *Inferface Device* (HID) library.
hashing|[ID (C++11)](http://github.com/r-lyeh/id) <a href="https://travis-ci.org/r-lyeh-archived/id"><img src="https://api.travis-ci.org/r-lyeh-archived/id.svg?branch=master" align="right" /></a> <br/> simple *compile-time hasher* and sequential ID generator.
mesh, tool|[Img2Sky (Win32)](http://github.com/r-lyeh/img2sky) <br/> *vertex-color mesh builder tool* for skyboxes and static geometry.
io|[Journey (C++11)](http://github.com/r-lyeh/journey) <a href="https://travis-ci.org/r-lyeh-archived/journey"><img src="https://api.travis-ci.org/r-lyeh-archived/journey.svg?branch=master" align="right" /></a> <br/> lightweight *append-only, header-less, journaling file format*.
spec|[JXML](http://github.com/r-lyeh/JXML) <br/> loss-less representation of *JSON in XML*.
spec|[JXMLex](http://github.com/r-lyeh/JXMLex) <br/> expressive representation of *JSON in XML*.
network|[Knot (C++03)](http://github.com/r-lyeh/knot) <a href="https://travis-ci.org/r-lyeh-archived/knot"><img src="https://api.travis-ci.org/r-lyeh-archived/knot.svg?branch=master" align="right" /></a> <br/> lightweight and simple *TCP networking* C++ library.
gameplay|[Kult (C++11):star2:](https://github.com/r-lyeh/kult) <a href="https://travis-ci.org/r-lyeh-archived/kult"><img src="https://api.travis-ci.org/r-lyeh-archived/kult.svg?branch=master" align="right" /></a> <br/> lightweight *entity/component/system* library.
gameplay|[Live (C++11)](http://github.com/r-lyeh/live) <a href="https://travis-ci.org/r-lyeh-archived/live"><img src="https://api.travis-ci.org/r-lyeh-archived/live.svg?branch=master" align="right" /></a> <br/> *automatic reloader* of variables, featuring type inference.
data-structures|[LRU (C++11)](https://github.com/r-lyeh/lru) <a href="https://travis-ci.org/r-lyeh-archived/LRU"><img src="https://api.travis-ci.org/r-lyeh-archived/LRU.svg?branch=master" align="right" /></a> <br/> lightweight *LRU cache structure* for list<T> and map<K,V> containers.
gameplay|[Memo (C++11)](http://github.com/r-lyeh/memo) <a href="https://travis-ci.org/r-lyeh-archived/memo"><img src="https://api.travis-ci.org/r-lyeh-archived/memo.svg?branch=master" align="right" /></a> <br/> simple and lightweight *factory class*, featuring automatic type casting.
stats|[Metrics (C++11)](https://github.com/r-lyeh/metrics) <a href="https://goo.gl/l0C5wv"><img src="https://goo.gl/bn24Kq" align="right" /></a> <br/> table metrics w/ benchmarking, unit conversions in CSV,TSV,ASCII,markdown.
io|[mINI (C++11)](https://github.com/r-lyeh/mINI)<a href="https://travis-ci.org/r-lyeh-archived/mINI"><img src="https://api.travis-ci.org/r-lyeh-archived/mINI.svg?branch=master" align="right" /></a> <br/> very minimal *.INI reader/writer*.
data-structures|[Oak (C++03)](http://github.com/r-lyeh/oak) <a href="https://goo.gl/l2IoOI"><img src="https://goo.gl/8YevhJ" align="right" /></a> <br/> simple and lightweight *tree container*.
design|[Pitch (Markdown)](https://github.com/r-lyeh/pitch) <br/> forkable game *pitch template*.
spec,tool,image|[Pug](https://github.com/r-lyeh/pug) <br/> *pug, png with a twist*: lossy image format.
network|[Route66 (C++03)](https://github.com/r-lyeh/route66) <a href="https://goo.gl/rE1dM1"><img src="https://goo.gl/TD7UpH" align="right" /></a> <br/> lightweight *embeddable HTTP server*.
io|[Quant (C++03)](https://github.com/r-lyeh/quant) <a href="https://goo.gl/gSHXKv"><img src="https://goo.gl/Kuv8pn" align="right" /></a> <br/> *quantization suite* to/from half-floats, s/unorm bytes, quats and vec3s.
time|[Sand (C++11)](http://github.com/r-lyeh/sand) <a href="https://travis-ci.org/r-lyeh-archived/sand"><img src="https://api.travis-ci.org/r-lyeh-archived/sand.svg?branch=master" align="right" /></a> <br/> lightweight *timer controller*.
script|[Scriptorium:star:](https://github.com/r-lyeh/scriptorium) <br/> Game *Scripting Languages benchmarked*.
data|[Sentry (C++11)](https://github.com/r-lyeh/sentry) <a href="https://travis-ci.org/r-lyeh-archived/sentry"><img src="https://api.travis-ci.org/r-lyeh-archived/sentry.svg?branch=master" align="right" /></a> <br/> lightweight *data monitor*.
hashing|[Sole (C++11):star2:](http://github.com/r-lyeh/sole) <a href="https://travis-ci.org/r-lyeh-archived/sole"><img src="https://api.travis-ci.org/r-lyeh-archived/sole.svg?branch=master" align="right" /></a> <br/> lightweight library to generate universally *unique identificators* (UUID) both v1 and v4.
image|[Spot (C++11):star2:](http://github.com/r-lyeh/spot) <a href="https://travis-ci.org/r-lyeh-archived/spot"><img src="https://api.travis-ci.org/r-lyeh-archived/spot.svg?branch=master" align="right" /></a> <br/> compact and embeddable RGBA/HSLA library that supports *WEBP, JPG, progressive JPG, PNG, TGA, DDS DXT1/2/3/4/5, BMP, PSD, GIF, PVR2/3 (ETC1/PVRTC), KTX (ETC1/PVRTC), PKM (ETC1), HDR, PIC, PNM (PPM/PGM), CRN, PUG, FLIF, CCZ, EXR and vectorial SVG files*.
databases |[SQLight (C++11)](http://github.com/r-lyeh/sqlight) <a href="https://travis-ci.org/r-lyeh-archived/sqlight"><img src="https://api.travis-ci.org/r-lyeh-archived/sqlight.svg?branch=master" align="right" /></a> <br/> lightweight *MySQL client*.
misc |[TinyBits (C,C++)](http://github.com/r-lyeh/tinybits) <br/> tiny bits and *useful snippets*.
debug|[Tracey (C++11):star2:](http://github.com/r-lyeh/tracey) <a href="https://travis-ci.org/r-lyeh-archived/tracey"><img src="https://api.travis-ci.org/r-lyeh-archived/tracey.svg?branch=master" align="right" /></a> <br/> lightweight and simple C++ memory *leak finder* with no dependencies.
data-structures|[Trie (C++11)](http://github.com/r-lyeh/trie) <a href="https://travis-ci.org/r-lyeh-archived/trie"><img src="https://api.travis-ci.org/r-lyeh-archived/trie.svg?branch=master" align="right" /></a> <br/> lightweight and simple *autocompletion* data structure.
animation |[Tween (C++03)](https://github.com/r-lyeh/tween) <a href="https://travis-ci.org/r-lyeh-archived/tween"><img src="https://api.travis-ci.org/r-lyeh-archived/tween.svg?branch=master" align="right" /></a> <br/> lightweight *easing library*.
data-structures|[Unordered_map (C++11)](http://github.com/r-lyeh/unordered_map) <a href="https://travis-ci.org/r-lyeh-archived/unordered_map"><img src="https://api.travis-ci.org/r-lyeh-archived/unordered_map.svg?branch=master" align="right" /></a> <br/> *portable header* for std::unordered_map<K,V> template.
debug|[Unifont (C++11)](http://github.com/r-lyeh/unifont) <a href="https://travis-ci.org/r-lyeh-archived/unifont"><img src="https://api.travis-ci.org/r-lyeh-archived/unifont.svg?branch=master" align="right" /></a> <br/> *embeddable console 1bpp font*.
spec, io|[Unify (C++11)](http://github.com/r-lyeh/Unify) <a href="https://travis-ci.org/r-lyeh-archived/unify"><img src="https://api.travis-ci.org/r-lyeh-archived/unify.svg?branch=master" align="right" /></a> <br/> a function to *normalize resouce identificators*.
network|[VLE (C99, C++03)](https://github.com/r-lyeh/vle) <a href="https://travis-ci.org/r-lyeh-archived/vle"><img src="https://api.travis-ci.org/r-lyeh-archived/vle.svg?branch=master" align="right" /></a> <br/> simple *variable-length encoder/decoder*.
audio|[Wave (C++11)](http://github.com/r-lyeh/wave) <br/> lightweight *3D sound wrapper* for OpenAL that supports OGG and MusePack decoding.
utils|[Warp (C++11):star2:](http://github.com/r-lyeh/warp) <a href="https://travis-ci.org/r-lyeh-archived/warp"><img src="https://api.travis-ci.org/r-lyeh-archived/warp.svg?branch=master" align="right" /></a> <br/> a handy *string interpolator*.
text|[Wire (C++11):star2:](http://github.com/r-lyeh/wire) <a href="https://travis-ci.org/r-lyeh-archived/wire"><img src="https://api.travis-ci.org/r-lyeh-archived/wire.svg?branch=master" align="right" /></a> <br/> a drop-in *std::string replacement* with extended functionality and safe C/C++ formatters.

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

* [AVA](https://github.com/r-lyeh/AVA) -- tiny *3D game engine* in C++, with C and Lua interfaces.
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
