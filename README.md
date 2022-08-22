# Business Administration

## Compilation

Serve:

```
$ hugo server --renderToDisk --cleanDestinationDir --noHTTPCache --destination build/public --cacheDir $PWD/build/cache --themesDir build/themes
```

Static:

```
build/hugo/hugo --cacheDir /mnt/nfs/home/perez_m/usr/src/simverse/core/build/hugo/doc/generated --config build/hugo/hugo_theme/config.toml,build/hugo/doc/config.toml --themesDir build/hugo/hugo_theme/themes --destination build/hugo/doc/generated/public
```
