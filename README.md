# GFM [![Build Status](https://travis-ci.org/d-gamedev-team/gfm.png?branch=master)](https://travis-ci.org/d-gamedev-team/gfm)

<img alt="logo" src="https://cdn.combinatronics.com/p0nce/gfm/master/logo.svg" width="200">


**IMPORTANT: GFM has been stripped down to gfm:math and gfm:integers only. Use version 7 if you want the former content.**

See the changelog here to upgrade: [https://github.com/d-gamedev-team/gfm/wiki/Changelog](https://github.com/d-gamedev-team/gfm/wiki/Changelog)


## License

Public Domain (Unlicense).


## How to use GFM?

Add the sub-package you are interested in in your `dub.json`:
```d
   {
      "dependencies": {
        "gfm:math": "~>8.0"
      }
   }
```

## Changelog

https://github.com/d-gamedev-team/gfm/wiki/Changelog

## Why use GFM?
  * GFM provides math primitives that are useful for games like vectors/matrices/quaternions in the `gfm:math` package,
  * Also provide arbitrary sized integers, fixed point numbers, and half-float numbers in `gfm:integers`,


## Dependencies

You absolutely don't need to use the whole of GFM. Pick just the **sub-package** you need to minimize the amount of dependencies and code compiled.

There is an ongoing work to delete things in GFM that exist elsewhere but better.
See http://code.dlang.org to discover lots of useful libraries for your programs.

So you'll find that GFM actually decreases in size over time.

