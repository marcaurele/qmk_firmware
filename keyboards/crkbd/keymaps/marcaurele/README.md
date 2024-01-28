# My CRKBD keymap

## Operations

```console
# Clean compile
qmk compile --clean -kb crkbd/rev1 -km marcaurele

# Flash (for each unit)
qmk flash -kb crkbd/rev1 -km marcaurele

# Generate the JSON mapping
qmk c2json -kb crkbd/rev1 -km marcaurele
```
