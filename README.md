# elm-format

`elm-format` is the official source code formatter for Elm.


## Basic Usage

```bash
elm-format Main.elm
```


## Development info

### Building

Install the Elm platform from source using the BuildFromSource.hs script, then:

```bash
cd Elm-Platform/master
git clone https://github.com/avh4/elm-format.git
cd elm-format
cabal sandbox init --sandbox=..
cabal install -j
```

### Running tests

After installing with the instructions above:

```bash
./tests/run-tests.sh
```