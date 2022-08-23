# Business Administration

Notes on Business Administration

## Installation

Clone with submodules:

```
$ git clone --recurse-submodules https://github.com/mbpnotepad/business.git
```

Alternatively, clone first and then update submodules:

```
$ git clone https://github.com/mbpnotepad/business.git
$ cd business
$ git submodule update --init --recursive
```

## Compilation

Serve:

```
$ hugo server --renderToDisk --cleanDestinationDir --noHTTPCache --destination build/public --cacheDir $PWD/build/cache
```

Static:

```
build/hugo/hugo --cacheDir $PWD/build/cache --destination build/public
```
