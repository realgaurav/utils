## utils: scripts, tools et. al.

A compiled list of tips/tricks repo.

* CLI for dictionary lookup (requires curl)

```
dict() {
     curl dict://dict.org/d:$1
}
```

TODO: format output, add options for foldoc

* Delete lines in files using sed

```
sed -i '<START>,<END>d' <FILENAME>
```
