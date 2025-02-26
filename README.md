# 3p-xxhash

[Autobuild][] packaged [xxhash][].

[Autobuild]: https://github.com/secondlife/autobuild
[xxhash]: https://github.com/Cyan4973/xxHash

## Submodules

This repository vendors xxhash using submodules. Be sure to pull them when cloning or updating this repository.

Fresh clone:
```
git clone --recurse-submodules https://github.com/AlchemyViewer/3p-xxhash.git
```

Existing checkout:
```
git submodule update --init --recursive
```