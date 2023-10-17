# Anna Freud's Custom TiddlyWiki Tour

Build with:

```
tiddlywiki ./wiki --build index
```

The output file `index.html` will be in the `./wiki/output` folder.

Upload to TiddlyHost with:

```
./bin/thost-uploader annafreud-manuals-tour wiki/output/index.html jeremy.ruston@gmail.com $(cat ~/.thostpass)
```
