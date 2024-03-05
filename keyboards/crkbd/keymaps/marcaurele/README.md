# My CRKBD keymap

## Operations

```console
pipenv install qmk

# To install all depedencies
pipenv run qmk setup

# Set default options
pipenv run qmk config user.keyboard=crkbd/rev1 user.keymap=marcaurele

# Clean compile
pipenv run qmk compile --clean -kb crkbd/rev1 -km marcaurele
pipenv run qmk compile --clean

# Flash (for each unit)
pipenv run qmk flash -kb crkbd/rev1 -km marcaurele

# Generate the JSON mapping
pipenv run qmk c2json -kb crkbd/rev1 -km marcaurele
```
